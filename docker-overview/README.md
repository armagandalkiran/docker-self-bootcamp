# Why use Docker ?

Docker makes it really easy to install and run software without worrying about setup or dependencies.

<img width="519" alt="Why use Docker image alt" src="https://github.com/armagandalkiran/docker-self-bootcamp/assets/77741597/5aaf8ddf-908d-4cb6-9f08-dcba76a3f44e">

# What is Docker ?

## Docker Ecosystem

- Docker Client
- Docker Server
- Docker Machine
- Docker Images
- Docker Hub
- Docker Compose

So, Docker is a platform or ecosystem around creating and running containers.

Image: Single file with all the deps and config required to run a program.

Container: Instance of an image. Runs a program. Container is a program with it's own isolated set of hardware resources. ( memory, network tech, hard drive )

## Docker Client

<img width="1198" alt="Docker client title image" src="https://github.com/armagandalkiran/docker-self-bootcamp/assets/77741597/6561e212-eca8-47e0-88e6-c0d13e2cc57b">

# What is a container ? ( in detail )

<img width="452" alt="What is a container image-1" src="https://github.com/armagandalkiran/docker-self-bootcamp/assets/77741597/482b351e-f3c8-497a-987e-0b9f209079ea">

<img width="688" alt="What is a container image-2" src="https://github.com/armagandalkiran/docker-self-bootcamp/assets/77741597/1b1fca23-cd67-4f58-9967-ad7c3c5b076c">

<img width="663" alt="What is a container image-3" src="https://github.com/armagandalkiran/docker-self-bootcamp/assets/77741597/45c4ecbd-21d1-4b57-b348-183ac85f7461">

<img width="739" alt="What is a container image-4" src="https://github.com/armagandalkiran/docker-self-bootcamp/assets/77741597/b731d629-74d0-4007-ba55-a088b948b533">

Namespacing: Isolating resources per process (or group of processes)

(Processes, Hard drive, Network, Users, Hostnames, Inter Process Communication)

Control Groups (cgroups): Limit amount of resources used per process.

(Memory, CPU Usage, HD I/O, Network Bandwith)

# Image and Container relation

<img width="739" alt="Image and Container relation" src="https://github.com/armagandalkiran/docker-self-bootcamp/assets/77741597/352026dc-5856-4aa3-8cfc-f23b24795530">

# How is Docker running on computer ?

<img width="558" alt="How is Docker running on computer image" src="https://github.com/armagandalkiran/docker-self-bootcamp/assets/77741597/5da6f426-6020-4830-9b5f-8128519e5e8e">
