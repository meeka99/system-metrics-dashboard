# System Metrics Dashboard

This project is a Flask-based web application that monitors and displays real-time system metrics such as CPU usage, RAM usage, disk space, and system uptime. The dashboard provides real-time graphs and alert notifications when certain thresholds are exceeded.

## Features
- Real-time system metrics:
  - CPU usage (%)
  - RAM usage (%)
  - Disk free space (GB)
  - System uptime (hours)
- Alerts:
  - High CPU usage (>80%)
  - High RAM usage (>80%)
  - Low disk space (<20GB)
- Email notifications for alerts.
- Graphs for visualizing trends over time.
- Dockerized for easy deployment.

## Installation Instructions

### Prerequisites
- Python 3.9 or higher
- pip (Python package manager)
- Docker (optional, for containerized deployment)

- ## Screenshots

### Dashboard
![Dashboard](https://github.com/meeka99/meeka99/blob/main/Screenshot%202024-12-15%20002803.png?raw=true)

### CPU Usage Graph
![CPU Usage Graph](https://github.com/meeka99/meeka99/blob/main/Screenshot%202024-12-15%20002812.png?raw=true)

### RAM Usage Graph
![RAM Usage Graph](https://github.com/meeka99/meeka99/blob/main/Screenshot%202024-12-15%20002821.png?raw=true)

### Disk Free Space Graph
![Disk Free Space Graph](https://github.com/meeka99/meeka99/blob/main/Screenshot%202024-12-15%20002828.png?raw=true)


### Local Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/meeka99/system-metrics-dashboard.git
   cd system-metrics-dashboard
