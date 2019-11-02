# Battle between VM's VS Containers

- Containers are light weight, as compared to the VM's as we already know that Containers dont have the additional kernel for each container but rather they share the kernel from the same host machine on which they are running.

- In this case, we might have often get confused that on docker hub for that matter we see docker images with image name such as ubuntu, alpine, debian, centos, in this case these images are light weight images which contain (binaries/libraries) which contain very light foot print and at the end use the base OS kernel. 

- Container thereby consume lesser hardware resources as compared to the VM.

- As a take a way, containers make running more software application/components as compared to that virtual machines.

- When VM runs in that case a application running inside of the VM is more isolated as compared to the same application running inside of the container, In the case of VM, it has its own host so that encures another booting time to boot up the vm but the same isnt the case when container is present.

- In the case of Type 2 VM , When we have like lets say 4 VMS in that case we have four applications running inside of each VM, in this case each request for a resource for by the application first reaches the Guest VM (Opearing System) after which the request is handed over to the Base OS and finally the request is hand over to the Underlying Hardware. Example of Type 2 VM is VMWARE Player, Virtualbox.

- In the case of Type 1 VM, when the application running inside of the VM request for the resource to the Guest OS the request is forwarded to the Hypervisor which runs at lower level and has access to the hardware thereby, the overall performance is better in this case as compared to Type 1 VM, Example of Type1 VM is Hyper-V
