# movies-app-helm

## Introduction

This repository contains Helm charts for deploying the movies-app on Kubernetes using ArgoCD for continuous deployment.

## Prerequisites

Before using Helm and ArgoCD, ensure you have:

- [Helm](https://helm.sh/) installed
- [ArgoCD](https://argoproj.github.io/argo-cd/) installed and configured

## Deployment

1. Install the movies-app using Helm:

$ helm install movies-app ./movies-app-chart

2. Access the ArgoCD dashboard to monitor deployments.
