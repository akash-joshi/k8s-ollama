Title: Deploying Local-First LLM Inference Pipelines on Amazon EKS

Brief: AI models are ubiquitous. We've already been pestering ChatGPT for answers to questions for the last couple years. However, did you know that the same technology that powers ChatGPT can be deployed on your AWS infrastructure? In this talk, we'll dive deep into running open-source Language Models locally and deploying them to Amazon EKS. We'll explore serving HTTP APIs on top of these models using AWS services, so you can build enterprise-grade applications while maintaining full control over your infrastructure. Finally, we'll learn how to implement this approach and scale it effectively!

This talk empowers you to deploy any open-source LLM model to AWS in a distributed, scalable manner, enabling you to be the AI Champion of your organization!

Details:
1. Introduction to Open-Source LLMs and Ollama
- We'll explain how open-source LLMs compare to managed services like AWS Bedrock and Amazon SageMaker
- We'll demonstrate using Ollama to download and run a language model locally (e.g., llama3.2 or deepseek-r1)
- We'll discuss why local-first deployment might be the right choice for your use case

2. Leveraging Amazon EKS for LLM Inference
- We'll explore the architecture of Amazon EKS and how it simplifies Kubernetes management
- We'll set up a local development environment with AWS CLI and eksctl
- We'll deploy a simple "Hello World" application to Amazon EKS
- We'll understand the different layers in deploying applications to EKS (containers, pods, deployments, and services)
- We'll implement auto-scaling for handling variable inference loads

3. Deploying LLM Inference APIs to Amazon EKS
- We'll demonstrate deploying an LLM inference API to Amazon EKS step-by-step
- We'll configure Horizontal Pod Autoscaling (HPA) to automatically scale our LLM pods based on CPU/memory utilization

Join this session to learn how to deploy and scale open-source LLMs on AWS while maintaining full control over your infrastructure!
