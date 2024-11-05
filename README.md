# Docker Compose Files

A set of YAML files to create stacks of Docker containers using Docker Compose or Portainer.

## Create stacks via command line

```
git clone https://github.com/fullmetalbrackets/docker.git
cd docker
docker compose -f <filename>.yaml up -d
```

## Create through Portainer

1. Login to Portainer, choose environment and go to *Stacks* ->  *Add new stack*
2. Copy and paste contents of a YAML file into the *Web editor* and click *Deploy the stack*.
