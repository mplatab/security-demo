# Spring Security Basic Project

This project demonstrates the implementation of Spring Security in a basic application using **User** and **Roles** as entities.

## Features

- Authentication and authorization with Spring Security
- User entity for managing user data
- Role entity for defining user roles
- Basic role-based access control

## Technologies Used

- Java
- Spring Boot
- Spring Security
- Hibernate/JPA
- MySQL (or any other relational database)

## Prerequisites

Before running the project, ensure you have the following installed:

- Java JDK 17 or higher
- Maven
- MySQL (or another configured database)
- An IDE like IntelliJ IDEA or Eclipse

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd <project-directory>
   ```

2. **Configure the database**
    - Open `application.properties` (or `application.yml`).
    - Update the database connection settings:
      ```properties
      spring.datasource.url=jdbc:mysql://localhost:3306/your_database
      spring.datasource.username=your_username
      spring.datasource.password=your_password
      spring.jpa.hibernate.ddl-auto=update
      ```

3. **Build and run the application**
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

4. **Access the application**
    - The application will be available at `http://localhost:8080`.

## Endpoints

- **/login**: Login page for user authentication.
- **/admin**: Access restricted to admin roles.
- **/user**: Access for authenticated users.

## Future Improvements

- Add JWT-based authentication.
- Implement a frontend interface.
- Enhance security with OAuth2.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to contribute and enhance the project!
