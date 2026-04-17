# KubeGuard

KubeGuard is a Kubernetes security enforcement system using Kyverno to block insecure container deployments using policy-as-code.

## Features
- Blocks root user containers
- Admission control using Kyverno
- Minikube-based local setup

## Flow
kubectl apply → API Server → Kyverno → Allow / Deny Pod