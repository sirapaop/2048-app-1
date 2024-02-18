# 2048-app

run on aws

minikube start 

cd 2048-app/2048/2048/k8s

kubectl apply -f .

kubectl get all

kubectl port-forward svc/my-mini-app-service 30001:80 --address 0.0.0.0 &
