# 📘 Assignment: REST APIs with FastAPI

## 🎯 Objective

Learn to build REST APIs using the FastAPI framework in Python. You'll create endpoints for handling HTTP requests, manage data, and implement basic CRUD operations.

## 📝 Tasks

### 🛠️ Set Up FastAPI Application

#### Description
Install FastAPI and create a basic application with a root endpoint that returns a welcome message.

#### Requirements
Completed program should:

- Install FastAPI and uvicorn using pip
- Create a FastAPI application instance
- Define a GET endpoint at "/" that returns a JSON response with a welcome message
- Run the server and verify the endpoint works

### 🛠️ Implement CRUD Operations

#### Description
Add endpoints for creating, reading, updating, and deleting items in a simple in-memory data store.

#### Requirements
Completed program should:

- Define a data model for items (e.g., with id, name, description)
- Implement GET /items to retrieve all items
- Implement POST /items to create a new item
- Implement GET /items/{id} to retrieve a specific item
- Implement PUT /items/{id} to update an item
- Implement DELETE /items/{id} to delete an item
- Handle cases where items don't exist (return appropriate HTTP status codes)