# File Upload Docker Compose

This repository contains the Docker Compose configuration for the File Upload System, which includes both the backend and frontend projects.

## Features

- Multi-container setup using Docker Compose
- Backend: Django and Django REST Framework
- Frontend: React and Material-UI
- PostgreSQL database

## Requirements

- Docker
- Docker Compose

## Setup

1. **Clone the repository:**

    ```sh
    git clone https://github.com/semahkadri/FileUpload-docker.git
    cd FileUpload-docker
    ```

2. **Ensure the backend and frontend repositories are cloned in the same parent directory:**

    ```sh
    git clone https://github.com/semahkadri/FileUpload-backend.git
    git clone https://github.com/semahkadri/FileUpload-frontend.git
    ```

    The directory structure should look like this:

    ```
    /path/to/parent-directory
    ├── FileUpload-backend
    ├── FileUpload-frontend
    └── FileUpload-docker
    ```

3. **Build and start the Docker containers:**

    ```sh
    docker-compose up --build
    ```

4. **Access the backend API:**

    Open your browser and go to `http://localhost:8000/api/`

5. **Access the frontend application:**

    Open your browser and go to `http://localhost:3000/`

## Project Structure

- `file-upload-backend/` - Backend project directory
- `file-upload-frontend/` - Frontend project directory
- `docker-compose.yml` - Docker Compose configuration file

## License

This project is licensed under the MIT License.
