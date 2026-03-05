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

<img width="998" height="321" alt="image" src="https://github.com/user-attachments/assets/93ccffac-a5d9-4535-82bd-89d0b44cecb6" />

<img width="805" height="381" alt="image" src="https://github.com/user-attachments/assets/2f6cf7ca-b845-40c6-999d-681fa9c7fb4a" />

<img width="1132" height="552" alt="image" src="https://github.com/user-attachments/assets/4b686254-0332-4ef3-b9c1-1d57cf345860" />

<img width="1086" height="437" alt="image" src="https://github.com/user-attachments/assets/73021d4e-9bbf-46b4-a75e-8c8d1294bb61" />


<img width="1102" height="528" alt="image" src="https://github.com/user-attachments/assets/88cbc0e1-f871-43c1-a377-b30875dc098a" />

<img width="1082" height="420" alt="image" src="https://github.com/user-attachments/assets/ecf90eaf-017a-4a3c-acb8-a3995d67ec9a" />

<img width="975" height="498" alt="image" src="https://github.com/user-attachments/assets/d7df89c9-a16d-4441-8f40-5b5fe0d8a3cc" />
