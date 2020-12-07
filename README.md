# Local Server Profiles

Docker-compose examples using opt/in to pass in product configurations

## Clone the pingidentity-server-profiles repository

```sh
cd ${HOME}
mkdir -p projects/devops/
cd projects/devops/
git clone \ https://github.com/pingidentity/pingidentity-server-profiles.git
```

## Clone the docker-compose files

```sh
git clone \ https://github.com/gmorgan-ping/local-server-profiles.git
```

## Launch example(s)

```sh
cd local-server-profiles/00-standalone/pingfederate
docker-compose up -d
```

## Clean up

```sh
docker-compose down
```
