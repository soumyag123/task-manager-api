# Task Manager API

A REST API built with Java and Spring Boot to manage tasks.

## Tech Stack
- Java 21
- Spring Boot 3.x
- Spring Data JPA
- H2 In-Memory Database

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /tasks | Get all tasks |
| GET | /tasks/{id} | Get task by ID |
| POST | /tasks | Create a task |
| PUT | /tasks/{id} | Update a task |
| DELETE | /tasks/{id} | Delete a task |

## How to Run

1. Clone the repo
   git clone https://github.com/YOURUSERNAME/task-manager-api.git

2. Navigate to project folder
   cd task-manager-api

3. Run the app
   ./mvnw spring-boot:run

4. API runs on http://localhost:8081

## Sample Request

POST /tasks
{
    "title": "Learn Spring Boot",
    "completed": false
}

## Sample Response
{
    "id": 1,
    "title": "Learn Spring Boot",
    "completed": false
}