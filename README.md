#  Node.js CI/CD Task

This repository contains my solution for **DevOps Internship Task 1: Automating the deployment of a Node.js application using GitHub Actions**.

---

## What I Did

- Created a basic **Node.js** app (`app.js`)
- Wrote a **Dockerfile** to containerize the app
- Configured a **CI/CD pipeline using GitHub Actions**
- Automated the build and push of Docker images to **DockerHub**

---

##  How It Works

1. Push any changes to the `main` branch.
2. GitHub Actions automatically:
   - Builds a new Docker image
   - Tags it as `latest`
   - Pushes it to DockerHub at:  
      `ankumpetavimala/nodejs-demo-app:latest`

##  Files
 
 app.js: The Node.js application.
 Dockerfile: Docker configuration.
 .github/workflows/main.yml: CI/CD pipeline.

##  How to Test
 Run this on any machine with Docker:

docker pull ankumpetavimala/nodejs-demo-app:latest
docker run -d -p 3000:3000 ankumpetavimala/nodejs-demo-app:latest
     

---


