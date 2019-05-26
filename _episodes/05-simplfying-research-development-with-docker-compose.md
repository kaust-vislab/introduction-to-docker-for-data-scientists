---
title: "Simplifying Research Development with Docker Compose"
teaching: 25
exercises: 15
questions:
- "What is Docker Compose?"
- "How can I use Docker Compose to simplify my research development workflow?"
objectives:
- "Understand the command 'docker-compose up'."
- "Write you own docker-compose.yml file."
keypoints:
- "Compose is a tool for defining and running Docker applications."
- "With Compose you use a single YAML file to configure your research project as a Docker application and then a single command,`docker-compose up`, to create the container and start your application."
---

## What is Docker Compose

Compose is a tool for defining and running Docker applications. With Compose, you use a YAML file to configure the various pieces of your application’s services. Then, with a single command, you create and start all the services from your configuration.

Docker Compose is a tool that makes it easier to run apps that require multiple Docker containers. Docker Compose allows you to move commands into a docker-compose.yml file for reuse. The Docker Compose command line interface (cli) makes it easier to interact with your multi-container app. Docker Compose comes free with your installation of Docker.

## Image Registries (DockerHub)

## Volumes
From [Medium][introduction-to-containers-and-vms]
Volumes are the “data” part of a container, initialized when a container is created. Volumes allow you to persist and share a container’s data. Data volumes are separate from the default Union File System and exist as normal directories and files on the host filesystem. So, even if you destroy, update, or rebuild your container, the data volumes will remain untouched. When you want to update a volume, you make changes to it directly. (As an added bonus, data volumes can be shared and reused among multiple containers, which is pretty neat.)


## Networks


[introduction-to-containers-and-vms]: https://medium.freecodecamp.org/a-beginner-friendly-introduction-to-containers-vms-and-docker-79a9e3e119b

