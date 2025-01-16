## Networking

Networking was implemented with service type: LoadBalancer

## Cloud provider AWS

# cluster
<img width="1136" alt="image" src="https://github.com/user-attachments/assets/ac9832f0-248f-4082-aa55-6c532e248e71" />

# Resources

# Pod

<img width="1136" alt="image" src="https://github.com/user-attachments/assets/baaeac00-bf37-41b4-9d4b-7de2457f58a4" />

# Service and LoadBalancer

<img width="1136" alt="image" src="https://github.com/user-attachments/assets/0cb5befd-df53-42f1-8440-771683a6e8e5" />

<img width="1305" alt="image" src="https://github.com/user-attachments/assets/7bc9e7e5-0f1b-48a0-ade6-c7330252fda2" />

<img width="1714" alt="image" src="https://github.com/user-attachments/assets/9d1b4030-1de9-4b77-9dbd-f95dbf34b499" />

## Docker Registry - DockerHub

<img width="1305" alt="image" src="https://github.com/user-attachments/assets/f5bc7c09-67ad-4ce0-b775-6554126f510e" />

<img width="1714" alt="image" src="https://github.com/user-attachments/assets/1c89fa5d-2f79-4db1-8ec0-8d637085af3b" />


## Acceptance Criteria:

# Cache

Was implemented with buildx to cache docker layers, and using the file package-lock.json as it helps us to know if the node_modules have changed.

- https://github.com/JsanchezPilo/hi-zealous/blob/main/.github/workflows/deploy.yml#L29

## CI/CD pipeline

# Post-deployment

It was implemented with helm using the feature **wait** as it waits until the new pods are ready, wich help us to validate rollouts

Liveness and Readiness were implemented here: https://github.com/JsanchezPilo/hi-zealous/blob/main/zealous/values.yaml#L96
