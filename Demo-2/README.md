This demo is basically for reading the configuration from custom resources.


```kubectl apply -f crd.yaml```

```kubectl apply -f rule.yaml```

```kubectl apply -f policy.yaml```

```kubectl apply -f binding.yaml```


Statement that will fail

```kubectl create deployment nginx --image=nginx --replicas=2```

Statement that will pass

```kubectl create deployment nginx --image=nginx --replicas=5```

