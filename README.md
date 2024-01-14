# REST-API-with-H2-In-memory-Database

This repository contains a REST API application that utilizes an in-memory H2 database, enforces field validations, and provides customized exception handling.

# Key Features
In-memory H2 database: Data is stored in a lightweight, ephemeral database, making it ideal for testing and development environments.
Field validations: Data integrity is ensured through validation rules applied to incoming requests.
Global exception handler: Provides a consistent approach to handling exceptions, with overridden messages for improved user experience.
# Getting Started
Prerequisites:
Java JDK 11 or later
Maven
# Clone the repository:
Bash
git clone https://github.com/your-username/REST-API-with-H2-Database.git
Use code with caution. Learn more
# Run the application:
Bash
cd REST-API-with-H2-Database
mvn spring-boot:run
Use code with caution. Learn more
# API Endpoints
(Could be found in the controller classes)
# Technologies Used
Spring Boot
Spring Data JPA
H2 Database
# Validation API
- The application leverages the `@ResponseBody` annotation to seamlessly handle serialization and deserialization of objects in controllers.
- This annotation ensures that objects returned from controller methods are automatically converted to JSON (or other supported formats) and sent back to the client.
- It also facilitates the deserialization of incoming JSON data into Java objects in request bodies.

# Additional Information
Global exception handling: The application uses a global exception handler to customize error messages and provide meaningful feedback to clients.
Field validations: Validation rules are defined for relevant fields to ensure data consistency and prevent invalid data from being persisted.
# Contributing
Fork the repository
Create a branch for your changes
Commit your changes and push to your fork
Create a pull request
 # BEAM INC.
