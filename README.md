# docker-gotify
Docker image to run a Gotify server behind a Traefik reverse-proxy

## Setup
1. Input your domain name in `.env`
1. Input your choice of admin password in `secrets/ADMIN_PASSWORD.secret`
1. Make sure that Docker network `traefik` exists, `docker network ls`
1. Run `docker-compose up`and check logs