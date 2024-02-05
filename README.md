# Appv1 Dockerized Application for book "Cloud Native CI/CD with Tekton & ArgoCD"

This repository is part of the project for the book "Cloud Native CI/CD with Tekton & ArgoCD." 
It contains the source code for a simple Dockerized web application named Appv1.

## Files
1. **Dockerfile:**
   - Purpose: Describes the steps to build a Docker image for the Appv1 application.
   - How to use: Execute `docker build -t appv1:latest .` to build the Docker image.

2. **index.html:**
   - Purpose: Contains the HTML code for the static web page served by the Appv1 application.
   - How to use: No direct action needed. This file is automatically included in the Docker image during the build process.

Feel free to explore and modify the code according to your needs. Happy coding!

## Note
For Kubernetes manifests related to deploying this application, please check the [kubernetes-manifests](https://github.com/arunvel1988/kubernetes-manifests) repository in the same project.
