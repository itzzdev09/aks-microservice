# Scalable Microservice with Docker and K6 Testing

## 📌 Project Overview
This project demonstrates how to build, containerize, and test a microservice using Docker and K6.  
It simulates a cloud-native workflow, making it easy to later extend into Kubernetes (AKS) with Helm, HPA, and CI/CD.

## 🏗️ Tech Stack
- **Containerization:** Docker  
- **Backend:** Node.js (Express server)  
- **Performance Testing:** K6  
- **Version Control:** Git + GitHub  

## 🚀 Steps to Run
1. Build the Docker image:
   ```sh
   docker build -t my-microservice ./docker-microservice
2. Run the container:
   ```sh
   docker run -p 8080:80 my-microservice
3. Test with K6:
   ```sh
   k6 run test.js

