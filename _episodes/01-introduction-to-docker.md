---
title: "Introduction to Docker"
teaching: 20
exercises: 0
questions:
- "What is Docker?" 
- "Why should I use containers as part of my reseach workflow?"
- "What is a container image?"
- "What is a container?"
- "What is a container registry and why should I use a registry as part of my research workflow?"
objectives:
- "Explain how containers can be used to enhance portability and reproducibility of research workflows."
- "Explain the difference between a container image and a container."
- "Explain how a container differs from a virtual machine."
- "Understand how container registries, such as DockerHub, can be used to automate research workflows."
keypoints:
- "Docker is a platform for developing, deplying, and running applications inside containers."
- "Containers help improve the portability, reproducibility, and scalability of software engineering and data science workflows."
- "A container image is a 'blueprint' that is used to create standardized units of software called containers."
- "Publishing your container image to a container registry allows other researchers to create containers from your image and reproduce your results or to build upon your image in order to extend your results."
---

## What is Docker?
Docker is a platform for developing, deploying, and running applications inside standardized units of software called containers. Containers help improve security, reproducibility, and scalability of software development and data science workflows.

## Motivating examples using Jupyter-Stacks and Rocker
Objective is to show learners how I use Docker as part of my develoment workflow to produce reproducible data science pipelines.

{% include links.md %}

