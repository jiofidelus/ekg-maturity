# Background & Intro

Knowledge Graph in General and Enterprise Knowledge Graph in particular are built to reply to a set of competencies questions. Thus, once they are built, software modules are built up to them for a variety of purpose such as search, question answering, recommendation, etc. There are many ways to organize EKG and software modules around him: monolitic architecture, service oriented architecture and microservice architecture. These architectures are used to describe how different software components developed to describe competencies questions collaborate with the EKG. Thus, different types of architectures should be considered: at the physical level, we have the physical architecture, consisting of the devices which is used to query the KG. At the logical level, we have different technologies that are used to deploy the KG, that are used to developed the software components and on which the different software component runs. For instance, if the KG can be queried from a mobile phone, different operating systems for mobile phones should be considered.

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
