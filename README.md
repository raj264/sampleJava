Sample Java Spring Boot REST API
This is a minimal Java Spring Boot application demonstrating basic REST API functionality, including GET and POST requests. It serves as a simple starting point for understanding Spring Boot and building RESTful services.

 Features
Spring Boot REST API

Sample GET and POST endpoints

DTO usage for request body mapping

Simple response handling

 Project Structure
css
Copy
Edit
sampleJava/
├── src/
│   └── main/
│       └── java/
│           └── com/
│               └── example/
│                   └── sample/
│                       ├── MainApplication.java
│                       ├── controller/
│                       │   └── SampleController.java
│                       └── dto/
│                           └── TestRequestDto.java
🔧 How to Run
Clone the repository

bash
Copy
Edit
git clone https://github.com/raj264/sampleJava.git
cd sampleJava
Build and run the application

bash
Copy
Edit
./mvnw spring-boot:run
Access the API

GET /hello – Returns a simple greeting

POST /postTest – Accepts a JSON request body and returns a response

 Sample Request (POST /postTest)
Request Body

json
Copy
Edit
{
  "name": "Raj",
  "email": "raj@example.com"
}
Response

json
Copy
Edit
{
  "message": "Received name: Raj and email: raj@example.com"
}
🛠 Tech Stack
Java 17+

Spring Boot

Maven

📄 License
This project is open-source and available under the MIT License.
