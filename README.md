# SpringActuator

we can add actuator in application by adding starter dependency in pom.xml
we can access actuetor by url http://localhost:8080/actuator
By dafault only health is shown.To enable to all endpoints add below line in application.properties.

management.endpoints.web.exposure.include=*
