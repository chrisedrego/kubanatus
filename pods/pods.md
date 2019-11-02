# Pods

- Pods are the smallest unit for kubernetes.
- A Pods are collection of one more containers which are group together which share the common resources. 
- Pods common resources which involves the below:
1. Network Space
2. Volumes
3. Cgroups
4. Linux Namespaces

-  As a pod is assigned an IP Address the containers present in the Pods have the same IP Address.
- Intercommunication between containers present in the same pod can be done using localhost.
- Pods is the smallest deployable unit in the Kubernetes.
- Pods can be called as containers that share resources such as file systems, common namespace and IP Address.

- Pods can also be termed as single container or couple of containers which are combined together



- Two Models of running a Pod:

1. One Container, One pod:
  - In this case, One Pod contains only one container running within it. This is the most common model that is present in
  kubernetes
  
2. Multiple Containers, One Pod:
  - In this case, as the name suggest there are multiple containers which run in the same pod and share the overall resources which are present.
  - Multiple Containers that run are tightly coupled
  
 
