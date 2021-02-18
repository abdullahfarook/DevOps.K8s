# Introduction

Kubernetes Commands and Utils

# Getting Started

// warning: gives all rights
kubectl create clusterrolebinding serviceaccounts-cluster-admin --clusterrole=cluster-admin --group=system:serviceaccounts

rollout restart deploy qf-api-prod-deployment

# cert-bot helm charts

choco install kubernetes-helm
kubectl create ns cert-manager
helm repo add jetstack https://charts.jetstack.io
helm repo update
