# secure_api

A simple FastAPI application packaged with Docker.

## Getting Started

### Build the Docker image

```bash```
docker build -t myapp .


Run the Docker container

docker run -p 8000:8000 myapp

Open your browser and go to:

http://localhost:8000/

You should see the JSON response:

{"message": "Hello, world!"}