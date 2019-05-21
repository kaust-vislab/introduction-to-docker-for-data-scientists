---
title: "Running Docker Containers"
teaching: 25
exercises: 15
questions:
- "Where do Docker images come from?"
- "How do I run a Docker container based on a Docker image?"
- "How do I access a running Docker container?"
- "How do I make my research project files accessible inside a Docker container?"
- "How do a delete a Docker container when I no longer need it?"
objectives:
- "Pull a Docker image from DockerHub."
- "Run a Docker container based on a Docker image."
- "Access an interactive shell inside a running Docker container."
- "Mount a directory on your local machine into a Docker container."
- "Delete a Docker container when it is no longer needed."
keypoints:
- "Existing Docker images can be pulled from container registries such as DockerHub."
- "To run a Docker container based on a Docker image use the `docker container run` command."
- "???"
- "Mount a directory on the host into a container by passing the `--volume` option to the `docker container run` command."
- "Pass the `--rm` flag when using the `docker container run` command to automatically remove the container when it exits."
---