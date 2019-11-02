# Kube-Proxy

- kube-proxy is present on each node in the cluster.
- kube-proxy is responsible for the networking aspect.
- kube-proxy acts as a network proxy and does the load balancing for services.

- kube-proxy is used to implement part of Kubernetes Service.
- Kube-proxy as already discussed is involved in the network communication between in the pods, in respect to within the cluster or 
from outside of the cluster.

- A service is a type of kubernetes resource that causes a proxy to be configured to forward requests to a set of pods, we can 
direct the traffic to a pod directly but pods are ephemiral in this case the ip address of pods keeps on changing, if the pods
ip changes there isnt a way to connect to the pod. Service in this case might act like a proxy to then forward the request over to the pod.
