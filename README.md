# Simple NGinX Redirector Helm Chart

## Values File

```yaml
appHost:  your.to
locationMaps:
  - path: test1
    url:  https://www.target1.com
  - path: test2
    url:  https://www.target2.com
```

## Local Installation

```sh
helm install <release_name> . --namespace=<namespace> --values <values_file>
```

## Installation from Repository

```sh
helm repo add pacroy https://raw.githubusercontent.com/pacroy/helm-repo/master
```

```sh
helm repo update
```

```sh
helm install <release_name> pacroy/nginx-redirector --namespace=<namespace> --values <values_file>
```
