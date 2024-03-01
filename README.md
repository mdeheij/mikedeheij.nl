# My personal website

## Building from HTML

```sh
kubectl create configmap homepage-files --dry-run=client  --from-file ./index.html -o yaml | kubectl-neat > content.yaml
```

## Requirements

- [kubectl](https://kubernetes.io/docs/tasks/tools/)
- [kubectl-neat](https://github.com/itaysk/kubectl-neat)