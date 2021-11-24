# kind

Kubernetes in Docker の略

https://kind.sigs.k8s.io/


## Install

golang がインストールされているならば `go get sigs.k8s.io/kind` する方が早い。
但し、`$(go env GOPATH)/bin`にインストールされる為、適宜PATHを通す必要がある。


## How to use.

```bash
 $ kind create cluster
```