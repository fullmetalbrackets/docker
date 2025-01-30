# Docker Compose Files

A set of YAML files to create stacks of Docker containers using Docker Compose or Portainer.

> ⚠ Be sure to edit the YAML files and change local directories (e.g. `/opt/docker` and `/mnt/storage`, etc.) to the path of your own local data before running!

## Create stacks via command line

```
git clone https://github.com/fullmetalbrackets/docker.git
cd docker
docker compose -f <filename>.yaml up -d
```

## Create through Portainer

1. Login to Portainer, choose environment and go to *Stacks* ->  *Add new stack*
2. Copy and paste contents of a YAML file into the *Web editor* and click *Deploy the stack*.
