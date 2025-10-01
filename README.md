# my-docker-web
Simple static site served by nginx in Docker.

Run locally:
  docker-compose up --build

Server (pull from GHCR):
  docker login ghcr.io -u bis-a11y -p <PAT>
  docker-compose pull
  docker-compose up -d
