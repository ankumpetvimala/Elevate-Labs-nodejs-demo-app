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
     📦 `pravalika27/nodejs-demo-app:latest`

---


