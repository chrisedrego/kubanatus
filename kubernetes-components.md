## Kubernetes Components

Kubernetes is made up of multiple components, which together build up together to form Kubernetes.

Kubernetes at a Higher-Level contains two type of components:
1. Master Components
2. Node Components

## Master Components
- Master components invole in the decision making more precisely the scheduling of the workloads accross the cluster.
- Master Componets (Nodes) dont run user specific containers.
- Master Node contains various components which are present:
1. kube-apiserver
2. etcd
3. kube-scheduler



### kube-apiserver
- Kube-apiserver is responsible for most of the heavy lifting that is done by kubernetes
- Kube-apiserver can be scaled horizontally in this case, we can have multiple instance of the kube-api-server running which
can be loadbalanced.
