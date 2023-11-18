## Assignment in Advanced Systems Integration & Architecture 

1. Define Service Oriented Architecture(SOA). - Service Oriented Architecture is part of software development that can use software components which are called services, to create business applications. 

2. List and discuss the characteristics of SOA. 
 
- The following are the characteristics of SOA 

> Standardized Service Contracts - this characteristic adheres to a specific service description. This can be used to express a service's purpose, capabilities, and the ability to use formal and standardized service contracts.

> Loose Coupling - this characteristic minimizes the dependencies on each other and can make specific types of relationships in or out of their service boundaries with an emphasis on "loosening" dependencies. This spans between the service contract, service implementation, and service consumers.

> Abstraction - this characteristic enables services to hide the logic that they encapsulate from the outside world, avoids the generation of unnecessary information of the service, can hide as much of the underlying details of a service if possible, can enable and preserve loosely-coupled relationships, and it plays an important role for positioning and the design of the overall service composition.

> Service Reusability - this characteristic can divide its logic to services with the purpose of maximizing its reusability.

> Autonomy - this characteristic enables existing services to have control over the logic that they encapsulate, it represents the service's ability to carry out its logic independently from outside influences, requires services to be more isolated, and gives benefits such as increased reliability and the service's predictability over its behavior.

> Statelessness - this characteristic incorporates its state management deferral extensions within its service design goal, can increase service scalability, and it can support the design of agnostic logic and improve the service's reusability.

> Discoverability - this characteristic makes it easy for services to be discovered, can implement contracts to contain appropriate metadata for discovery which also can provide purpose and capabilities for humans. It can also store the metadata in a service registry or in profile documents.

> Composability - this characteristic can break a service's big problems into little problems, ensures the execution of the service is efficient in an individual process and should be highly tuned, as well as allow different data types to be flexible in their contracts so that data exchange can be made for similar functions.

> Interoperability - this characteristic uses standards that allow users from different subscribers to use their services, it is often emphasized that it is the key to communication between the provider and consumer, and it ensures the service that it does not get obsolete to the statuses of interfaces and have an identity of their own so that it can be managed individually and/or in sets.

3. Define Microservices. - Microservices is described as a true cloud-native architectural approach, which can help teams update existing code easier, use different stacks for various components, and scale a component independently from one another. 
 
4. List and discuss the benefits of using Microservices. 
 
- These are the benefits of using Microservices: 

> Independently deployable - this means that because the services are being provided in a smaller and in an independent manner, it promises organizations a benefit to what frustrations an organization has with small changes that usually take a long amount of time to finish.

> Right tool for the job - this means that Microservices eases the process of having every component of an application to have a common stack, data model, and database even though there are better tools for specific elements.

> Precise scaling - this means that individual services can also be individually deployed and scaled with the help of Microservices. If done correctly, it requires less infrastructure because it enables precise scaling of components that require it, instead of the whole application.

5. List and discuss the similarities and differences of SOA and Microservices.
> SOA is mainly an enterprise-wide effort to help standardize of how services talk and integrate with each other, while microservices is only applied to application-specific scenarios.

> Simply put, SOA focuses more in an enterprise-scope, while Microservices Architecture focuses more in an application scope.

> Microservices enables an application's internals to be broken up into pieces that can be independently changed, scaled, and administered. However, it does not define on how applications talk to one another, thus returning to the aspect of SOA.