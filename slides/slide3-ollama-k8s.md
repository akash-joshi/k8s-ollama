## Create namespace

kubectl create namespace ollama

## Apply the deployment

kubectl apply -f ollama.yml

## Get Pods

<!-- Getting pods for ollama namespace -->
kubectl get pods -n ollama

<!-- All namespaces -->
kubectl get pods -A

## Display Logs

- f flag is for follow
- deployment/ollama is the name of the deployment. This can be replaced with pod name

kubectl logs -f -n ollama deployment/ollama

## Apply the service

kubectl apply -f ollama-service.yml

## Check service status

kubectl get services -n ollama

## Access service via minikube

minikube service ollama-service -n ollama