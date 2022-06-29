# Bitcash Compose

Bitcash's docker compose development environment

## Learn

https://learn.blockmatic.io/devops/

## Usage

1) Clone all services and build their images locally

- bitcash-apollo  
- bitcash-auth-old   
- bitcash-hasura
- bitcash-auth

2) Run `task boot`

## Dependencies

You need the following global dependencies on your host machine.

- docker https://docs.docker.com/get-docker/
- docker compose https://docs.docker.com/compose/
- task manager https://taskfile.dev/#/installation
- hasura cli https://hasura.io/docs/latest/graphql/core/hasura-cli/index.html   
  ` yarn global add hasura-cli@2.3.0-beta.1`

We use http://taskfile.dev to manage some comon task.  .  
Make sure you create a `.env` file so docker compose can read your environment vars.

## Useful Commands

```
- `docker-compose build` build all containers,
- `docker-compose up` starts all containers.
- `docker-compose up --build` rebuilds and starts all containers.
- `docker-compose exec [service_name] [bash | sh]` open bash or sh in a container.
- `docker-compose stop` stops all containers.
- `docker-compose down` stops and removes all containers.
- `docker-compose restart` restarts all services.
```
