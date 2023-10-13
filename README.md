# Todo List Application with Spring Boot

This is a simple Todo List application developed using Spring Boot. It allows users to create, read, update, and delete tasks in a todo list. This project serves as a basic example of building a RESTful API with Spring Boot.

## Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- H2 Database (for simplicity; you can replace it with a different database)
- Maven

## Features

- Create a new task
- Read a list of tasks
- Read a single task by ID
- Update a task
- Delete a task

## Getting Started

These instructions will help you get a copy of the project up and running on your local machine for development and testing purposes.

1. **Clone the repository**:

   ```bash
   git clone https://github.com/nelson2804/TODOLIST.git
   ```

2. **Navigate to the project folder**:

   ```bash
   cd todo-list-spring-boot
   ```

3. **Run the application**:

   You can use your IDE to run the Spring Boot application or use Maven from the command line:

   ```bash
   mvn spring-boot:run
   ```

   The application will start on `http://localhost:8080`. You can access it through your web browser or use API client tools like Postman.

## API Endpoints

- **GET /tasks**: Get a list of all tasks.
- **GET /tasks/{id}**: Get a task by ID.
- **POST /tasks**: Create a new task.
- **PUT /tasks/{id}**: Update an existing task by ID.
- **DELETE /tasks/{id}**: Delete a task by ID.

Example usage with `curl`:

- Create a task:

   ```bash
   curl -X POST -H "Content-Type: application/json" -d '{"title":"Buy groceries","completed":false}' http://localhost:8080/tasks
   ```

- Get a list of tasks:

   ```bash
   curl http://localhost:8080/tasks
   ```

- Get a task by ID:

   ```bash
   curl http://localhost:8080/tasks/{id}
   ```

- Update a task:

   ```bash
   curl -X PUT -H "Content-Type: application/json" -d '{"title":"Buy groceries","completed":true}' http://localhost:8080/tasks/{id}
   ```

- Delete a task:

   ```bash
   curl -X DELETE http://localhost:8080/tasks/{id}
   ```

## Contributing

Feel free to contribute to the project. You can create pull requests and report issues. All contributions are welcome!

## License

This project is open-source and available under the [MIT License](LICENSE).

---

Enjoy your new Spring Boot Todo List Application! If you have any questions or need further assistance, please don't hesitate to ask.

## Contact

If you have any questions, issues or suggestions, please feel free to contact the developer:

Name: Nelson Arrais
Email: nelsonarrais9@gmail.com

## Make a Donation

If you wish to support the continued development of this project, you can make a donation via PIX. Your generosity is greatly appreciated.

PIX key: nelsonarrais9@gmail.com

Nubank