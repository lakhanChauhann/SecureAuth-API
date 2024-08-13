# SecureAuth-API
# User Registration and Login API

A robust user authentication REST API built with Node.js, Express, and MongoDB Atlas, designed with security as a priority.

- **JSON Web Token (JWT)** for authentication and authorization.
- **Bcrypt** for secure password hashing.
- **Regular expressions** for enforcing password criteria.
- **Input validation** to ensure data integrity.

---

## Setup Instructions

1. Create a **.env** file in the root directory of the project.
2. Add the following environment variables:

    ```env
    MONGODB_URI=your_mongodb_database_uri
    JWT_SECRET_KEY=your_secret_key_for_jwt
    ```

---

## API Endpoints

### GET Requests

- **`GET /user/login`** - Endpoint for user login.
- **`GET /user/register`** - Endpoint for user registration.
- **`GET /user/profile`** - Endpoint to retrieve user profile information.

### POST Requests

- **`POST /user/login`** - Endpoint to authenticate a user.
- **`POST /user/register`** - Endpoint to register a new user.
- **`POST /user/is-token-valid`** - Endpoint to validate a JWT.
- **`POST /user/change-password`** - Endpoint to change the user's password.

### DELETE Requests

- **`DELETE /user/delete-account`** - Endpoint to delete a user account.

---

## Developed by

**Lakhan Chauhan**
