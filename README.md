# dockerized-flask-app
A simple Flask web application containerized using Docker. This project demonstrates how to set up a minimal Flask app with a Dockerfile, making it easy to deploy and run in a containerized environment.

## Clone the repository
To get started, clone this repository to your local machine using the following command: <br>
`git clone <repo link>`

## To build the Docker image:

`docker build -t flask_app .`

## To check available Docker images:

`docker images`

## To run the container:

`docker run --name cont1 -dit -p 80:5000 flask_app

## To log into the container:

`docker exec -it cont1 bash`

## To stop and remove the container:

`docker stop cont1
docker rm cont1`

## To remove the image:
`docker rmi flask_app`

Now, you can access the Flask app by opening http://<your-server-ip> in your browser.

`


