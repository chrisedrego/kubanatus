# Containers

- Containers as we know aren't separate Operating System which run on top of Base OS, but rather at the very core of it they are nothing but processes which are intelligently isolated from each other.

## Understanding how the processes are isolated from each other
- In the case of containers they are isolated from each other with the help Linux Namespace  & Linux Control Groups (cgroup)
  - Linux Nmaespace, refers to that each of the container has a personal view of the system and its resource i.e. (file system, network, processes inside of the containers, and their hostname)
  - Linux cgroups, refers to limits/caps the amount of resources which are assigned to each processes / cotnainers which involves (cpu, memory, network bandwidth and so on)
  

