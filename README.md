# DevOps Project: Version Control & Deployment

## Tools Used
- Git & GitHub
- Docker
- Kubernetes
- GitHub Actions (CI/CD)

## Workflow
1. Code pushed to GitHub
2. CI pipeline runs tests (pytest)
3. Docker image built
4. Image pushed to Docker Hub
5. Deployed to Kubernetes

## Run Project
kubectl port-forward deployment/version-app 5000:5000
