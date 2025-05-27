# workshop
# my-test

Sample application for ArgoCD deployment

## Kubernetes Application

This application was created using the Backstage Kubernetes Application Template. 

## Deployment

The Kubernetes manifests are located in the `k8s` directory and will be deployed by ArgoCD.

## Configuration

- Application Name: my-test
- Team: naruto
- Container Image: nginx:latest
- Replicas: 1
- Custom Label: my-awesome-app