# The Ultimate Guide to Deploying n8n

Welcome to the comprehensive, step-by-step guide on how to deploy **n8n.io** in any environment—from your local computer to Enterprise-grade Kubernetes clusters.

Inspired by the structured approach of "Python for Developers," this repository provides a logical progression from basic setups to high-availability architectures.

---

## 📚 Table of Contents

### Part I: Basic Local Deployments
- **[Chapter 01](./Chapter01/Chapter01_Local_NodeJS_Installation.ipynb)** - Local Installation via Node.js (Windows, Mac, Linux)
- **[Chapter 02](./Chapter02/Chapter02_Local_Docker_Compose.ipynb)** - n8n in Local Docker Compose with Persistent Data
- **[Chapter 03](./Chapter03/Chapter03_PM2_Process_Management.ipynb)** - Running n8n as a Service Using PM2
- **[Chapter 04](./Chapter04/Chapter04_n8n_on_Raspberry_Pi.ipynb)** - Deploying n8n on a Raspberry Pi

### Part II: VPS and Cloud VM Deployments
- **[Chapter 05](./Chapter05/Chapter05_Ubuntu_VPS_NodeJS.ipynb)** - Ubuntu VPS Deployment (Node.js)
- **[Chapter 06](./Chapter06/Chapter06_Ubuntu_VPS_Docker.ipynb)** - Ubuntu VPS Deployment (Docker)
- **[Chapter 07](./Chapter07/Chapter07_Nginx_Reverse_Proxy_HTTPS.ipynb)** - Reverse Proxy with Nginx and SSL (HTTPS)
- **[Chapter 08](./Chapter08/Chapter08_AWS_EC2_Deployment.ipynb)** - Deploying on AWS EC2 Instance
- **[Chapter 09](./Chapter09/Chapter09_DigitalOcean_Droplet.ipynb)** - Deploying on DigitalOcean Droplet
- **[Chapter 10](./Chapter10/Chapter10_Google_Cloud_VM.ipynb)** - Deploying on Google Cloud VM Instance
- **[Chapter 11](./Chapter11/Chapter11_Azure_VM_Instance.ipynb)** - Deploying on Azure VM Instance
- **[Chapter 12](./Chapter12/Chapter12_Private_Tunnels.ipynb)** - Exposing Private n8n via Tunnels (Cloudflare, Tailscale)
- **[Chapter 13](./Chapter13/Chapter13_Render_Heroku_PaaS.ipynb)** - Deploying on Render or Heroku PaaS
- **[Chapter 14](./Chapter14/Chapter14_CapRover_Dokku.ipynb)** - Deploying with CapRover or Dokku

### Part III: Advanced Container & Kubernetes Deployments
- **[Chapter 15](./Chapter15/Chapter15_Docker_Compose_PostgreSQL.ipynb)** - Docker Compose with External PostgreSQL
- **[Chapter 16](./Chapter16/Chapter16_Queue_Mode_Redis.ipynb)** - Scaling with Queue Mode (Postgres and Redis)
- **[Chapter 17](./Chapter17/Chapter17_Docker_Swarm_Cluster.ipynb)** - Docker Swarm Cluster Deployment
- **[Chapter 18](./Chapter18/Chapter18_Kubernetes_Single_Pod.ipynb)** - Kubernetes Deployment (Single Pod)
- **[Chapter 19](./Chapter19/Chapter19_K8s_External_Database.ipynb)** - Kubernetes with Managed External Database
- **[Chapter 20](./Chapter20/Chapter20_K8s_Ingress_SSL.ipynb)** - Kubernetes Ingress and Let’s Encrypt
- **[Chapter 21](./Chapter21/Chapter21_Scaled_K8s_Queue_Mode.ipynb)** - Scaled Kubernetes Architecture (Queue Mode)
- **[Chapter 22](./Chapter22/Chapter22_Helm_Chart_Deployment.ipynb)** - Deploying n8n via Helm Chart
- **[Chapter 23](./Chapter23/Chapter23_AWS_ECS_Fargate.ipynb)** - AWS ECS Fargate Serverless Deployment
- **[Chapter 24](./Chapter24/Chapter24_Google_Cloud_Run.ipynb)** - Google Cloud Run Serverless Deployment
- **[Chapter 25](./Chapter25/Chapter25_Azure_Container_Instances.ipynb)** - Azure Container Instances Deployment
- **[Chapter 26](./Chapter26/Chapter26_HashiCorp_Nomad.ipynb)** - HashiCorp Nomad Deployment

### Part IV: Enterprise and Creative Architectures
- **[Chapter 27](./Chapter27/Chapter27_High_Availability.ipynb)** - High Availability Setup (Horizontal Scaling)
- **[Chapter 28](./Chapter28/Chapter28_MultiRegion_Failover.ipynb)** - Multi-Region Deployment & Disaster Recovery
- **[Chapter 29](./Chapter29/Chapter29_Backup_Restore.ipynb)** - Backup, Restore, and Data Persistence Strategies
- **[Chapter 30](./Chapter30/Chapter30_CICD_GitOps.ipynb)** - CI/CD and GitOps for n8n Deployments
- **[Chapter 31](./Chapter31/Chapter31_Logging_Monitoring.ipynb)** - Centralized Logging and Monitoring (ELK, Grafana)
- **[Chapter 32](./Chapter32/Chapter32_Security_Hardening.ipynb)** - Security Hardening and Best Practices
- **[Chapter 33](./Chapter33/Chapter33_Version_Control.ipynb)** - Workflow Version Control and Team Collaboration

---

## Prerequisites
Before beginning, ensure you have basic knowledge of:
- Command Line (Terminal)
- Basic Networking (DNS, Ports)
- Docker (for Chapters 2 and beyond)

## About this Guide
This repository is a live documentation project. Each chapter contains a Jupyter Notebook with:
1.  **Overview**: What we are deploying.
2.  **Commands**: Ready-to-copy terminal commands.
3.  **Configurations**: YAML/Config files needed for the environment.
4.  **Troubleshooting**: Common issues for that specific setup.
