# 🍃 Spring Cloud Micro-services Architecture 
# Under development... 🚀

- [Customer micro-service](https://github.com/Slimani-CE/customer-service)
- [Inventory micro-service](https://github.com/Slimani-CE/inventory-service)
- [Billing micro-service](https://github.com/Slimani-CE/billing-service)
- [Gateway micro-service](https://github.com/Slimani-CE/gateway-service)
- [Eureka discovery](https://github.com/Slimani-CE/eureka-discovery)

# Table of Contents
- [📖 Overview](#-overview)
- [📖 Architecture](#-architecture)
# 📖 Overview
This project is a microservices-based architecture designed to handle various functionalities related to customer management, inventory management, and billing. It involves the development and deployment of multiple microservices using Java frameworks and libraries.

1. Customer-service:

    * Creation of the Customer microservice, which handles customer-related operations.

    * Implementation of the Customer entity and the CustomerRepository interface using Spring Data.

    * Deployment of the RESTful API of the microservice using Spring Data Rest.

    * Testing of the Customer microservice. 

2. Inventory-service:

    * Creation of the Inventory microservice, responsible for managing product inventory.
    * Implementation of the Product entity and the ProductRepository interface using Spring Data.
    * Deployment of the RESTful API of the microservice using Spring Data Rest.
    * Testing of the Inventory microservice.

3. Gateway service:

    * Creation of the Gateway service using Spring Cloud Gateway.
    * Testing of the service proxy using both static configuration based on the application.yml file and static configuration based on Java configuration.

4. Registry Service:

    * Creation of the Registry Service based on Netflix Eureka Server, which acts as a service registry.
    * Testing of the proxy using dynamic route management to communicate with the registered microservices in the Eureka Server.
5. Billing-Service:

    * Creation of the Billing microservice using Open Feign to communicate with the Customer-service and Inventory-service.
6. Angular client:

    * Creation of an Angular client application that allows the display of invoices.
    
This project demonstrates the implementation of microservices architecture using various technologies and frameworks such as Spring Data, Spring Cloud Gateway, Netflix Eureka Server, and Open Feign. It showcases the development of individual microservices with their respective functionalities and communication between them. Additionally, it includes the creation of a client application using Angular to provide a user interface for viewing invoices.

# 📖 Architecture