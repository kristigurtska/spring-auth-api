
## Description
A Spring Boot REST API that implements secure user authentication and authorization using JWT. Users can register and log in, and access protected endpoints using a token-based system. Passwords are securely stored using BCrypt hashing.

## Technologies Used
- Java
- Spring Boot
- Spring Security
- JWT 
- Spring Data JPA (Hibernate)
- SQL Server
- Maven
- Lombok

## How it works
- user registers with username, email, and password
- password is encrypted using BCrypt and stored in the database
- user logs in with email and password
- If credentials are valid, a JWT token is generated
- Token is sent in request headers to access protected endpoints
- Spring Security validates the token on each request
  
