# test-docker


# Docker Commands
To build and run your application using Docker, follow these steps:

# Build the Docker Image:

docker build -t <your-image-name> .
This command builds a Docker image using the Dockerfile in the current directory. Replace <your-image-name> with a meaningful name for your image.

# Run the Docker Container:

docker run -d -p <host-port>:<container-port> --name <your-container-name> <your-image-name>
This command runs a Docker container in detached mode, mapping a host port to a container port. Replace <host-port> with the port on your machine and <container-port> with the port your application is listening on inside the container. <your-container-name> should be replaced with a name for your container.

# Stop the Docker Container:

docker stop <your-container-name>
Stops the running container.

# Remove the Docker Container:

docker rm <your-container-name>
Removes the container after it's been stopped.

# Remove the Docker Image:

docker rmi <your-image-name>
Deletes the Docker image from your local machine.