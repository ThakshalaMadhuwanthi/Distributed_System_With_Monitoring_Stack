
📦 Distributed System with Monitoring Stack
📌 Overview

This project demonstrates a containerized distributed system using Docker, NGINX, and a full monitoring stack (Prometheus, Grafana, cAdvisor). It is designed to illustrate key concepts in distributed systems such as:

Access Transparency
Location Transparency
Replication Transparency
Concurrency Transparency
System Monitoring & Observability

The system simulates multiple web servers behind a load balancer and provides real-time performance monitoring.

🏗️ Architecture

The system consists of:

Load Balancer (NGINX)
Web Servers (web1, web2, web3)
Monitoring Stack
Prometheus (metrics collection)
Grafana (visualization)
cAdvisor (container monitoring)
Flow:
Client → NGINX Load Balancer → Web Servers (replicas)
                           ↓
                 Prometheus + cAdvisor → Grafana Dashboard
🚀 Features
✔ Distributed System Concepts
Access Transparency (single entry point)
Location Transparency (hidden backend servers)
Replication Transparency (multiple replicas of web service)
Concurrency Transparency (multiple simultaneous users)
✔ Monitoring Stack
Real-time container monitoring
CPU & memory usage tracking
Grafana dashboards for visualization
Prometheus metrics scraping
🐳 Tech Stack
Docker & Docker Compose
NGINX (Load Balancer)
Prometheus
Grafana
cAdvisor
Linux (Ubuntu / EC2)
