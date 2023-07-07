# Argo Bootstrap

This repository contains a set of files and configurations to help you bootstrap your Kubernetes cluster with Argo(CD, Rollouts and so on) using [FluxCD](https://github.com/yashwanth-l/fluxcd2-bootstrap).

## Getting Started

To get started with Argo Bootstrap, follow these steps:

- Clone this repository to your local machine:

```sh
git clone https://github.com/yashwanth-l/argo-bootstrap.git
```

## Directory Structure

The top level directories are as below(and will be extended, with testing and adding features)

```sh
.
└── clusters
    └── argo-kind-k8s
        ├── argocd
        └── argorollouts
```

- This can be _customized_ to your needs to install any components, as I do in my Cluster as described below

  - **clusters/argo-kind-k8s/argocd:** Contains installation of `argocd` and its CRD based manifests

  - **clusters/argo-kind-k8s/argorollouts:** Contains installation of `argo-rollouts` and its CRD based manifests

## Support

If you have any questions or need assistance, please open an [issue](https://github.com/yashwanth-l/argo-bootstrap/issues).
