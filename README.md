# Django Berry

A Django-based web application.

## Quick Start

### Prerequisites
- Docker

### Build and Run

1. Build the Docker image:
   ```
   docker build -t django_berry .
   ```

1. Run the container with a specific name:
   ```
   docker run --name django_berry -p 8000:8000 django_berry
   ```

3. Access the application at `http://localhost:8000/graphql`