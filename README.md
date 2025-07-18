
# Getting Started with Docker: Welcome App

This guide helps you run a Dockerized Flask-based Welcome App on your local machine using Docker.

## Prerequisites

- Docker Desktop must be installed and running.
- Basic terminal access (Command Prompt or PowerShell).

## Steps to Run the App

### 1. Launch Docker Desktop

Ensure Docker is running in the background.

### 2. Open Terminal

Open a terminal window (e.g., Command Prompt or PowerShell).

### 3. Pull the Docker Image

Run the following command to pull the Docker image from Docker Hub:

```bash
docker pull shivanshupandey28/welcome-app:latest
````

### 4. Verify the Image

Check if the image was downloaded:

```bash
docker images
```

You should see `shivanshupandey28/welcome-app` listed.

### 5. Run the Docker Container

Start the container and expose it on port 5000:

```bash
docker run -d -p 5000:5000 shivanshupandey28/welcome-app:latest
```

The app will be available at: [http://localhost:5000](http://localhost:5000)

## Summary

```bash
docker pull shivanshupandey28/welcome-app:latest
docker run -d -p 5000:5000 shivanshupandey28/welcome-app:latest
```

