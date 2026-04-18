# 🚀 End-to-End DevOps CI/CD Pipeline with Monitoring on AWS

## 📌 Project Overview
This project demonstrates a complete DevOps workflow including application deployment, CI/CD automation, containerization, reverse proxy setup, and real-time infrastructure monitoring on AWS EC2.

## 🏗️ Architecture
GitHub → CI/CD → EC2 → Docker → Nginx → Application
↓
Node Exporter → Prometheus → Grafana

## ⚙️ Tech Stack

- Cloud: AWS EC2
- Containerization: Docker
- Web Server: Nginx
- CI/CD: GitHub Actions / Jenkins
- Monitoring: Prometheus, Grafana, Node Exporter
- OS: Ubuntu
- Domain + SSL: Hostinger + Certbot
  
## 🚀 Features

- Automated application deployment
- Docker containerized application
- Nginx reverse proxy setup
- HTTPS secured domain
- CI/CD pipeline integration
- Real-time system monitoring
- Dashboard visualization using Grafana

## 📊 Monitoring Setup

  ### Prometheus
     - Collects system metrics from Node Exporter
     - Endpoint: `http://13.205.142.11:9090`

  ### Grafana
     - Visualizes metrics in dashboards
     - Endpoint: `http://13.205.142.11:3000`

## 🌐 Live Project

- Application: https://devopsproject.online
- Prometheus: http://13.205.142.11:9090/targets
- Grafana: http://13.205.142.11:3000

## 🧠 Key Learnings

- AWS EC2 deployment
- Docker containerization
- CI/CD automation
- Reverse proxy configuration
- Monitoring and alerting systems
- 
## 👨‍💻 Author

Vignesh Albert  
DevOps & Cloud Enthusiast
