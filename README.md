# Simple nginx redirect Helm Chart

[![Lint Code Base](https://github.com/pacroy/nginx-redirect-helm/actions/workflows/linter.yml/badge.svg)](https://github.com/pacroy/nginx-redirect-helm/actions/workflows/linter.yml)
[![Check Markdown Links](https://github.com/pacroy/nginx-redirect-helm/actions/workflows/markdown-link-check.yml/badge.svg)](https://github.com/pacroy/nginx-redirect-helm/actions/workflows/markdown-link-check.yml)
[![Test and Publish Chart](https://github.com/pacroy/nginx-redirect-helm/actions/workflows/test-and-publish.yml/badge.svg)](https://github.com/pacroy/nginx-redirect-helm/actions/workflows/test-and-publish.yml)

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
