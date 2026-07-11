# 📘 Assignment: REST APIs with FastAPI

## 🎯 Objective

Build a simple REST API using FastAPI that supports creating and retrieving records. Practice route creation, request validation, and JSON responses.

## 📝 Tasks

### 🛠️ Create Basic API Endpoints

#### Description
Set up a FastAPI app and implement endpoints for health checks and listing resources.

#### Requirements
Completed program should:

- Include a root endpoint that returns a status message
- Include a `GET` endpoint that returns a list of items in JSON
- Run locally with Uvicorn without startup errors

### 🛠️ Add Create-and-Validate Behavior

#### Description
Implement a `POST` endpoint that accepts input data, validates it with a Pydantic model, and stores it in memory.

#### Requirements
Completed program should:

- Define a Pydantic model for request validation
- Reject invalid payloads with FastAPI validation errors
- Return the created object in the response with a unique ID
