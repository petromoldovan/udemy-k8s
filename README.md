## Course Ref

https://www.udemy.com/course/docker-and-kubernetes-the-complete-guide/

### K8S commands

Apply changes from folder

```
kubectl apply -f k8s
```

create a secret:

```
kubectl create secret generic pgpassword --from-literal PGPASSWORD=12345asdf
```

check all secrets:

```
kubectl get secrets
```
