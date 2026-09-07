# Hello World Spring Boot Application

This is a simple Spring Boot application that returns "Hello, World!" when accessed at the root URL ("/").

## Prerequisites

- Java 11 or higher
- Maven

## Getting Started

1. Clone the repository:

   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```
   cd hello-world
   ```

3. Build the project using Maven:

   ```
   mvn clean install
   ```

4. Run the application:

   ```
   mvn spring-boot:run
   ```

5. Open your web browser and go to:

   ```
   http://localhost:8080/
   ```

   You should see the message "Hello, World!".

## Project Structure

```
hello-world
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── example
│   │   │           ├── HelloWorldApplication.java
│   │   │           └── HelloController.java
│   │   └── resources
│   │       └── application.properties
│   └── test
│       └── java
│           └── com
│               └── example
│                   └── HelloWorldApplicationTests.java
├── pom.xml
└── README.md
```

## License

This project is licensed under the MIT License.