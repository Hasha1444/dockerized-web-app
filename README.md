# Dockerized Web Application

A simple Python Flask web application containerized using Docker.

## Technologies
- Python
- Flask
- Docker

## Build Docker Image

docker build -t dockerized-web-app .

## Run Container

docker run -p 5000:5000 dockerized-web-app

## Output

Open:
http://localhost:5000

Expected Output:
Hello from Docker!
