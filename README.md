# Simple Express App wrapped in Docker

This was to practice how to create a docker image and container from a simple app

## Docker Command

`docker ps`
Shows the containers that are running.

`docker build -t myimagename:1.0.0`
Builds a docker image from the DockerFile in the current folder using tag "myimagename:1.0.0".

`docker run -p 5050:8080 -v /Users/myuser/code/myproject/:/src/ myimagename:1.0.0`
Runs Docker image with volume mapped to local folder

`docker kill 123` 
Kills the container with the container ID beginning with 123