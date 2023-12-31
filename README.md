# K8s Monitoring Stack with Helm

This project sets up a comprehensive monitoring stack in a Kubernetes cluster using Helm charts. It includes the installation and configuration of Redis, Prometheus, and Grafana for efficient monitoring, metrics collection, and visualization.

The project showcases the power of Helm for orchestrating Kubernetes deployments and managing complex applications. With separate Helm charts for each component, you can easily customize and deploy the monitoring stack tailored to your specific requirements. Redis serves as the data store, Prometheus collects and stores metrics, and Grafana provides a user-friendly interface for visualization and alerting.

## Table of Contents
- [Installation](#installation)
- [Redis Configuration](#redis-configuration)
- [Prometheus Setup](#prometheus-setup)
- [Grafana Installation](#grafana-installation)

## Installation

Everything in this project is installed in a Kubernetes cluster using Helm charts. There are three separate directories in the project, each containing a Helm chart for a specific component:

1. [Redis Chart](./redis/): Contains the Helm chart for Redis.
2. [Prometheus Chart](./prometheus/): Contains the Helm chart for Prometheus.
3. [Grafana Chart](./grafana/): Contains the Helm chart for Grafana.

To install the project in your Kubernetes cluster, follow the instructions provided in each chart's respective directory.

## Redis Configuration

### Redis Installation
- Redis was installed within the Kubernetes cluster using the Redis Helm chart.

### Redis Setup as Master-Replica
- Redis was configured as a master-replica setup within the Kubernetes cluster.

### Redis Persistent Storage
- Redis was configured with persistent storage within the Kubernetes cluster.

### Redis Metrics
- Redis metrics were enabled for monitoring within the Kubernetes cluster.

## Prometheus Setup

### Prometheus Installation
- Prometheus was installed within the Kubernetes cluster using the Prometheus Helm chart.

### Prometheus Configuration
- The Prometheus Helm chart was used for Prometheus installation within the Kubernetes cluster.

### Exporters Enabled
- Kubestate metrics exporter and Node exporter were enabled for Prometheus within the Kubernetes cluster.

## Grafana Installation

### Grafana Installation
- Grafana was installed within the Kubernetes cluster using the Grafana Helm chart.

### Visualization
- Node exporter and Redis metrics were visualized in Grafana within the Kubernetes cluster.

