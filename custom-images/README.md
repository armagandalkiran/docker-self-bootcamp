# Building Custom Images Through Docker Server

Dockerfile: Configuration to define how our container should behave.

Writing a dockerfile == Being given a computer with no OS and being told to install Chrome.

<img width="644" alt="How do you install chrome image" src="https://github.com/armagandalkiran/docker-self-bootcamp/assets/77741597/12ad5d03-afcd-4bd2-a09b-7d7e3654f67f">

## Building a docker file

- docker build . --no-cache --progress=plain

## Steps

<img width="822" alt="Dockerfile steps image" src="https://github.com/armagandalkiran/docker-self-bootcamp/assets/77741597/06a07f52-9efd-43fb-b069-79591b76b26d">

### FROM alpine

- Download alpine image

### RUN apk add --update redis

- Get image from previous step.
- Create a container out of it.
- Run 'apk add --update redis' in it.
- Take snapshot of that container's file system (FS).
- Shut down that temporary container.
- Get image ready for next instruction.

### CMD `["redis-server"]``

- Get image from last step.
- Create a container out of it.
- Tell container it should run 'redis-server' when started.
- Shut down that temporary container.
- Get image ready for next instruction.

No more steps ! Output is the image generated from previous step.


# Building custom image command

- docker build -t armagandalkiran/redis-latest .



