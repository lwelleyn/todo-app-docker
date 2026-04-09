# Todo App — Docker

Simple todo application running in a Docker container.

## Tech stack
- Node.js
- Docker
- docker-compose (coming soon)

## How to run

1. Clone the repo:
git clone git@github.com:lwelleyn/todo-app-docker.git
cd todo-app-docker

2. Build the image:
docker build -t my-todo-app .

3. Run the container:
docker run -d -p 3000:3000 my-todo-app

4. Open in browser:
http://localhost:3000

## What I learned
- Writing a Dockerfile from scratch
- Building and running Docker images
- Port mapping between container and host
