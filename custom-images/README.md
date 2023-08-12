# Building Custom Images Through Docker Server

Dockerfile: Configuration to define how our container should behave.

Writing a dockerfile == Being given a computer with no OS and being told to install Chrome.

## Building a docker file

- docker build . --no-cache --progress=plain

## Steps

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



