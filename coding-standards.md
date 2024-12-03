# Node.js Coding Standards

## Naming Conventions
- **Variables and functions**: Use camelCase (e.g., `getUserData`, `isValidEmail`).
- **Classes and components**: Use PascalCase (e.g., `UserController`, `AuthService`).
- **Files and folders**: Use lowercase with hyphens separating words (e.g., `user.controller.js`, `auth.service.js`).

## Code Formatting
- Use **Prettier** to format code automatically.
- **ESLint** should be configured to ensure consistent coding styles across the project.

## Comments
- **Function Comments**: Each function should have a description of its purpose, parameters, and return type.
- **Complex Logic**: Any complex or non-obvious logic should be explained using comments.

## Best Practices
- Always validate inputs to prevent security risks.
- Use asynchronous functions with **async/await** for better readability.
- Keep functions small and focused on one responsibility.

## Error Handling
- Use **try-catch** blocks in async functions to handle errors.
- All errors should be passed through a global error handler.
- Ensure that appropriate HTTP status codes are used in responses.