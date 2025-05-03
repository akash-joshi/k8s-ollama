A llama and a whale walk into a bar.

Alternate Title: Deploying LLM-based inference pipelines to Kubernetes

Brief: AI models are ubiquitous. We've already been pestering ChatGPT for answers to questions for the last couple years. However, did you know that the same technology which powers ChatGPT can also run on your developer machines, that too completely free of cost? In this talk, we'll dive deep into running the Language Models on your servers, to serve an HTTP API on top of them. Finally, we'll learn how we can use the power of Kubernetes and devops to automate deployments to various cloud platforms.

This talk empowers you to deploy any open-source LLM model to cloud platforms in a distributed manner, enabling you to be the AI Champion of your organisation!

What will attendees learn?
- How to run Ollama locally and deploy LLaMA models
- Setting up a basic Kubernetes deployment for AI workloads
- Creating and managing Kubernetes services for LLM inference
- Implementing automatic model loading in containerized environments

What problems does it solve?
- Running LLM models in a containerized environment
- Exposing LLM services through Kubernetes
- Automating model loading and initialization
- Setting up a production-ready LLM service

Detailed Agenda:

1. Introduction to Ollama and LLaMA
* Overview of Ollama and its capabilities
* Understanding LLaMA model requirements
* Setting up Ollama locally
* Demo: Running LLaMA model locally

2. Kubernetes Basics for LLM Deployment
* Core Kubernetes concepts (Deployments, Services, Namespaces)
* Container orchestration fundamentals
* Resource requirements for LLM workloads
* Demo: Setting up a basic Kubernetes cluster

3. Deploying Ollama to Kubernetes
* Creating Kubernetes manifests for Ollama
* Setting up namespace and deployment
* Configuring container lifecycle hooks
* Demo: Deploying Ollama with automatic model loading

4. Exposing the LLM Service
* Creating and configuring Kubernetes services
* Setting up LoadBalancer for external access
* Managing service ports and networking
* Demo: Accessing the LLM service through LoadBalancer