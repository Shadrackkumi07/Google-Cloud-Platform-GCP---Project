<div align="center">

# GCP Final Lab Project

![Project Showcase Image](https://drive.google.com/uc?export=view&id=1udKGwR8dzmsFvFLefu-qu7JqcryvGU8d)

</div>


Welcome to the repository for my Google Cloud Platform (GCP) Final Lab Project. This project showcases the culmination of my hands-on experience working with GCP services to build and deploy cloud-based solutions. Below, you will find detailed documentation about the project, the steps I followed, and key takeaways.

---


## Introduction

This project involved completing a series of lab assignments on Google Cloud Platform to design and implement cloud-based solutions. The objective was to gain proficiency in GCP services and deploy production-grade applications using industry best practices.

## Project Overview

The lab covered:

1. **GKE Cluster Deployment**: Creating a Google Kubernetes Engine (GKE) cluster for container orchestration.
2. **Persistent Storage**: Setting up Persistent Disks for stateful applications.
3. **Monitored Web Server**: Deploying a monitored web server with Prometheus and Grafana integration.
4. **NTP Server Cluster**: Implementing a highly available and self-updating NTP server cluster.
5. **Security Configuration**: Applying firewalls, IAM roles, and network policies.

## Setup and Deployment

### Prerequisites

- A Google Cloud Platform account
- gcloud CLI installed and configured
- kubectl CLI for managing GKE clusters
- A GitHub repository for version control

### Deployment Steps

1. **Set Up GCP Resources**:
   - Create a GKE cluster in the `us-central` region.
   - Configure Persistent Disks for data storage.
2. **Deploy Applications**:
   - Use Kubernetes manifests to deploy web servers and NTP clusters.
   - Configure Load Balancers for high availability.
3. **Monitoring and Security**:
   - Integrate Prometheus and Grafana for application monitoring.
   - Implement IAM roles and firewall rules for enhanced security.

## Features

- Scalable Kubernetes-based architecture.
- Persistent storage for stateful applications.
- High availability through load balancing and self-healing mechanisms.
- Real-time monitoring with dashboards.
- Automated updates for deployed services.

## Testing and Validation

- **Unit Testing**: Verified Kubernetes manifests using `kubectl apply --dry-run`.
- **Integration Testing**: Validated application deployment and connectivity.
- **Monitoring Tests**: Ensured Prometheus and Grafana were capturing metrics.
- **High Availability Tests**: Simulated node failures and verified failover mechanisms.

## Final Results

- Successfully deployed a GKE cluster with monitored web servers and NTP server clusters.
- Achieved high availability and robust security configurations.
- Demonstrated proficiency in GCP services and cloud architecture.

## Lessons Learned

1. Importance of automation and monitoring in cloud-based deployments.
2. Best practices for securing cloud resources and applications.
3. Strategies for optimizing cost and performance in GCP.


## References

- [Google Cloud Platform Documentation](https://cloud.google.com/docs)
- [Kubernetes Documentation](https://kubernetes.io/docs)
- [Prometheus and Grafana Documentation](https://prometheus.io/docs/)

---

Thank you for visiting this repository. If you have any questions or feedback, feel free to open an issue or contact me directly!

