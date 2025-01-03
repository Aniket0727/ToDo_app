# To-Do List API with FastAPI and SQLite

This project provides a simple **REST API** for managing a to-do list. It is built using **FastAPI** for the backend, with **SQLite** as the database for storing tasks. The API supports the following operations:

1. **Create** a task with a title, description, and status.
2.  **Read** all tasks or a specific task by ID.
3.  **Update** the status of a task (pending, in-progress, completed).
4.  **Delete** a task by ID.

The API also provides **Swagger UI** documentation for easy testing and interaction with the endpoints.

# Features

1. **POST /tasks**: Create a new task.
2. **GET /tasks**: Fetch all tasks.
3. **GET /tasks/{id}**: Fetch a task by its ID.
4. **PUT /tasks/{id}**: Update the task status (pending, in-progress, completed).
5. **DELETE /tasks/{id}**: Delete a task by its ID.

## Dependencies

This project requires the following Python packages:

1. **FastAPI**: A modern, fast (high-performance) web framework for building APIs with Python.
2. **Uvicorn**: A lightning-fast ASGI server to run the FastAPI app.
3. **SQLite3**: A simple, serverless SQL database to store the task data.
4. **Pydantic**: For data validation and parsing request bodies in the FastAPI app.

To install the dependencies, run the following command:

pip install fastapi uvicorn sqlite3 pydantic
