# Ory Hydra/Kratos Example Projects

This repository contains experimental projects. Do not use these configs and .env files on production.

I personally prefer [Postgresql](https://www.postgresql.org/) as RDBMS database. You will see all examples with Postgresql. If you want to reach databases you can use [DBeaver](https://dbeaver.io/), it's cross platform and open source advanced DB client.

## Containers

- [oryd/hydra](https://hub.docker.com/r/oryd/hydra/): OAuth 2.0 and OpenID Connect server
- [oryd/kratos](https://hub.docker.com/r/oryd/kratos/): User management server
- [oryd/mailslurper](https://hub.docker.com/r/oryd/mailslurper/tags): Simple SMTP mail server (use only for testing)

## Before the start

- [Install Docker](https://docs.docker.com/get-docker/)
- Watch the [5 min tutorial](https://www.ory.sh/docs/hydra/5min-tutorial)

## Terms

- DSN: Data Source Name (*see [more](https://www.ory.sh/docs/self-hosted/deployment) details*)
- [postgresql connection string](https://stackoverflow.com/a/20722229/6940144)