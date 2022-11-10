# Deploy Neo4j 5 as a single statefulset and 3 replicas

This is just a quick demo to prove it is possible.

Still need to figure out how to handle bringing a single pod into offline maintenance mode

*N.B this doesn't work on GKE yet as the Pod hostnames don't include the IP address*
To run the demo:

```
kubectl apply -k k8s
```
