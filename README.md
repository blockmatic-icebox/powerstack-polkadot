# PowerStack Compose

Docker compose local environment

⚡️ [PowerStack: a powerful fullstack development framework](https://powerstack.xyz).

_Disclaimer: This is a work in progress. Will be finalized soon._
## Usage

1) Clone all services and build their images locally

- powerstack-apollo  
- powerstack-auth   
- powerstack-hasura
- powerstack-auth

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

## Contributing

We use a [Discussions Board](https://github.com/blockmatic/powerstack-docs/discussions/1) to gather thoughts, bug reports and feature requests from the community.

Follow the standard Github Flow for PRs. [Contributing Guidelines](https://docs.powerstack.xyz/powerstack/other-resources/contributing-guidelines).

## Blockmatic

Blockmatic is building a robust ecosystem of people and tools for the development of blockchain applications.

[blockmatic.io](https://blockmatic.io)

<!-- Please don't remove this: Grab your social icons from https://github.com/carlsednaoui/gitsocial -->

<!-- display the social media buttons in your README -->

[![Blockmatic Twitter][1.1]][1]
[![Blockmatic Facebook][2.1]][2]
[![Blockmatic Github][3.1]][3]

<!-- links to social media icons -->
<!-- no need to change these -->

<!-- icons with padding -->

[1.1]: http://i.imgur.com/tXSoThF.png 'twitter icon with padding'
[2.1]: http://i.imgur.com/P3YfQoD.png 'facebook icon with padding'
[3.1]: http://i.imgur.com/0o48UoR.png 'github icon with padding'

<!-- icons without padding -->

[1.2]: http://i.imgur.com/wWzX9uB.png 'twitter icon without padding'
[2.2]: http://i.imgur.com/fep1WsG.png 'facebook icon without padding'
[3.2]: http://i.imgur.com/9I6NRUm.png 'github icon without padding'

<!-- links to your social media accounts -->
<!-- update these accordingly -->

[1]: http://www.twitter.com/blockmatic_io
[2]: http://fb.me/blockmatic.io
[3]: http://www.github.com/blockmatic

<!-- Please don't remove this: Grab your social icons from https://github.com/carlsednaoui/gitsocial -->
