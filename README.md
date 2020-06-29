Task – 1 Implementing REST Service and a Client Using REST Template

This Application should provide a simple REST API for storing Details of Doctors 

The data is stored Using HIkari Database. 

Need to Create a REST API Using Spring DATA JPA 

Need to Create a Client Application to Access the Service

Please follow the instructions in the todo section

Todo:
•	Create a Java Bean to Represent Patient
•	Create a Java Bean to Represent Doctor with a List of Patients
o	Doctor Bean should have Specialization and Location apart from the other properties decided by the developer
•	Create a Repository to Store Doctor Details
•	Expose a REST endpoints to add and find, update and Delete Doctor details
Create a Spring MVC Based Application to access the Exposed REST Points using Rest Template and display the details of Doctors and Patients in a JSP or thymeleaf template.


Task – 2  : REST Application with Swagger Documentation and  JPA Custom Methods 


Todo:
•	Create Methods and Rest Endpoints to find the Doctors by Specialization and Location
•	Add the Swagger  Module and Document the REST API suitably
•	Add HATEOS Support When the User search for Doctor API should return Doctor details with List of Clinical Labs in the Area where doctor is located.
Use the Spring MVC Based Application to access the Exposed REST Points using Rest Template and display the details .

Task – 3: Implementing Feign Client
 
Todo:
•	Create  Spring Boot Applications for Eureka Registry and Spring Config Server with git support
•	Register the REST Service created in earlier task with Eureka Server
•	Create a Feign Client for the registered service 

