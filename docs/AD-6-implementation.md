# Implementation Documentation for AD-6

To update the greeting message in the Spring Boot application, the following change was made:

1. In the HelloController class (src/main/java/com/example/springboot/HelloController.java), the return value of the index() method was changed from "Hello from Spring Boot with Kafka!" to "hayabusa".

This modification updates the greeting message that is displayed when accessing the root URL of the application. The @RestController annotation ensures that the returned string is directly written into the HTTP response body.