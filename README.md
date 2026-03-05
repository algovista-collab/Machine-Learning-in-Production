# Machine-Learning-in-Production
Designing an ML Production System end-to-end

<img width="1178" height="353" alt="image" src="https://github.com/user-attachments/assets/3da3f942-3495-4d10-8e6e-471357a581b6" />

Concept Drift is when for example size of the house doesn't change but the price changes because of the inflation. In the input distribution changes, that is size of the house changes but relationship between the x and y will not change. This is called Data drift. Data drift refers to the shifts in input feature distributions, whereas concept drift refers to shifts in the relationships between model inputs and outputs. 

<img width="716" height="493" alt="image" src="https://github.com/user-attachments/assets/4acfef6d-06b0-45cb-86d7-5807b6f0bb7b" />

<img width="666" height="525" alt="image" src="https://github.com/user-attachments/assets/ca56b7f3-af98-4f8e-9826-f2534429257b" />

| Feature | Shadow Deployment | Canary Deployment | Blue-Green Deployment |
| :--- | :--- | :--- | :--- |
| **User Impact** | None (Silent) | Small % affected | All users (post-switch) |
| **Traffic Split** | 100% (Duplicated) | Incremental (5% -> 100%) | Binary (0% or 100%) |
| **Rollback** | N/A | Fast | **Instant** |
| **Infrastructure** | High (2x inference) | Low | **Highest** (2x environments) |
| **Best For** | Testing accuracy | Risk mitigation | Zero-downtime releases |


<img width="1011" height="462" alt="image" src="https://github.com/user-attachments/assets/efb75711-0d09-421e-87a2-e6ab88893e56" />
