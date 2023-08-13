# Docker Compose

- Seperate CLI that gets installed along with Docker.
- Used to start up multiple Docker containers at the same time.
- Automates some of the long-winded arguments we were passing to 'docker run'.

## Commands

- docker-compose up
- docker-compose up -d
- docker-compose up --build

- docker-compose down
- docker-compose ps

## Restart Policies

- "no": Never attempt to restart this . container if it stops or crashes.
- "always": If this container stops *for any reason* always attempt to restart it.
- "on-failure": Only restart if the container stops with an error code.
- "unless-stopped": Always restart unless we (the developers) forcibly stop it.