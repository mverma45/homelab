Nginx Compose Deployment Lab

- 'docker compose restart' restarts an existing container; it does not rebuild the image.
- 'docker compose up -d --build" builds an updated image and recreates the service when needed.
- '"8082:80" maps Forge host port 8082 to Nginx container port 80.
- Verify deployment with 'docker compose ps', 'curl', container inspection, and logs.
