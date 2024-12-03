# API Guidelines for Node.js

## RESTful API
- All API routes must follow RESTful principles.
- Use meaningful HTTP status codes for responses:
  - **200 OK**: Successful request
  - **201 Created**: Resource created successfully
  - **400 Bad Request**: Invalid input
  - **401 Unauthorized**: Authentication required
  - **500 Internal Server Error**: Server-side error

## Controller Design
- Controllers should handle request parsing and response sending.
- Services should handle database requests like getting data from database
- Business logic should be moved to repositories, not handled in services.
  
## Request Validation
- Input validation should be done at the request level, not in controllers.
- Use libraries like **Joi** or **express-validator** to validate incoming requests.

## Security
- Always sanitize user inputs to avoid security vulnerabilities (e.g., SQL injection).
- Use **Helmet.js** and **CORS** for basic security hardening.
