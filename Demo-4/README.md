This demo is basically for reading the configuration from configmap.


```kubectl apply -f config.yaml```

```kubectl apply -f admissionpolicy.yaml```

```kubectl apply -f admissionpolicybinding.yaml```


Statement that will fail

```kubectl create deployment nginx --image=wrong-reg/nginx --replicas=2```

Statement that will pass

```kubectl create deployment nginx --image=docker.io/nginx --replicas=2```

