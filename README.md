# Jenkins & Docker CI/CD Pipeline on AWS

Ci/CD pipeline for a python flask application using Jenkins, Docker, AWS ECR, EC2

<!-- marmaid test i guess-->

```mermaid
flowchart LR
    GitHub --> Jenkins
    Jenkins --> ECR
    ECR --> EC2
```
