# Why Kubernetes ?

- Makes packaging and delivery of the Software more faster.
- Scalibility
- Portable accross multiple platform, a container present on Azure Kubernetes Service can run on EKS on Amazon while as the 
same could also run on your local Rasberry pie setup for kubernetes.

### Self-Healing
- Previously, if one instance of the application used to fails, it was the responsibility of the ops to spin up another instance of the application to avoid further downtime, with the help of Kubernetes that has been taken care with the help controllers such as Deployments/RC/RS so that if one instance of the application dies it can intiate another instance of the same application to be provisioned with minimal downtime 

### Abstraction of underlying hardware which is involved.
- As a developer, it was the prime responsibility to develop clean code but as the ops team is involved to deploy the code in the production environment, it was then the responsibility of the ops to take care of the application in case of any hardware failure.
- In the case of Kubernetes, as the application run inside of Pods which contain containers so the underlying hardware which host the resources are pod really dont cause a compatability problem.

### Providing a Consistent Environment
- As already discussed before, all the application workloads runs on pods/containers it helps to provide a consistent environment accross various tages which involes Dev, QA and Production.

### Ready-for-new Changes + Faster Development + Faster Release/Deployment
- 
