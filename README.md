# cka_practice
Practice memo for CKA

## Pods

- https://kubernetes.io/docs/concepts/workloads/pods/

## Replication Controller

- https://kubernetes.io/docs/concepts/workloads/controllers/replicationcontroller/

現在は非推奨になっている

## ReplicationSet

- https://kubernetes.io/docs/concepts/workloads/controllers/replicaset/

## Deployment

- https://kubernetes.io/ja/docs/concepts/workloads/controllers/deployment/

## Namespaces

- https://kubernetes.io/docs/concepts/overview/working-with-objects/namespaces/


### Getting pods in namespaces

```bash
 kubectl get pods --namespace=default
 ```

デフォルトでは `namespace=default`となっている。
全てのnamespaceのpod情報が欲しいときは `-A` オプションを使う

## Service

- https://kubernetes.io/docs/concepts/services-networking/service/


## kubernetes 基本コマンド

- kubectl get
  - https://jamesdefabia.github.io/docs/user-guide/kubectl/kubectl_get/
- kubectl describe
  - https://jamesdefabia.github.io/docs/user-guide/kubectl/kubectl_describe/

## Tips & Tools

- kubeval
- kubeconform
- kube-score
