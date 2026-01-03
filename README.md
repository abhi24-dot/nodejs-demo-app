NodeJS Demo App – Task 1 (DevOps)

This is a simple Node.js demo application created for practicing DevOps concepts and CI/CD pipelines.

What I did

Created a basic Node.js application (index.js)

Added a Dockerfile to containerize the application

Configured a GitHub Actions workflow (.github/workflows/main.yml) that:

Installs dependencies

Runs tests

Builds a Docker image for the application

Pushes the Docker image to Docker Hub

The workflow is automatically triggered whenever code is pushed to the repository.

On every push, the workflow runs and uploads the latest Docker image of the application to Docker Hub.

How to run locally

Clone the repository

Run npm install

Run npm start
