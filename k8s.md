# Kubernetes Tutorial

A Kubernetes Pod is a group of one or more Containers, tied together for the purposes of administration and networking. The Pod in this tutorial has only one Container. A Kubernetes Deployment checks on the health of your Pod and restarts the Pod's Container if it terminates. Deployments are the recommended way to manage the creation and scaling of Pods.

![alt text](https://kubernetes.io/docs/tutorials/kubernetes-basics/public/images/module_01_cluster.svg)

1. Create Deployment

Reference - https://github.com/jmalloc/echo-server

kubectl create deployment hello-minikube --image=kicbase/echo-server:1.0

2. Create Service

kubectl expose deployment hello-minikube --type=LoadBalancer --port=8080

3. List services

kubectl get services 

4. Access service

minikube service hello-minikube