## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).

- Service-oriented architecture (SOA) is a method of software development that uses software components called services to create business applications. Each service provides a business capability, and services can also communicate with each other across platforms and languages. Developers use SOA to reuse services in different systems or combine several independent services to perform complex tasks.

For example, multiple business processes in an organization require the user authentication functionality. Instead of rewriting the authentication code for all business processes, you can create a single authentication service and reuse it for all applications. Similarly, almost all systems across a healthcare organization, such as patient management systems and electronic health record (EHR) systems, need to register patients. These systems can call a single, common service to perform the patient registration task.

2. List and discuss the characteristics of SOA.

- It supports loose coupling everywhere in the project: meaning the services and components in SOA are not very dependent with each other, this way if you change a service then it wont cause too much trouble for the other services.
 
- SOA supports interoperability: meaning any client can use the services even if their knowledge is not directly what type of technology the SOA uses. Its components being not very dependent with each other allows its services and system to work work together regardless of types of technologies, platform or programming languages it uses.

- It increases the quality of service: because of each services are like independent with each other therefore each service is specialized with something and can focus in it which helps improve the quality of service it will provide.

- It supports vendor diversity: SOA can use diverse technologies from more than just one vendor that can be utilized for different services.

- It promotes discovery and federation: SOA promotes discovery because it allows each components and services utilize each other. SOA also supports federation because it allows the distribution of its services to different loactions, group or other organizations

- It is location-transparent: SOA can be distributed to different location no matter where they are.

- It is still maturing and achievable idea: its capabality to grow is still there because it can adapt to the continues growth of technology.

3. Define Microservices.

- Microservices are an architectural and organizational approach to software development where software is composed of small independent services that communicate over well-defined APIs. These services are owned by small, self-contained teams.

Microservices architectures make applications easier to scale and faster to develop, enabling innovation and accelerating time-to-market for new features.

4. List and discuss the benefits of using Microservices.

- Improved Scalability: Each services has their own and independent resources, meaning if one mciroservice has problems with its resources or if it is experiencing high traffics then other microservices wont be affected  because it runs a different resources. This also allow changes like updates to happen without having to shutdown the whole system.

- Better Fault Isolation for More Resilient Applications: Problems like failures of a service are isolated or contained so that it wont affect other services, it is more effective because each service runs independently to others.

- Programming Language and Technology Agnostic: Developers can connect services that are built with diverse programming languages and Technology. This also allows it to adapt to new technology.

- Better Data Security and Compliance: Microservices offers each services to focus on a specific task that way a specific service can focus in implementing security measures at the service level reducing the risk of having problems when storing data in a signle database.


5. List and discuss the similarities and differences of SOA and Microservices.

Similarities:

- Its services are both independent to other services.
- Both supports the use of diverse number of Programming languages and technology
- Both allows each services/ microservices to grow independently

Differences;

- In SOA each service can connect with each other, in Microservice each microservice is smaller and specialized in a single task only and it does not share its resources to other microservice.
-SOA has a signle data storage that is shared by other services, Microservices dont share a signle storage because each microservice has its own storage.
-Microservice is designed to scale in the cloud environment, SOA is not.

6. Define Web Services.

- Web services are a type of internet software that use standardized messaging protocols and are made available from an application service provider's web server for use by a client or other web-based programs.

Web services can range from major services such as storage management or customer relationship management (CRM) down to much more limited services such as the furnishing of a stock quote or the checking of bids for an auction item. The term is sometimes also referred to as application services.

Users can access some web services through a peer-to-peer arrangement rather than by going to a central server. Some services can communicate with other services. This exchange of procedures and data is generally enabled by a class of software known as middleware.

The evolution of web services occurred as all major platforms were able to access the internet, but different platforms could not interact with each other. Web services were able to take platforms to the next level by publishing functions, message, programs or objects to the rest of the internet.

7. List and discuss the benefits of using Web Services.

- Exposing the Existing function on the network: It is like a program which its functions can be accessed or used remotely by others when it is connected to the network as long as they use HTTP requests.

- Interoperability: Some applications can use web services and Interoperability allows applications to communicate with each other, this also allows other applications to share data and services with each other. This basically allow applications to work together.

- Standardized Protocol: From the word protocol, this is like set of rules that a business follows which would give them advantages like wide range of choices, reduction in cost due to competition, and increase in quality. 

- Low Cost Communication: This basically allows you to implement/use web services and allow applications to communicate at low cost. 

8. List and discuss the characteristics of Web Services.

- XML-base: Web services uses XML to represent and exchange information between applications or systems. 

- Loosely Coupled: This basically means that each service is something like indepedent with other services, so that if one service is changed or updated it won't affect other services.

- Coarse-Grained: It provides more functions compared to fine-grained services. 

- Ability to be synchronous or Asynchronous: This basically means that it is more flexible because clients can do synchronous or Asynchronous operations . 

- Supports Remote Procedure Calls (RPCs): This allows clients to use Web services remotely because it is using a XML based protocol. 

- Supports Document Exchange: Because of Web services using XML, it now allows businesses to exchange documents between systems.

9. List and discuss the distinct roles in Web Services Architecture.

- Provider: It just basically just provide and create web services that clients can use whenver they need/want it.

- Requestor: It is basically an application that can interact with a web service.

- Broker: This helps the Requestor in finding services. It provides something called UDDI(Universal Description , Discovery and Integration) that allows application to find Web services. 

10. List and discuss the Web Services Components.

- SOAP: its a messaging protocol that uses XML to allow the exchanging of structured informations between applciations

- WSDL: it is also XML based that is used to describe the interface of a web services and how to use it. This is written in a languange understandable for computers

- UDDI: it is also XML base, but this help in publishing , finding, and accessing web services for those who need them.z    

References:

https://aws.amazon.com/what-is/service-oriented-architecture/#:~:text=you%20implement%20microservices%3F-,What%20is%20service%2Doriented%20architecture%3F,other%20across%20platforms%20and%20languages.

https://www.xenonstack.com/insights/service-oriented-architecture

https://blog.dreamfactory.com/7-key-benefits-of-microservices/

https://www.javatpoint.com/restful-web-services-characteristics-of-web-services#:~:text=Coarse%2Dgrained,-In%20the%20coarse&text=It%20provides%20broader%20functionality%20in,more%20coarse%2Dgrained%20service%20operations.

https://www.h2kinfosys.com/blog/what-is-web-service-architecture/#:~:text=The%20architecture%20of%20web%20service,the%20artifacts%20of%20web%20services.

https://www.geeksforgeeks.org/components-of-web-services/
