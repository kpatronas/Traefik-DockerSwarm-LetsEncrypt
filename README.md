# Traefik - Docker Swarm - LetsEncrypt
## What it does
This yaml file is intented for docker swarm, it creates a Traefik proxy/Load Balancer with a simple "hello world" container as a service, Traefik also automatically creates an Lets Encrypt SSL certificate for the configured domain of the service
## Instructions
* replace admin@domain.com and helloworld.domain.com with the values of your domain
* replace the helloworld section with the container you want to use

