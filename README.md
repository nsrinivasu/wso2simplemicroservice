This repository consists
1) PeopleRestService microservice developed using MSF4J Framework, added swagger annotations and Junit tests and SOAP UI test suite.
It offers following resources
1)GET - getAllPeople
2)GET - getPeople
3)Post - addPerson
4)PUT - updatePerson
5)DELETE - remove person

2) Developed simple service using WSO2 eclipse tool, sends a message to service
It is simple scenario where a client makes request for people details by provide email address. The required information is available in a microservice deployed in the MSF4J profile of WSO2 Enterprise Integrator (WSO2 EI). Configured an API resource in the ESB profile of WSO2 EI that will receive the client request, instead of the client sending messages directly to the back-end service, thereby decoupling the client and the back-end service. 

