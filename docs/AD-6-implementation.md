# Implementation Documentation for AD-6

To update the greeting message in the Spring Boot application, the following change was made:

1. In the HelloController class (src/main/java/com/example/springboot/HelloController.java), the return value of the index() method was modified from "Hello from Spring Boot with Kafka!" to "hayabusa".

This change ensures that when the root URL of the application is accessed, it will now display "hayabusa" instead of the previous greeting message.

No other changes were necessary as the rest of the application's functionality remains unaffected by this update.