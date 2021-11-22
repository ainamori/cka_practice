# cka_practice

## Pods

- https://kubernetes.io/docs/concepts/workloads/pods/


### pod.yml

- Requirement keys
  - apiVersion
  - kind
  - metadata
    - name
    - labels
  - spec
    - containers
      - name
      - image

```bash
 kubectl apply -f pod.yml
```

