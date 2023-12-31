
# School Management System - Spring Boot Project

This Spring Boot project is a school management system that allows you to manage entities related to a school. It includes four main entities: Filiere, User, Role, and Student, and provides API endpoints for managing them. The project also integrates Swagger UI for easy API documentation and testing.


## Project Structure

The project follows a typical Spring Boot project structure:

- **src/main/java/ma.projet.example**: Contains the Java source code.
  - **controller**: Contains controllers for managing the API endpoints.
  - **repository**: Provides data access to the database.
  - **service**: Business logic and service layer.
  - **model**: Entity classes for filiere, user, role, and student.
  - **dto**: Data Transfer Objects for request and response.
- **src/main/resources**: Contains application properties, Swagger configuration, and other resources.

## Entities

1. **Filiere**: Represents a field of study.
2. **User**: Represents a user of the application.
3. **Role**: Defines user roles and permissions.
4. **Student**: Represents a student entity.

## Controllers

1. **FiliereController**: Manages filiere-related operations.
2. **RoleController**: Manages role-related operations.
3. **StudentController**: Manages student-related operations.

## Repositories

1. **FiliereRepository**: Provides data access for filiere entities.
2. **RoleRepository**: Provides data access for role entities.
3. **StudentRepository**: Provides data access for student entities.

## Services

1. **FiliereService**: Business logic and operations for filiere entities.
2. **RoleService**: Business logic and operations for role entities.
3. **StudentService**: Business logic and operations for student entities.

## Swagger UI

This project integrates Swagger UI for easy API documentation and testing. You can access the Swagger UI at (http://localhost:8088/swagger-ui/index.html#/) once the application is running. It provides a user-friendly interface to explore and test the available API endpoints.

## Getting Started

Follow these steps to set up and run the project:

1. Clone the repository: `git clone (https://github.com/BAJEDDI/springbootproject`
2. Open the project in your favorite IDE.
3. Configure your database connection in `application.properties` or `application.yml`.
4. Build the project using Maven: `mvn clean install`.
5. Run the application: `mvn spring-boot:run`.
6. Access the API and Swagger UI at (http://localhost:8088/swagger-ui/index.html#/)

## API Endpoints

You can find the detailed documentation for API endpoints in the Swagger UI. Use Swagger UI to explore and test the available APIs.

## Technologies Used

- Spring Boot
- Maven
- Spring Data JPA
- Swagger UI

## Author

- BAJEDDI

## Screenshots
**Swagger ui**
**Student controller**
![image](https://github.com/BAJEDDI/springbootproject/assets/147507670/e9842238-addb-4fd8-b0be-4f04bf9b5101)
**1**
![image](https://github.com/BAJEDDI/springbootproject/assets/147507670/26e44e51-cd02-4908-9f9b-2b284be175fa)
![image](https://github.com/BAJEDDI/springbootproject/assets/147507670/b85f1fdb-86aa-4c2c-896d-98527ce555a9)
**Role controller**
![image](https://github.com/BAJEDDI/springbootproject/assets/147507670/bc96c852-ea83-4aa7-a99c-ddc788620f7d)
**1**
![image](https://github.com/BAJEDDI/springbootproject/assets/147507670/fe37b093-d6cc-4171-9243-4dd4902e78c8)
![image](https://github.com/BAJEDDI/springbootproject/assets/147507670/a8f07c5c-cc64-4513-a7b1-8b1e13f4f18d)
**Filiere controller**
![image](https://github.com/BAJEDDI/springbootproject/assets/147507670/a66e7d8b-6648-44ca-89d9-fed00f05f0cc)
**1**
![image](https://github.com/BAJEDDI/springbootproject/assets/147507670/5ad14a36-bf6a-4aa8-896a-087d1e75d44f)
![image](https://github.com/BAJEDDI/springbootproject/assets/147507670/5bbcb751-714d-4397-bb91-176890a46c5f)
**postman**
   **filiere**
![image](https://github.com/BAJEDDI/springbootproject/assets/147507670/f8c74b91-c66b-4ece-823d-f062ef579143)
   **roles**
![image](https://github.com/BAJEDDI/springbootproject/assets/147507670/6406148e-029c-4dec-906c-2a0e4c055ed8)
**student**
![image](https://github.com/BAJEDDI/springbootproject/assets/147507670/5d0d6b42-d9c1-4c64-9441-4fb435376ee9)

