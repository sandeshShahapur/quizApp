# Quiz Application

Backend implementation of a Quiz Application through the use of RESTful API with CRUD operations for questions and quizzes. It's built using Spring Boot, following the MVC architecture, and managed with Maven. You can use Postman to test the API.

## Local Hosting Instructions

Follow these steps to locally host the project and test the API using Postman:

### Prerequisites

- Java JDK (8 or later) installed
- Maven installed
- Postman installed (for testing the API)

### Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/sandeshShahapur/quizApp.git
   cd monolith-quiz-application

2. Build the project using Maven:

    ```sh
    mvn clean install

3. Run the application:

    ```sh
    mvn spring-boot:run

The application will be accessible at `http://localhost:8080`

### Using Postman to Test the API
1. Testing the API:
  - Utilize the various requests to interact with the API:
    - Create new questions and quizzes
    - Retrieve questions and quizzes
    - Update existing questions and quizzes
    - Delete questions and quizzes

# Contributing
Contributions aren't welcome.
