# 📘 Assignment: REST APIs with FastAPI

## 🎯 Objective

Build a RESTful API using FastAPI and Pydantic models to practice endpoint design, request validation, and JSON responses.

## 📝 Tasks

### 🛠️ Define API Models and Routes

#### Description
Create the data models and API routes for a simple service that manages items or resources.

#### Requirements
Completed program should:

- Define Pydantic models for request and response validation
- Include at least `GET`, `POST`, and `GET /items/{item_id}` endpoints
- Return JSON responses for each endpoint

### 🛠️ Add Request Validation and Error Handling

#### Description
Validate input data and handle invalid requests or missing resources.

#### Requirements
Completed program should:

- Validate request payloads using Pydantic
- Return clear HTTP error responses for invalid input or missing items
- Use appropriate status codes such as `201` for creation and `404` for not found

### 🛠️ Run and Test the API

#### Description
Run the FastAPI app and test the endpoints with example requests.

#### Requirements
Completed program should:

- Start the app with `uvicorn`
- Include example request data or sample HTTP requests
- Confirm the API returns expected JSON and status codes
