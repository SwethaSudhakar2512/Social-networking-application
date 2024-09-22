# Social-networking-application
# Social Network API

## Requirements

- Docker
- Docker Compose

## Setup

1. Clone the repository.
2. Run `docker-compose up --build` to start the services.
3. Access the API at `http://localhost:8000`.

## API Endpoints

- **POST /api/signup/**: Sign up a new user.
- **POST /api/login/**: Login with email and password.
- **GET /api/users/**: Retrieve all users (Requires authentication).
