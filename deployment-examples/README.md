# k8s-tutorial
Commands:

```
kubectl rollout history deployment deployment-pod-web-nginx-example
```

```
kubectl apply -f deployment-pod-web-nginx-example.yaml --record
```

```
kubectl annotate deployment deployment-pod-web-nginx-example.yaml kubernetes.io/change-cause="mensagem desejada"
```

```
kubectl rollout undo deployment deployment-pod-web-nginx-example --to-revision=x
```