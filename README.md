# Docker & Kubernetes Week 2

## Project Overview

This repository contains a Dockerfile and Kubernetes manifests created as part of the Docker & Kubernetes Week 2 assignment.

## Files

- **Dockerfile** - Builds a custom Nginx image that serves a static web page.
- **pod.yaml** - Creates a single Redis Pod.
- **deployment.yaml** - Creates an Nginx Deployment managed by Kubernetes.
- **screenshots/** - Contains screenshots of executed commands.

## Difference Between Pod and Deployment

### Pod
- A Pod is the smallest deployable unit in Kubernetes.
- It runs one or more containers.
- If a Pod fails, Kubernetes does not automatically recreate it unless managed by a controller.

### Deployment
- A Deployment manages Pods.
- It automatically recreates failed Pods.
- It supports scaling and rolling updates.
- It ensures the desired number of replicas are always running.

## Technologies Used

- Docker
- Kubernetes
- Minikube
- kubectl
- Git
- GitHub