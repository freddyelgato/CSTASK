# CSTASK - "Hello World" Application in C#

This project is a simple "Hello World" web application created in C# and deployed in a Docker container. You can run it locally and access it in your browser.

## Requirements
- **Docker**: [Install Docker](https://www.docker.com/get-started) if you don’t have it yet.

## Installation Instructions

1. **Clone this repository**:
   ```bash
   git clone https://github.com/freddyelgato/CSTASK.git

2. **Run the application in Docker**:
   ```bash
   docker run -d -p 8080:8080 --name CSTASK 2424833f/cstask
 - **d**: Runs the container in detached mode.
 - **p8080**: Maps container port 8080 to your machine's port 8080.

3. **Access the application in your browser to see the "Hello World" message**:
   ```bash
   http://localhost:8080
   
## Useful Commands
- View containers: `docker ps`.
- Stop the container: `docker stop CSTASK`.
- Remove the container: `docker rm CSTASK`.

## Enlaces
- Docker Hub Image: [docker ps](https://hub.docker.com/repository/docker/2424833f/cstask).
  
- GitHub Repository: [docker stop CSTASK](https://github.com/freddyelgato/CSTASK).
