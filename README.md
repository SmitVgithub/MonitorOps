# 📡 MonitorOps

> **MonitorOps** is a complete monitoring stack for observability and alerting in modern infrastructure. This repository includes configuration files and setup instructions for **Gatus**, **Grafana**, **Uptimekuma**, and **Alertmanager**—all containerized and ready for production.

---

## 📁 Repository Structure

```bash
PulseWatch/
│
├── gatus/               # Gatus config files 
├── grafana/             # Grafana dashboards, provisioning, plugins
├── uptimekuma/          # Uptime config for log aggregation
├── alertmanager/        # Alertmanager routes and receivers
└── README.md            # Project documentation
```

## 🚦 Stack Overview
> Component | Description
> Gatus | Automated health checks and SLA-style monitoring
> Grafana | Dashboards and metrics visualization
> Uptime Kuma | Self-hosted status page and uptime tracker
> Alertmanager | Alert routing and Slack notification integration

## 🧰 Prerequisites
* Docker
* Docker Compose
* Slack Webhook (for alerts)

