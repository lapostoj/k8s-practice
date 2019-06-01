# k8s Practice (Kubernetes Practice)

Author: lapostoj

Contact: jerome.lapostolet@gmail.com

## Description

Small project to keep trace of the configuration files created for experiments made with _Kubernetes_.

## Technology

- [Kubernetes](https://kubernetes.io/docs/home/)
- [Minikube](https://kubernetes.io/docs/setup/minikube/)

## How To Use

### Setup For MasOSX

Install _Minikube_

```bash
brew cask install minikube
```

Create a cluster with

```bash
minikube start --vm-driver=hyperkit
```

Using _hyperkit_ seems overall lighter than having to install _VirtualBox_ as well.

Validate that your _kubectl_ config was updated correctly by running

```bash
❯ kubectl config current-context
minikube
```

You can validate further the state of the cluster, and also keep an eye on what you create in it thanks to the _Kubernetes_ dashboard by running

```bash
minikube dashboard
```
