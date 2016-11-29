# Linux
### CarND Programming Environment - Installation Instructions


## Step 1

First, follow the instructions to install Docker for your Linux distribution from https://docs.docker.com/engine/installation/linux/.

## Step 2

This step ensures Docker is installed properly on your computer.

Launch `Terminal` and type the following at the prompt to download and launch the `hello-world` Docker container (https://hub.docker.com/_/hello-world/):

```
docker run hello-world
```

You should now see the following confirming successful installation: 

```
docker run hello-world
Unable to find image 'hello-world:latest' locally
latest: Pulling from library/hello-world
c04b14da8d14: Pull complete
Digest: sha256:0256e8a36e2070f7bf2d0b0763dbabdd67798512411de4cdcf9431a1feb60fd9
Status: Downloaded newer image for hello-world:latest

Hello from Docker!
This message shows that your installation appears to be working correctly.

To generate this message, Docker took the following steps:
 1. The Docker client contacted the Docker daemon.
 2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
 3. The Docker daemon created a new container from that image which runs the
    executable that produces the output you are currently reading.
 4. The Docker daemon streamed that output to the Docker client, which sent it
    to your terminal.
```

**NOTE**: No need to try something more ambitious. We have bigger fish to fry below. XD