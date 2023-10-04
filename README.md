# k8s-dashboard
when ready, run command:

```shell
# get port
kubectl get svc -n kubernetes-dashboard -o wide
# create token
kubectl -n kubernetes-dashboard create token admin-user --duration 604800s
```
