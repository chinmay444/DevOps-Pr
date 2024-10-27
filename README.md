# DevOps-Pr 
**CI/CD Workflow
![IMG_20241027_232824](https://github.com/user-attachments/assets/0254af40-5aa9-4b00-aa84-5c164fd60edf)

# CI/CD Pipeline with Jenkins, SonarQube, and Docker

This guide outlines a simple CI/CD pipeline using Jenkins, SonarQube, and Docker.

## Workflow Overview

1. **Developer**: Write code and push it to the GitHub repository.
2. **GitHub**: GitHub triggers a Jenkins job using webhooks.
3. **Jenkins**: Jenkins automates the CI/CD pipeline:
   - Pulls code from GitHub.
   - Sends code to **SonarQube** for quality checks.
   - Builds and packages code using **Docker** for deployment.
4. **SonarQube**: Provides code quality analysis feedback.
5. **Docker**: Builds an image for consistent deployment.

## Setup Instructions

1. **Install Jenkins** on a server and configure GitHub Webhooks.
2. **Install SonarQube** on a server and integrate it with Jenkins.
3. **Install Docker** on the Jenkins server for building and deploying containers.
