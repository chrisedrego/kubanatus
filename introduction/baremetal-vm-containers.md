# Going back in time
## Baremetal v/s Virtual Machine v/s Containers

## BareMetal
In the early days, the deployment used to occur on the Baremetal Physical machine, if let say on this one physical machine 
we have multiple applications running in that case, if there are multiple applications which run on one physical machine, it 
consumes the resources.
If one application starts over consuming the resources which are present, the performance of other application which are present
gets hampered. In this case scalling is not possible, and having multiple copies of the physical machine is runs different 
application isnt a better approach.

## Virtual Machine
In this case, we have base OS on top of which we have the Virtual Machine, in which each Virtual Machine contains its own Operating Sytem along with 
the application/binaries which are present.
In this case, Virtual Machine adds the extra layer of isolation, so that the application running in one VM, cannot freely access the 
other Virtual Machine.
the only pitfall behind this approach is that, the additional OS is needed for each Virtual Machine and that adds the overhead 
and that consumes more resources.

## Containers
In this case, Containers share the Resources involving the Base Operating System which is present.
Conatainer are similiar and have their own filesystem, CPU, memory, process space.

Container help to make it more of Microservice based approach, by breaking down the whole application (the whole Big Monolithic 
Application) into smaller groups of Microservices.








