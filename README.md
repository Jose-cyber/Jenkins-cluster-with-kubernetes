# Deploying jenkins cluster with Kubernetes

this project use kubernetes to provide a local cluster with 2 replicas of container jenkins.

### Require comands:

*  **kubectl apply -f .**
*  **kubectl -n jenkins-app port-forward service/jenkins-service 8080:8080**

