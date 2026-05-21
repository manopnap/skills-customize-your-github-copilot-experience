# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a simple REST API using the FastAPI framework so you can practice defining routes, validating requests with Pydantic, and returning JSON responses.

## 📝 Tasks

### 🛠️ Build the API foundation

#### Description

Create a FastAPI application with a root endpoint and run it locally with Uvicorn.

#### Requirements
Completed program should:

- Create a FastAPI app in `starter-code.py`
- Define a root `GET /` endpoint that returns a welcome JSON message
- Include the application title and version in the response
- Run the app using `uvicorn starter-code:app --reload`

### 🛠️ Implement item CRUD endpoints

#### Description

Add routes for working with a collection of items using Pydantic models and an in-memory store.

#### Requirements
Completed program should:

- Define a Pydantic model `Item` with `id`, `name`, `description`, and `price`
- Implement `GET /items` to return all items
- Implement `GET /items/{item_id}` to return a specific item
- Implement `POST /items` to accept and return a new item

### 🛠️ Add request validation and error handling

#### Description

Extend the API with update and delete operations and handle invalid requests with proper HTTP responses.

#### Requirements
Completed program should:

- Implement `PUT /items/{item_id}` to update an existing item
- Implement `DELETE /items/{item_id}` to remove an item from the store
- Return `404` when a requested item does not exist
- Use appropriate status codes for success and error responses
