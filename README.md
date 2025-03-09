# Project5: Kubernetes Deployment, Labels vs. Annotations

This repository provides a sample Kubernetes deployment and service for a simple hello-k8s application. The goal is to demonstrate the practical difference between **labels** and **annotations** in Kubernetes.

## Overview

We use a hello-k8s container from Docker Hub (nginxdemos/hello:plain-text) to illustrate how to:
- Use **labels** to identify and group resources.
- Use **annotations** to store additional metadata that does not affect resource selection.

## Files

- **deployment.yaml**: Contains the Kubernetes Deployment configuration with both labels and annotations.
- **service.yaml**: Contains the Service configuration to expose the application.
- **README.md**: This document.

## How to Deploy

### Prerequisites

- A running Kubernetes cluster (e.g., using Minikube or AWS EKS).
- `kubectl` configured to access your cluster.

### Steps

1. **Clone the Repository:**

   ```bash
   git clone <repository-url>
   cd <repository-directory>

