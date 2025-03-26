1. Create Deployment

Reference - https://github.com/jmalloc/echo-server

kubectl create deployment hello-minikube --image=kicbase/echo-server:1.0

2. Create Service

kubectl expose deployment hello-minikube --type=LoadBalancer --port=8080

3. List services

kubectl get services 

4. Access service

minikube service hello-minikube