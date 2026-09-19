# Docker Task - 2

## Objective

Create a Dockerfile and Docker Compose file to deploy a website displaying basic details.

## Technologies Used

- Docker
- Docker Compose
- Nginx
- Linux
- AWS EC2

## Project Files

- `Dockerfile` - Builds the Nginx Docker image.
- `docker-compose.yml` - Builds and runs the web container.
- `index.html` - Website containing basic details.
- `screenshots/` - Screenshots demonstrating the Docker deployment and website.

## Docker Deployment

The application is deployed using Docker Compose.

The container exposes port 80 and maps it to port 80 on the EC2 host.

## Verification

The application was verified using:

```bash
docker compose ps
docker port docker-task-2-web
curl http://localhost
