# React-nextjs
This is a Dockerfile and docker-compose setup for a basic, no extensions added, 
enviroment for [react-nextjs](https://react.dev/learn/start-a-new-react-project)

## Getting Started
1. Clone the Repository
First, clone this repository to your local machine:

2. build the docker-compose
```bash
docker-compose up --build
```

## Directory Structure
- `Dockerfile`: Contains instructions for building the Docker image for React-Nextjs.
- `docker-compose.yml`: Defines the Docker services, including how to build the Eleventy image and how to mount volumes for development.
- `package.json`: The npm manifest. 
- `/src`: The source directory where your Eleventy templates and content reside.
- `/public`: Public Assets

## Accessing the site
You can access the development server at the following address
[http://localhost:9001]

## Stopping the Server
To stop the server, press Ctrl + C in the terminal where Docker Compose is running. 

To remove the containers and networks created by Docker Compose, you can run:
```bash
docker-compose down
```

