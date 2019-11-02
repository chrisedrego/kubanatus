# Services

- Services are the backbone of the Kubernetes service discovery mechanism.

## Service as Internal load balancer

- In the attempt for highly availiability of application we often scale the number of replicas
, which thereby creates multiple pods, As pods we know are ephimeral in nature, which makes them less reliable to have stable endpoint for the end user to serve the request, in this case service is for the rescue as it goes ahead and acts a load balancer to which the request is been sent and its the job of the service to then forward the request to the respective pods.

- Service are directed to send the traffic to the specific set of pods with the help of selector attribute which maps to these specific pods.

- Labels which get assigned to a pods are important as it maps to the selector attribute in service, which is usefull for service discovery.

