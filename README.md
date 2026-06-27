
📦 Distributed System with Monitoring Stack
📌 Overview

This project is a containerized distributed system built using Docker and NGINX, demonstrating key concepts of distributed systems along with a full monitoring stack for observability.

The system simulates multiple backend web servers behind a load balancer and integrates real-time monitoring using Prometheus, Grafana, and cAdvisor.

🏗️ System Architecture

The architecture consists of:

NGINX Load Balancer
Multiple Web Server Containers (web1, web2, web3)
Monitoring Stack
Prometheus (metrics collection)
Grafana (visualization)
cAdvisor (container-level monitoring)
🔑 Key Distributed System Concepts Implemented
✔ Access Transparency

Users interact with a single endpoint through a load balancer without knowing backend server details.

✔ Location Transparency

Backend server locations and container details are hidden from users.

✔ Replication Transparency

Multiple identical web server containers operate as a single logical service.

✔ Concurrency Transparency

Multiple users can access the system simultaneously without interference.

📊 Monitoring Stack

The system includes a full observability layer:

Prometheus collects metrics from containers
cAdvisor provides real-time container performance data
Grafana visualizes system metrics through dashboards
🧱 Technologies Used
Docker & Docker Compose
NGINX (Load Balancer)
Prometheus
Grafana
cAdvisor
Linux (Ubuntu / EC2)
