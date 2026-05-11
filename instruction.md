# End-to-End DevOps EKS Blog Application

## Project Objective

This project demonstrates a complete DevOps CI/CD pipeline using AWS EKS, Terraform, Jenkins, Docker, Kubernetes, SonarQube, Nexus, Trivy, Prometheus, and Grafana.

## Architecture Flow

Developer → GitHub → Jenkins → SonarQube → Trivy → Nexus → Docker → Kubernetes (EKS) → Prometheus → Grafana

## Tools Used

- GitHub
- Jenkins
- Docker
- Kubernetes
- AWS EKS
- Terraform
- SonarQube
- Nexus
- Trivy
- Prometheus
- Grafana

## Goals

- Automate application deployment
- Implement CI/CD pipeline
- Perform security scanning
- Monitor Kubernetes workloads
- Learn Infrastructure as Code

## 2. Add this to `instruction.md`

```markdown
# Project Progress Notes

## Completed Steps

### Step 1: Project Structure
Created folders for app, Docker, Kubernetes, Jenkins, Terraform, monitoring, Nexus, SonarQube, and Trivy.

### Step 2: Flask Application
Created a simple Flask application and tested it locally on port 5000.

### Step 3: Dockerized Application
Created a Dockerfile, built the Docker image, and ran the application as a container.

### Step 4: Docker Hub Push
Tagged and pushed the image to Docker Hub:

```text
spandanaerukulla/flask-devops-app:latest