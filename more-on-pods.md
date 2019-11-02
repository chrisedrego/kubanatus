# More on Pods.

## How do pods manage containers?

Pods support multiple containers and as they share common resources which involves IP Address, file-system, Namespaces.

If multiple containers are to be provisioned on the pods then in that case, all of the containers are coallocated at the same time.

Containers present in the same pod run on the same pod as well as the same node on which the pod is running.

Containers present in the same pod have the same IP Address as well as localhost.



## Sharing of Storage accross containers within a Pod

In this case, within a pod we can have multiple containers that share the same filesystem or volume.
Lets say if one container is attached to the volume and container writes the data to the volume, for some reason unknown if the
container fails and data is still attached to the volume and is present, so that once the new container is provisioned it can
 still access the data on the older container as well.
 
 
## Sharing Network accross containers withing a Pod.

In this case, the IP address present between all the containers present within a pod is the same, an hence both the containers 
communicate with each other using localhost.


