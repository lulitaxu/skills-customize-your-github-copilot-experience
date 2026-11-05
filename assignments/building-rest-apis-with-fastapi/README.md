# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build a simple REST API with the FastAPI framework, including routes, request data, and JSON responses.

## 📝 Tasks

### 🛠️	Create Your First FastAPI App

#### Description
Create a FastAPI application with a root route that returns a JSON greeting message.

#### Requirements
Completed program should:

- Create a FastAPI app instance
- Respond to `GET /` with a JSON message
- Run with uvicorn

### 🛠️	Add Item Routes

#### Description
Add routes to list, create, and read individual items stored in memory.

#### Requirements
Completed program should:

- Respond to `GET /items` with a list of items
- Create an item via `POST /items`
- Return a 404 response for an unknown item id
