# Concourse CI

First of all, you need to create this file below

```bash
CONCOURSE_VERSION=3.13.0
CONCOURSE_USER=
CONCOURSE_PASS=
POSTGRES_PASS=
```

You need to generate [key](https://github.com/concourse/concourse-docker/blob/master/generate-keys.sh) for concourse


After that, you can launch docker-compose

```bash
docker-compose up -d
```

Concourse register on traefik, if you deploy [it](https://github.com/azouz34200/home-proxy)