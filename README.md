# Kubernetes

## What is Kubernetes?

## Kuerbnetes Architeture?

## Pod Lifecycle

## Kubernetes Cheat Sheet

## ConfigMap and Secrets


## Helm for ingress controller

```shell
wget https://get.helm.sh/helm-v4.1.1-linux-amd64.tar.gz
tar -xzvf helm-v4.1.1-linux-amd64.tar.gz
cd linux-amd64/
./helm pull oci://ghcr.io/nginx/charts/nginx-ingress --untar --version 2.4.3
cd nginx-ingress/
../helm install nginx-ingress .
```
