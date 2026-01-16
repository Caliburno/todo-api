# Todo List API

RESTful API for task management built with Spring Boot.

## Technologies

- Java 21
- Spring Boot 3.5.9
- Spring Data JPA
- H2 Database
- Maven
- Lombok

## Features

- ✅ CRUD operations for tasks
- ✅ Input validation
- ✅ Exception handling
- ✅ API documentation with Swagger
- 🚧 User authentication (coming soon)
- 🚧 MySQL integration (coming soon)

## Getting Started

### Prerequisites

- Java 17 or higher
- Maven 3.6+

### Installation

1. Clone the repository
```bash
git clone https://github.com/Caliburno/ToDoList.git
cd ToDoList
```

2. Run the application
```bash
mvn spring-boot:run
```

3. Access the API at `http://localhost:8080`

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/tasks | Get all tasks |
| GET | /api/tasks/{id} | Get task by ID |
| POST | /api/tasks | Create new task |
| PUT | /api/tasks/{id} | Update task |
| DELETE | /api/tasks/{id} | Delete task |

## API Documentation

Once the application is running, visit:
- Swagger UI: `http://localhost:8080/swagger-ui.html`

## Project Status

🚧 Work in progress - Learning project for Spring Boot development

## Author

[Caliburno](https://github.com/Caliburno)

## License

This project is open source and available under the MIT License.
