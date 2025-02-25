# dockerized-flask-app
A simple Flask web application containerized using Docker. This project demonstrates how to set up a minimal Flask app with a Dockerfile, making it easy to deploy and run in a containerized environment.

## To build the Docker image:

`docker build -t flask_app .`

## To check available Docker images:

`docker images`

## To run the container:

`docker run --name cont1 -dit -p 80:5000 flask_app
`


