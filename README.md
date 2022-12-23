[![Build Status](https://app.travis-ci.com/vlmaier/docker-fib.svg?branch=master)](https://app.travis-ci.com/vlmaier/docker-fib)

# docker-fib

This repository was created in order to practice Docker deployment using multiple containers. I followed the Udemy course by Stephen Grider: [Docker and Kubernetes: The Complete Guide](https://www.udemy.com/docker-and-kubernetes-the-complete-guide).
The application itself calculates fibonacci numbers. To determine and send the fibonacci number for a specific index, it uses the following services:

- Postgres
- Redis
- Nginx
- Node Server
- Node Client
- React UI

It is deployed using Travis CI & Docker Hub.
