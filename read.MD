# selectors

Taint the node
```

kubectl taint nodes ip-192-168-18-216.ec2.internal hardware=gpu:NoSchedule
```
Untaint 
```
kubectl taint nodes ip-192-168-18-216.ec2.internal hardware=gpu:NoSchedule-
```

Label node
```

kubectl label nodes ip-192-168-18-216.ec2.internal hardware=gpu 
```

Ref: https://kubernetes.io/docs/tasks/configure-pod-container/assign-pods-nodes/ 