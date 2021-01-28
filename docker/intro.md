## What is Docker?

In their own words "Developing apps today requires so much more than writing code. Multiple languages, frameworks, architectures, and discontinuous interfaces between tools for each lifecycle stage creates enormous complexity. Docker simplifies and accelerates your workflow, while giving developers the freedom to innovate with their choice of tools, application stacks, and deployment environments for each project."

## Why use Docker?

Some of the key Aspects of Docker:
- Easy to install
- Ease of managing the dependencies for a project.
- Ease of setting up you code on a new Machine / Friend's Machine :p

### Docker Ecosystem

- [Docker Client](https://docs.docker.com/get-started/overview/#:~:text=Docker%20uses%20a%20client%2Dserver,to%20a%20remote%20Docker%20daemon.)
- Docker Server
- Docker Machine
- Docker Hub
- Docker Compose
- Docker Images

Docker is a platform or ecosystem around creating and running applications in containers.

### Let's get our Hands dirty with elbow grease

#### Setting up your Docker
1. [Sign up for a Docker Hub Account](https://hub.docker.com/)
2. [Docker Client for Windows/Mac](https://www.docker.com/products/docker-desktop)
3. Login to the Docker Client installed on your machine.
4. Verify docker installation, by running `$ docker version` in the terminal/power shell. Your output should look something similar to this 
    ```javascript
    _$ docker version
    Client: Docker Engine - Community
    Cloud integration: 1.0.7
    Version:           20.10.2
    API version:       1.41
    Go version:        go1.13.15
    Git commit:        2291f61
    Built:             Mon Dec 28 16:12:42 2020
    OS/Arch:           darwin/amd64
    Context:           default
    Experimental:      true
    
    Server: Docker Engine - Community
    Engine:
    Version:          20.10.2
    API version:      1.41 (minimum version 1.12)
    Go version:       go1.13.15
    Git commit:       8891c58
    Built:            Mon Dec 28 16:15:28 2020
    OS/Arch:          linux/amd64
    Experimental:     false
    containerd:
    Version:          1.4.3
    GitCommit:        269548fa27e0089a8b8278fc4fc781d7f65a939b
    runc:
    Version:          1.0.0-rc92
    GitCommit:        ff819c7e9184c13b7c2607fe6c30ae19403a7aff
    docker-init:
    Version:          0.19.0
    GitCommit:        de40ad0
    ```




References: [Official Page](https://www.docker.com/why-docker) [Udemy Course](https://www.udemy.com/course/docker-and-kubernetes-the-complete-guide/)