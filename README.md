 Kubernetes Project

Description
This project demonstrates deployment of an application using Kubernetes (Minikube).

 Tools Used
- Docker Desktop
- Minikube
- kubectl

Steps Performed
- Installed Docker and Minikube
- Created deployment using nginx
- Exposed service using NodePort
- Accessed application in browser

Commands Used
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
kubectl get pods
kubectl get services
kubectl get deployments
kubectl scale deployment my-app --replicas=4

 Output
Screenshots are attached in the repository.
