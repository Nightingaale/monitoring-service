# Monitoring-service

</p>
  <img src="https://skillicons.dev/icons?i=prometheus,grafana,git"/>
</p>

# Features

- Metrics Collection: Gathers application metrics (CPU, memory, latency, request rates) via Prometheus exporters
- Dynamic Dashboards: Provides customizable Grafana dashboards to visualize system health, API performance, and microservices metrics
- Log Aggregation: Supports correlation with Loki for centralized log analysis

# Prerequisites
- Docker: For building containers

## Getting Started

Set up monitoring service locally using Docker Compose for the dev environment.

### Prerequisites

Ensure you have the following installed:
- Docker
  
  ```sh
  docker --version
  ```

### Installation
1. Start your services with Docker Compose:
   ```sh
   docker compose up -d
   ```
2. Verify services are running:
   ```sh
   docker ps
   ```
