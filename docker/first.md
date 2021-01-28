### Let's get our hand wet by trying out the docker for the very first time


![Brace Yourself!](https://images.app.goo.gl/vXMbtw4HHgS3emXSA)

- Run `$ docker run hello world`
  <br/>Carefully look at the sequence of commands executed
  ```
  _$ docker run hello-world
    Unable to find image 'hello-world:latest' locally
    latest: Pulling from library/hello-world
    0e03bdcc26d7: Pull complete
    Digest: sha256:31b9c7d48790f0d8c50ab433d9c3b7e17666d6993084c002c2ff1ca09b96391d
    Status: Downloaded newer image for hello-world:latest
    
    Hello from Docker!
    This message shows that your installation appears to be working correctly.
    
    To generate this message, Docker took the following steps:
    1. The Docker client contacted the Docker daemon.
    2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
       (amd64)
    3. The Docker daemon created a new container from that image which runs the
       executable that produces the output you are currently reading.
    4. The Docker daemon streamed that output to the Docker client, which sent it
       to your terminal.
    
    To try something more ambitious, you can run an Ubuntu container with:
    $ docker run -it ubuntu bash
    
    Share images, automate workflows, and more with a free Docker ID:
    https://hub.docker.com/
    
    For more examples and ideas, visit:
    https://docs.docker.com/get-started/
  ```
  
    1. `$ docker run hello-world` ran on Docker-Client which is accessible using docker cli and through terminal 
    2. Docker Client Internally Called the Docker Serer to run the `hellw-world` command 
    3. Docker Server Checks if there is a local copy of hello world in the Image cache of your system.
    4. Docker Server was Unable to find a local copy of a hello-world image in the cache
    5. Docker Server pulls the image from docker registry, a.k.a. Docker Hub, free registry of opensource images.
    6. Docker Server caches the image downloaded from Docker Hub and stores it into the cache.
    7. Docker Server Runs the Image which results in the following output.