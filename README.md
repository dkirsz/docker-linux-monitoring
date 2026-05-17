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
![Grafana Dashboard Overview]([[LINK_DO_TWOJEGO_PIERWSZEGO_SCREENA]](https://i.imgur.com/Lu55SMH.png))

### Metrics Under Load (Stress Test)
![Metrics Spike](https://i.imgur.com/7den4BB.png)

---

## 🛠️ Prerequisites
* Linux OS (Ubuntu/Debian recommended)
* Docker & Docker Compose V2 installed

## 🚦 Quick Start

1. Clone this repository:
   ```bash
   git clone [https://github.com/](https://github.com/)dkirsz/docker-linux-monitoring.git
   cd docker-linux-monitoring
