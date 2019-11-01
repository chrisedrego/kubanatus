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

