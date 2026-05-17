# Linux System Monitoring Stack (Prometheus & Grafana)

A cloud-native monitoring solution built with Docker Compose to scrape system metrics from a Linux host using Prometheus Node Exporter and visualize them through a dynamic Grafana dashboard.

## 🚀 Features
* **Automated Deployment:** The entire stack spins up with a single Docker Compose command.
* **Real-time Metrics:** Captures CPU, Memory, Disk I/O, and Network stats every 15 seconds.
* **Dynamic Visualization:** Includes a production-ready Grafana dashboard with historical data tracking.

## 🏗️ Architecture
The project architecture consists of three main components:
1. **Node Exporter:** Runs on the host machine to collect native hardware and OS metrics.
2. **Prometheus:** A time-series database that scrapes metrics from Node Exporter at regular intervals.
3. **Grafana:** Connects to Prometheus as a data source to visualize metrics on an interactive dashboard.

---

## 📸 Dashboard Preview

### System Metrics Overview
<img width="1366" height="685" alt="grafana" src="https://github.com/user-attachments/assets/f02922e2-a077-46e9-a5fa-85159013b091" />


### Metrics Under Load (Stress Test)
<img width="1366" height="684" alt="grafana2" src="https://github.com/user-attachments/assets/1cf4226d-79bc-46bd-860b-a5951bac6dfe" />

---

## 🛠️ Prerequisites
* Linux OS (Ubuntu/Debian recommended)
* Docker & Docker Compose V2 installed

## 🚦 Quick Start

1. Clone this repository:
   ```bash
   git clone https://github.com/dkirsz/docker-linux-monitoring.git
   cd docker-linux-monitoring
