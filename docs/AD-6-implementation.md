# Implementation Documentation for AD-6

To update the greeting message in the Spring Boot application, the following change was made:

1. In the HelloController class (src/main/java/com/example/springboot/HelloController.java), the index() method was modified.
2. The return statement in the index() method was updated to return the new greeting message "hayabusa" instead of the previous message.

This change ensures that when the root URL of the application is accessed, the new greeting message "hayabusa" will be displayed to the user.