# Jenkins CI/CD Docker Demo Application

This repository demonstrates a complete CI/CD pipeline using:

- GitHub
- Jenkins
- Docker
- Docker Hub
- AWS EC2

## CI/CD Workflow

GitHub → Jenkins → Docker Build → Docker Hub Push

## Docker Image

amitkumar06ster/jenkins-demo-app:latest

## Build

docker build -t jenkins-demo-app .

## Run

docker run -d -p 8080:8080 jenkins-demo-app
