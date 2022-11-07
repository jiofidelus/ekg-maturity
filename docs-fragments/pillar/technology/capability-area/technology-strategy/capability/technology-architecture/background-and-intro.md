# Background & Intro

## Monolitic architectures
Description of architectures in which all the modules are tights together to form the application

## Service Oriented architecture
Once the monolitic is done, there is a possibility to create endpoints from this monolitic. For instance, to create a SPARQL endpoint that can be used to query the Knowledge Grapgh.

## Microservice architecture
The monolitic and the SOA architectures can have some limits when the application have to scale up. For instance, the number of users who connects to the graph can grow and lead to the server overflow. In this case, one can think to scale up the application by load balancing with new servers. In some cases, only some services of the application is too much demanded. In this case, we are faced with waste of resources. The microservice can solve this problem by allowing to divide the application in such a way that during the application monitoring, only the part of the application which is the most requested is scale up.

On the other hand, the services that the graph should provide can augment with time. The adoption of microservices architectires allow to developers having differents skills can involve in the development of these services. Thus, the services are developed, other services are called and the end point of these services are exposed to make them accessible to other services.

But the question can be to know how to organize the graph to allow to any service to dispose to his own data?


!!! warn

    Work in progress
