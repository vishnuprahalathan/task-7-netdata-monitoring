# task-7-netdata-monitoring

## ✅ Objective
Set up Netdata using Docker to visualize real-time system and application performance metrics.

## 🔧 Tools Used
- Docker
- Netdata (https://www.netdata.cloud/)

## 📦 Steps Followed

1. Installed Docker
2. Pulled Netdata Docker image
3. Ran Netdata container using:
   ```bash
   docker run -d --name=netdata -p 19999:19999 netdata/netdata
Accessed dashboard at: http://localhost:19999

Explored CPU, memory, disk I/O, Docker metrics

Captured dashboard screenshot
