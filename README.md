# Trend Store – DevOps Deployment Project

## Project Overview
This project demonstrates end-to-end deployment of a React application using
Docker, Kubernetes (AWS EKS), and Jenkins CI/CD.

## Tech Stack
- React (Static Build)
- Docker & DockerHub
- AWS EKS
- Kubernetes
- Jenkins CI/CD
- Nginx
- GitHub

## Architecture
Developer → GitHub → Jenkins → DockerHub → EKS → AWS LoadBalancer → User

## Application URL
http://ab6d30b8f93f64d13a247f5495e786a6-900030035.ap-south-1.elb.amazonaws.com

## CI/CD Flow
1. Code push to GitHub
2. Jenkins pipeline triggered
3. Docker image built
4. Image pushed to DockerHub
5. Kubernetes deployment updated in EKS

## Kubernetes
- Deployment: 2 replicas
- Service type: LoadBalancer

## Jenkins
- Declarative pipeline
- Docker + Kubernetes integration
- Credentials managed securely

## Screenshots
[screeshot.docx](https://github.com/user-attachments/files/24335848/screeshot.docx)


## Conclusion
This project demonstrates real-world DevOps practices including containerization,
CI/CD automation, and Kubernetes deployment on AWS.
