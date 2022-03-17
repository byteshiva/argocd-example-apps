refer:
https://www.digitalocean.com/community/tutorials/how-to-deploy-to-kubernetes-using-argo-cd-and-gitops


```
kubectl get services                                                                                     
NAME                            TYPE           CLUSTER-IP      EXTERNAL-IP   PORT(S)          AGE
guestbook-helm-guestbook        NodePort       10.98.101.21    <none>        80:30964/TCP     8d
➜  generics kubec
```

```
kubectl port-forward svc/guestbook-helm-guestbook  9090:80

```
