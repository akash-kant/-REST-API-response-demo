# Hello World REST API

This project demonstrates a simple REST API built using Spring Boot. The API responds with the message `"Hello, World!"` when accessed via a `GET` request at the `/hello` endpoint.

---

## Features
- Simple and beginner-friendly implementation.
- Uses Spring Boot for rapid development and ease of deployment.
- Returns `"Hello, World!"` as plain text.

---

## Technologies Used
- Java: Programming language.
- Spring Boot: Framework for creating REST APIs.

---

## Requirements
- Java Development Kit (JDK) 17 or above.
- Maven: Build and dependency management tool.
- A tool for testing the API (e.g., Postman, cURL, or a browser).

---

## Setup Instructions

### 1. Clone the Repository
bash
git clone ""https://github.com/your-username/your-repo-name.git""
cd your-repo-name

### 2. Build and Run the Application
- Using Maven:
mvn spring-boot:run
- Manually (if Maven is unavailable):
mvn clean install
- java -jar target/your-project-name-0.0.1-SNAPSHOT.jar

### 3. API Usage
- Endpoint
- GET /hello
- Response
- Status: 200 OK
- Body: "Hello, World!"

### 4. Testing the API
- Using Postman
1. Open Postman and create a new GET request.
2. Set the URL to: http://localhost:8080/hello
3. Send the request and view the response.
- Using cURL
curl http://localhost:8080/hello
- Using a Browser
Visit: http://localhost:8080/hello
