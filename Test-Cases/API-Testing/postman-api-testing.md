# API Testing with Postman

---

# API Testing Overview

This project contains sample API testing scenarios performed using Postman.

Tested:
- GET requests
- POST requests
- PUT requests
- DELETE requests
- Status codes
- Response body validation
- Authorization

---

# GET Request Testing

## Test Case 001

### Endpoint
GET /users

### Objective
Verify users list is returned successfully

### Expected Result
- Status code is 200
- Response contains users data
- Response time is acceptable

---

# POST Request Testing

## Test Case 002

### Endpoint
POST /login

### Objective
Verify user can log in with valid credentials

### Request Body

```json
{
  "email": "test@test.com",
  "password": "123456"
}
