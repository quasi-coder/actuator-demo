# actuator-demo
#Accessing the actuator
http://localhost:8080/actuator

#Accessing the info endpoint
http://localhost:8080/actuator/info

#Accessing the health endpoint
http://localhost:8080/actuator/health

#Accessing the metrics endpoint
http://localhost:8080/actuator/metrics

#Enable the default properties of actuator by adding below line in application.properties
management.endpoints.web.exposure.include=*

