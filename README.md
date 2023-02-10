# aks-nodejs-argocd
GitOps modernizes software management and operations by allowing developers to declaratively manage infrastructure and code using a single source of truth, usually a Git repository. Many development teams and organizations have adopted GitOps procedures to improve the creation and delivery of software applications.

For a GitOps initiative to work, an orchestration system like Kubernetes is crucial. The number of incompatible technologies needed to develop software makes Kubernetes a key tool for managing infrastructure. Without Kubernetes, implementing infrastructure-as-code (IaC) procedures is inefficient or even impossible. Fortunately, the wide adoption of Kubernetes has enabled the creation of tools for implementing GitOps.

One of these tools, ArgoCD, is a Kubernetes-native continuous deployment (CD) tool. It can deploy code changes directly to Kubernetes resources by pulling it from Git repositories instead of an external CD solution. Many of these solutions support only push-based deployments. Using ArgoCD gives developers the ability to control application updates and infrastructure setup from an unified platform. It handles the latter stages of the GitOps process, ensuring that new configurations are correctly deployed to a Kubernetes cluster.

In this tutorial, you will learn how to deploy a Node.js application on Azure Kubernetes Service (AKS) using a CI/CD pipeline and ArgoCD.

Prerequisites
To follow along with this tutorial, you will need a few things first.

Accounts for:

Docker Hub
GitHub
Microsoft Azure
CircleCI
These tools installed on your system:

Kubectl
ArgoCD CLI
Azure CLI
Node JS
Docker Engine
