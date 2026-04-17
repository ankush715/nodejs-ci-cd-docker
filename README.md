# 🚀 Node.js CI/CD Pipeline with Docker

## 📌 Project Overview
This project demonstrates how to build and deploy a Node.js application using Docker and CI/CD pipeline.

---

## ⚙️ Tech Stack
- Node.js
- Docker
- GitHub Actions (CI/CD)
- Linux

---

## 🔄 Workflow
1. Code pushed to GitHub  
2. CI/CD pipeline triggered  
3. Docker image built  
4. Application deployed  

---

## 📁 Project Structure
- app.js → Node.js app  
- Dockerfile → container setup  
- .github/workflows → CI/CD pipeline  

---

## 🚀 How to Run

```bash
docker build -t node-app .
docker run -p 3000:3000 node-app
