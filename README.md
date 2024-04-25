User Service - RBAC, JWT Auth, Docker, Redis, and PostgreSQL

This project is a user service and authorization system built with Golang (gin fw). The system provides authentication and authorization using Role-Based Access Control (RBAC) and JSON Web Token (JWT).

Features:

-    Role-Based Access Control (RBAC): Categorize users into different roles (e.g., admin, editor, user) and define which endpoints each role can access and what actions they can perform.
-    JSON Web Token (JWT): Use JWT to securely store user session information and for authentication.
-    Docker: Facilitate development and deployment environment using Dockerfile.
-    Redis: Use Redis for data caching and performance optimization.
-    PostgreSQL: Use PostgreSQL for the database.

Setup:

-    Install the required prerequisites (Docker, Redis, PostgreSQL).
-    Clone the project: git clone https://github.com/makseli/User-RBAC-Role-Based-Access-Control-in-Golang-with-Postgresql.git
-    Start Docker containers by running the command: docker-compose up -d.
-    Connect to the PostgreSQL database and perform the necessary configuration.
-    API documentation can be found at http://localhost:8080/docs.

Usage:

-    To create a user: Use the POST /api/v1/users endpoint.
-    To log in a user: Use the POST /api/v1/login endpoint.
-    For an authorized user to perform an action: Send a request to the relevant endpoint with the JWT token.

Notes:

-    This project is for development purposes and is not production-ready.
-    In a real application, you may need to implement more complex RBAC rules and error handling mechanisms.
-    For security, remember to securely store JWT tokens and other sensitive information.

Contribute:

If you want to contribute to this project, feel free to open pull requests and issues.
