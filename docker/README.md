
# Docker

Things I want to practice are...

### Basics
* What is docker, how it's different from Hypervisor
* Difference between container and image    
* Difference between docker daemon and docker CLI
* What is PID 1
* What is docker.sock file?
* Running docker container
* Interactively connecting to docker
* Attaching interactively to running docker container
* Executing a command in running docker container
* Starting a docker container with different command specified in entrypoint
* Starting a stopped container

### Networking
* How to create network in docker
* Connect two different container with custom network without docker-compose
* Waiting for another docker container using dockerize utility

### Dealing with Docker Image
* How to build custom images
* When to use distroless image
* Instruction types (build / runtime) 
* Multistage build
* Docker registry (artifactory/gcr)
* Where docker images are stored and retrieved
* How to pull / run images from artifactory locally
* Difference between CMD / ENTRYPOINT and when to use which one
* Difference between PUBLISH / EXPOSE

### Debugging Docker Images
* How to look into intermediate docker images
* Issues to deal with alpine images (SSL Certificates)
* Aware of glibc dependencies for go lang

### Volume
* What is volume
* How to mount volumes
* How to copy file into/from container
* Limitation of host volumes
 