# Testing Steps for AD-7

1. Ensure you have Java and Maven installed.
2. Clone the repository and navigate to the project directory.
3. Run the command: mvn clean install
4. Once the build is successful, run the command: mvn spring-boot:run
5. The application should start without any errors.
6. Open a web browser or use a tool like cURL to make a GET request to http://localhost:8080/greeting
7. Verify that the response is: "Hello from Spring Boot with Kafka!"
8. The application is running successfully with the Kafka dependencies included.