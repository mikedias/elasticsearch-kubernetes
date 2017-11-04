# Elasticsearch over Kubernetes

Simple experiment with Elasticsearch and Kubernetes

## Usage (for now)

``` 
kubectl create -f es-deployment.yaml
```

## TODO List

- [x] Run with the official Elasticsearch image
- [ ] Configure cluster connectivity
- [ ] Setup volume options
- [ ] Init a LoadBalancer to access the cluster externally 
- [ ] Setup a Kubernetes configmap
- [ ] Configure liveness and readness probe
- [ ] Implement separation of concerns (master, data, client)
