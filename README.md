# Node.js RESTful API with Express & MongoDB

## Description
This API allows users to manage a list of items using CRUD operations.

## Endpoints

### Get All Items
`GET /items`
- Response: `200 OK`
- Example:
```json
[
  { "name": "Laptop", "description": "Gaming laptop", "price": 1200 }
]
