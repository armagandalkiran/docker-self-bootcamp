# Manipulating containers with docker commands

- docker ps -> shows all running containers.
- docker ps --all -> shows all created containers.

- docker create <"image"> -> creates a container and returns container Id.
- docker start <"containerId"> -> starts container but do not return info.
- docker start -a <"containerId"> -> attach to container and returns information by watching output of container. ( you can restart a exited container as well with this command)

- docker run <"image"> -> combines docker create and docker start -a.

- docker system prune -> clears all containers from disk.

- docker logs <"containerId"> -> logs container output if started before.

- docker stop <"containerId"> -> allows some time ( 10 seconds ) to prepare and clean up. If 10 seconds up it's fallback to docker kill. ( signals )

- docker kill <"containerId"> -> instantly terminates the running container.

- docker exec -it <"containerId"> <"another_command"> -> allows to use multiple commands in one container.

- docker exec -it <"containerId"> sh -> opens command processor.
