# 🛒 Medusa Backend on AWS ECS with Terraform

This project deploys the Medusa.js backend to AWS using **Terraform**, **Docker**, and **ECS Fargate**.  
The backend is containerized, stored on Docker Hub, and deployed with infrastructure as code.

---

## 📦 Tech Stack

- [Medusa.js](https://docs.medusajs.com/) – Headless commerce backend
- Docker – Containerization
- Terraform – Infrastructure as Code
- AWS ECS Fargate – Container orchestration
- AWS RDS – PostgreSQL database

---

## 🚀 Project Setup

### 🐳 Build & Push Docker Image

```bash
# Build Docker image
docker build -t vikky17/medusa-backend:latest .

# Push to Docker Hub
docker push vikky17/medusa-backend:latest


## 📹 Demo Video

[![Watch the video](https://img.youtube.com/vi/lijjoWOcF6o/0.jpg)](https://youtu.be/lijjoWOcF6o)

👉 **[Click here to watch the demo on YouTube](https://youtu.be/lijjoWOcF6o)**
