# Microservices Architecture
![](img/microservicesarchitecturediagram.png)

![](img/clientdockerhostregistry.svg)

- [Microservices Architecture](#microservices-architecture)
  - [What is containerisation](#what-is-containerisation)
- [Docker](#docker)
  - [What is Docker?](#what-is-docker)
- [Benefits](#benefits)
  - [Docker Installation](#docker-installation)
    - [Requirements](#requirements)
    - [Installation](#installation)
    - [To Check Installation](#to-check-installation)
    - [Create an account](#create-an-account)

## What is containerisation
- Packaging services together in a container
# Docker
![](img/dockericon.png)
## What is Docker?
- Open source
- PaaS (platform as a service)
- Containerisation platform

# Benefits
- Faster than VMs
- Light-weight
- User-friendly
- Isolates 
- Uses fewer resources


## Docker Installation
https://docs.docker.com/desktop/windows/install/

### Requirements
- WSL 2 backend

### Installation
- Go to above link
- Click `Download Docker Desktop for Windows`
- Once downloaded, click the exe file to run the installer
- Select the Install Required components for WSL 2 option
- Go through the installation instructions
- At the end, it should ask to restart your computer

### To Check Installation
In the terminal:
- `docker`

![](img/dockercommand.png)

- `docker version`

![](img/dockerversion.png)

### Create an account
- Create an account on DockerHub
https://hub.docker.com/account/confirm-email/42542e657ad9500c9b1e616ca4abe8d23c975b87/
- Sign in on Docker Desktop


In terminal:
- `docker pull hello-world`
- `docker images`
- `docker run hello-world`

![](img/DockerRunHelloWorld.png)
