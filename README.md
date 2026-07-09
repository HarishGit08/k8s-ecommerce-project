# 🚀 Kubernetes eCommerce Platform with CI/CD & Monitoring

A production-style DevOps project demonstrating the deployment of a containerized eCommerce application on a multi-node Kubernetes cluster with CI integration using Jenkins and monitoring using Prometheus & Grafana.

---

# 📌 Project Overview

This project showcases an end-to-end DevOps workflow where a containerized backend application is deployed on a Kubernetes cluster running on AWS EC2 instances. The infrastructure includes Jenkins for Continuous Integration, Docker for containerization, Kubernetes for orchestration, and Prometheus & Grafana for monitoring.

---

# 🏗️ Architecture

```
                    GitHub Repository
                           │
                           ▼
                      Jenkins Pipeline
                           │
                           ▼
                   Source Code Checkout
                           │
                           ▼
                    Docker Image Build
                           │
                           ▼
                     Docker Hub Registry
                           │
                           ▼
              Kubernetes Multi-Node Cluster
          ┌──────────────────────────────────┐
          │          Master Node             │
          │      Kubernetes Control Plane    │
          └──────────────────────────────────┘
                   │                │
                   ▼                ▼
            Worker Node 1     Worker Node 2
           Frontend Pods      Backend + MySQL

                           │
                           ▼
                 Prometheus + Grafana
```

---

# ⚙️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Cloud | AWS EC2 |
| Operating System | Ubuntu Linux |
| Containerization | Docker |
| Container Registry | Docker Hub |
| Orchestration | Kubernetes (kubeadm) |
| CI | Jenkins |
| Monitoring | Prometheus & Grafana |
| Version Control | Git & GitHub |
| Backend | Node.js + Express |
| Web Server | Nginx |

---

# 📂 Project Structure

```
k8s-ecommerce-project/
│
├── backend/
│   ├── app/
│   ├── backend-deployment.yaml
│   ├── backend-service.yaml
│   ├── backend-configmap.yaml
│   └── backend-secret.yaml
│
├── frontend/
│
├── mysql/
│
├── ingress/
│
├── jenkins/
│
├── monitoring/
│
├── screenshots/
│
├── Jenkinsfile
│
└── README.md
```

---

# ✨ Features

- Multi-node Kubernetes Cluster
- Dockerized Backend Application
- Jenkins CI Pipeline
- GitHub Integration
- Docker Hub Integration
- Kubernetes Deployments
- Kubernetes Services
- ConfigMaps
- Secrets
- Persistent Volumes
- Persistent Volume Claims
- Ingress Controller
- Prometheus Monitoring
- Grafana Dashboards

---

# 🚀 Deployment Workflow

1. Clone the repository
2. Configure Kubernetes cluster
3. Deploy MySQL
4. Deploy Backend
5. Deploy Frontend
6. Configure Services
7. Configure Ingress
8. Deploy Jenkins
9. Configure Monitoring
10. Verify Application

---

# 🔄 CI Pipeline

Current Pipeline:

```
GitHub
   │
   ▼
Jenkins
   │
   ▼
Checkout Source Code
   │
   ▼
Verify Project Files
   │
   ▼
Pipeline Success
```

Future Enhancement:

```
GitHub
   │
   ▼
Jenkins
   │
   ▼
Build Docker Image
   │
   ▼
Push Image to Docker Hub
   │
   ▼
Deploy to Kubernetes
```

---

# 📊 Monitoring

Monitoring is implemented using:

- Prometheus
- Grafana

Metrics include:

- Node Health
- CPU Usage
- Memory Usage
- Pod Status
- Kubernetes Cluster Metrics

---

# 📸 Project Screenshots

## GitHub Repository

![GitHub](screenshots/github-home.png)

---

## Jenkins Dashboard

![Jenkins Dashboard](screenshots/jenkins-dashboard.png)

---

## Jenkins Pipeline

![Pipeline](screenshots/jenkins-pipeline.png)

---

## Docker Hub Repository

![DockerHub](screenshots/dockerhub.png)

---

## Kubernetes Nodes

![Nodes](screenshots/k8s-nodes.png)

---

## Kubernetes Pods

![Pods](screenshots/k8s-pods.png)

---

## Kubernetes Services

![Services](screenshots/k8s-services.png)

---

## Grafana Dashboard

![Grafana](screenshots/grafana-dashboard.png)

---

## Application

![Application](screenshots/application.png)

---

# 💡 Challenges Faced

- Configuring a multi-node Kubernetes cluster using kubeadm
- Managing Persistent Volumes and Persistent Volume Claims
- Deploying Jenkins on Kubernetes
- Configuring Docker image builds
- Integrating GitHub with Jenkins
- Troubleshooting Kubernetes networking and deployments

---

# 🎯 Future Enhancements

- Fully Automated CI/CD Pipeline
- Docker Build & Push from Jenkins
- Automated Kubernetes Deployment
- Helm Charts
- ArgoCD
- SonarQube Integration
- Trivy Image Scanning
- Slack Notifications

---

# 👨‍💻 Author

**Harish Korapati**

DevOps | AWS | Docker | Kubernetes | Jenkins | Linux

GitHub:
https://github.com/HarishGit08

Docker Hub:
https://hub.docker.com/u/harishkorapati

---

⭐ If you found this project useful, feel free to star the repository.
