Title: Deploying LLM-based inference pipelines to Kubernetes

Brief: AI models are ubiquitous. We've already been pestering ChatGPT for answers to questions for the last couple years. However, did you know that the same technology which powers ChatGPT can also run on your machine, that too completely free of cost? In this talk, we'll dive deep into running the Language Models on your machine. We'll also explore serving an HTTP API on top of these models, so you can build a software application on top of them. Finally, we'll learn how we can use the power of Kubernetes and devops, to develop them on your machine, and automate deployments to various cloud platforms!

This talk empowers you to deploy any open-source LLM model to cloud platforms in a distributed manner, enabling you to be the AI Champion of your organisation!

Details:
1. Introduction to Ollama
- We do an explanation of Ollama, and understand how it works.
- We then do a demo of how to use Ollama to download and run a language model (e.g. llama3.2 or deepseek-r1).

2. Introduction to Kubernetes
- We do a deep dive into the architecture of Kubernetes, and how it works.
- We set up minikube on our machine, and deploy a simple "Hello World" application to it.
- We then understand the different layers that go into deploying an application to Kubernetes (containers, pods, deployments and services).

3. Deploying Ollama to Kubernetes
We then do a demo of how to deploy a more complex application to Kubernetes, which serves an HTTP API on top of an LLM. While going through this, we deploy the application step by step, and understand the different components that go into it.

