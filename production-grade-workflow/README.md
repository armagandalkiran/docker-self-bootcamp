# Docker Volumes

Helps to prevent rebuild all the time when there is a change.

- docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app <"image_id">
