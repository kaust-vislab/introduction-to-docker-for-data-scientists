---
title: "Enough Docker to be Useful"
teaching: 25
exercises: 10
questions:
- "What is repo2docker?"
- "How does repo2docker use Docker?" 
- "How can I build, run, and push Docker images from source code repositories?"
objectives:
- "Build a Docker image for your source code repository using repo2docker."
- "Configure the user interface for the resulting Docker image."
- "Push the resulting Docker image to a cloud container registry."
- "Run a Docker container on your local machine using the image built using repo2docker."
keypoints:
- "repo2docker takes a source repository and builds a container image based on the configuration files found in the repository."
- "repo2docker can build an image based on repositories on your local machine or in the cloud (GitHub, GitLab, etc)."
- "repo2docker is the tool used by [BinderHub](https://binderhub.readthedocs.io/) to build images on demand."
---
## Motivation

[Docker...without the hassle!](https://towardsdatascience.com/docker-without-the-hassle-b98447caedd8)

## Installing repo2docker

## Using repo2docker

## Configuring the User Interface

## Choosing Languages for Your Environment

### Python

### R

## Sharing JupyterLab Workspaces With a Repository

## Building JupyterHub Ready Images

## Continuous Integration and repo2docker