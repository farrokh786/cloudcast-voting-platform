# cloudcast-voting-platform
A scalable microservices-based voting and analytics platform built on Azure Devops, docker, azurecloud, redis/postgresql
# 🌩️ CloudCast Voting Platform



A 3-tier microservices application built with Python, .NET, and Node.js — containerized using Docker and deployed via CI/CD pipelines on Azure DevOps. Designed to simulate real-time sentiment analysis with a cloud-native DevOps pipeline.



---



## 🔧 Tech Stack



- **Frontend**: Python (Flask)  

- **Worker**: .NET 7.0 (Background vote processor)  

- **Result App**: Node.js (Live dashboard)  

- **Database**: PostgreSQL  

- **Messaging Queue**: Redis  

- **CI/CD**: Azure DevOps (YAML pipelines), Self-hosted Linux Agent  

- **Containerization**: Docker  

- **Registry**: Azure Container Registry (ACR)  

- **Infrastructure**: Azure VM (Ubuntu), Docker Compose



## 🚀 Features



- Real-time vote submission and result display

- Separate microservices for frontend, worker, and dashboard

- Dockerized services for isolated deployments

- Azure DevOps pipelines for build and push (per microservice)

- Images stored and versioned in ACR

- Self-hosted agents on Azure VM for cost-efficient execution


 
## 📦 How to Run Locally
Requires Docker & Docker Compose
bash

docker compose u
