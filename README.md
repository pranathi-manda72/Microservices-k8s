**Kubernetes Microservices Deployment**
This project demonstrates the deployment of a microservices-based application on a Kubernetes cluster using YAML configuration files. The application consists of multiple independent services, each deployed and managed using Kubernetes Deployments and Services.
The deployment was implemented and tested on Ubuntu Linux using Minikube as the local Kubernetes cluster.

**Technologies Used**
Ubuntu (Linux / WSL)
Docker
Kubernetes
Minikube
kubectl

**How to Deploy**
minikube start
kubectl apply -f k8s/
kubectl get pods
kubectl get services
minikube service frontend-service

**Deliverables**
Kubernetes YAML configuration files
Successfully deployed microservices on Kubernetes
Documentation for deployment and execution

**Notes**
All Kubernetes configuration files are located in the k8s/ directory
Each microservice is deployed independently for scalability and reliability

**OUTPUT**
![image alt](https://github.com/pranathi-manda72/Microservices-k8s/blob/15f6108ede159c3efd519d55a417e32f3412f454/Screenshot%202026-01-31%20222110.png)
