# selectors

Taint the node
```

kubectl taint nodes ip-192-168-18-216.ec2.internal hardware=gpu:NoSchedule
```

Label node

```
kubectl label nodes ip-192-168-18-216.ec2.internal hardware=gpu 
```