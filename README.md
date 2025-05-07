# demoSpring

A simple Spring Boot project demonstrating basic CRUD operations using Spring Data JPA.

## 🚀 Technologies Used

- Java 21
- Spring Boot
- Spring Web
- Spring Data JPA
- H2 / MySQL (configure as needed)
- Maven

## 📂 Project Structure

src/
├── main/
│ ├── java/com/example/demoSpring/
│ │ ├── controller/ # REST controller
│ │ ├── entity/ # JPA entities
│ │ └── repo/ # Repository interfaces
│ └── resources/
│ └── application.properties


Endpoint for H2 Database:
http://localhost:8080/h2-console/


Related API Endpoints
Method	Endpoint	                                                     Description
GET	    http://localhost:8080/api/user/save	                           Saves a sample user
GET     http://localhost:8080/api/user/all                             Get all user info
GET     http://localhost:8080/api/user/4                               Get user by user id
PUT     http://localhost:8080/api/user/update/1                        Update a user by Id
DELETE  http://localhost:8080/api/user/delete/1                        Delete a user by Id
GET     localhost:8080/api/user/findByEmail?email=abc@gmail.com        Find user by email

sample json data:
{
  "name": "rasel",
  "email": "abc@gmail.com",
  "password": "1234"
}

