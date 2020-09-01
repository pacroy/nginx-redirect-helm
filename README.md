# Simple nginx redirect Helm Chart

For your own customer short URLs. e.g. http://your.to/somewhere

## Local Installation

```sh
helm install <release_name> . --namespace=<namespace> --values <values_file>
```

## Installation from Repository

```sh
helm repo add pacroy https://pacroy.github.io/helm-repo/
helm repo update
helm install <release_name> pacroy/nginx-redirect --namespace=<namespace> --values <values_file>
```
