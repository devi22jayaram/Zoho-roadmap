# Zoho Nathu La Server – DevOps Notes

## What is Nathu La?

Nathu La is **Zoho's in-house designed server platform** built for its own data centers. Instead of relying entirely on third-party server manufacturers, Zoho designed its own server infrastructure to efficiently run its cloud products, AI workloads, virtualization, and storage services.

---

# Why did Zoho build Nathu La?

* Reduce infrastructure costs.
* Improve performance for Zoho applications.
* Increase power efficiency.
* Optimize hardware for cloud and AI workloads.
* Gain complete control over the hardware and software stack.
* Reduce dependency on external server vendors.

---

# Major Components of a Server

* CPU (Intel Xeon Processor)
* Motherboard
* ECC RAM
* NVMe SSD Storage
* Network Interface Card (NIC)
* Power Supply Unit (PSU)
* Cooling Fans
* Server Chassis

---

# Nathu La Server Architecture

```text
                Internet
                    │
                 Firewall
                    │
              Load Balancer
                    │
            Nathu La Server
                    │
                Linux OS
                    │
                 Nginx
                    │
          Docker / Kubernetes
                    │
            Application Server
                    │
                Database
                    │
                 Response
```

---

# Role of a DevOps Engineer

A DevOps Engineer does **not** build the server hardware. Instead, they manage the software and infrastructure running on it.

Typical responsibilities include:

* Linux administration
* Application deployment
* Docker container management
* Kubernetes cluster management
* Nginx configuration
* CI/CD pipeline implementation
* SSL certificate management
* Monitoring and alerting
* Backup and recovery
* Performance optimization
* Production troubleshooting

---

# Linux Skills Required

Essential Linux commands:

```bash
top
htop
free -h
df -h
du -sh
ps -ef
systemctl
journalctl
netstat
ss
```

Key Linux concepts:

* Users and Groups
* File Permissions
* Process Management
* Package Management
* File System
* System Logs
* SSH

---

# Networking Concepts

Understand the following:

* IP Address
* DNS
* HTTP / HTTPS
* SSL/TLS
* Reverse Proxy
* Firewall
* Load Balancer
* TCP/IP
* Ports

---

# Nginx Responsibilities

* Reverse Proxy
* Static Website Hosting
* SSL Configuration
* Virtual Hosts
* Load Balancing
* URL Rewriting
* Request Forwarding

---

# Docker Responsibilities

* Build Docker Images
* Run Containers
* Manage Docker Networks
* Manage Docker Volumes
* Docker Compose

---

# Kubernetes Responsibilities

* Pods
* Deployments
* ReplicaSets
* Services
* Ingress
* ConfigMaps
* Secrets

---

# CI/CD Workflow

```text
Developer
     │
GitHub
     │
CI/CD Pipeline
     │
Build
     │
Docker Image
     │
Container Registry
     │
Kubernetes Cluster
     │
Nathu La Server
     │
Users
```

---

# Monitoring Tools

Common tools used by DevOps Engineers:

* Prometheus
* Grafana
* ELK Stack
* Loki
* CloudWatch

Monitor:

* CPU Usage
* Memory Usage
* Disk Usage
* Network Traffic
* Application Health
* Container Status

---

# Security Best Practices

* SSH Key Authentication
* Least Privilege Access
* Firewall Configuration
* SSL Certificates
* Secrets Management
* Regular Security Updates
* Automated Backups

---

# Important DevOps Interview Points

* Nathu La is Zoho's proprietary server platform.
* It is designed for Zoho's internal cloud infrastructure.
* DevOps Engineers manage the operating system, applications, containers, networking, automation, and monitoring—not the server hardware itself.
* Strong Linux, Networking, Docker, Kubernetes, Nginx, and CI/CD knowledge is essential.
* Infrastructure automation and continuous monitoring are key responsibilities.

---

# Key Takeaway

> "Nathu La demonstrates how modern cloud companies optimize their infrastructure by designing servers tailored to their own workloads. For a DevOps Engineer, the focus is on efficiently deploying, managing, securing, automating, and monitoring the software stack running on these servers to ensure high availability, scalability, and reliability."
