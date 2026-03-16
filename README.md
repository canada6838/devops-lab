# devops-lab
# devops-lab
# devops-lab
# devops-lab
# devops-lab
# DevOps Lab

This project demonstrates a simple DevOps pipeline.

## Technologies Used

- Python Flask
- Docker
- Kubernetes (Minikube)
- Git & GitHub
- GitHub Actions CI/CD

## Architecture

Developer → GitHub → GitHub Actions → Docker → Kubernetes

## Steps

1. Build Docker container
2. Deploy container to Kubernetes
3. Expose service using NodePort
4. Access application via Minikube

## Run locally

Build Docker image

docker build -t devops-demo ./docker

Deploy to Kubernetes

kubectl apply -f kubernetes/deployment.yaml
kubectl apply -f kubernetes/service.yaml
