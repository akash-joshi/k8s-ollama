# K8s Llama

This repository contains configuration and documentation for running Ollama with LLaMA model on Kubernetes.

## Documentation

- [Kubernetes Basics](k8s.md) - Basic Kubernetes concepts and commands
- [Ollama Setup](ollama.md) - Instructions for running Ollama locally
- [Ollama on Kubernetes](ollama-k8s.md) - Detailed steps for deploying Ollama on Kubernetes

## Quick Start

1. Create namespace and deploy Ollama:
```bash
kubectl create namespace ollama
kubectl apply -f ollama-deployment.yml
```

2. Deploy the service:
```bash
kubectl apply -f ollama-service.yml
```

3. Access the service:
```bash
minikube service ollama-service -n ollama
```

## Architecture

The deployment consists of:
- Ollama server running in a Kubernetes pod
- LoadBalancer service exposing port 11434
- Automatic LLaMA model loading on container startup

## Requirements

- Kubernetes cluster (e.g., minikube)
- kubectl CLI tool
- Sufficient resources to run LLaMA model
