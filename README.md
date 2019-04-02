# Personal Server Bundle
Collection of services used to run my homepage and other projects.

## Services
| Name | Description |
| --- | --- |
| Traefik | Reverse proxy and load balancer with easy support for containers. |
| Drone | Continious integration and deployment service. |
| PostgreSQL | Reliable and efficient relation database. |

## Requirements
* Docker 18.06
* Docker Compose 1.18

## Instructions

### Setup
```console
$ touch acme.json
$ cp .env-sample .env
```

Configure `.env` with the values specific to your application

### Running
```console
$ docker-compose up -d
```

## Todo
- [x] add Traefik
- [x] setup Traefik to redirect http to https
- [ ] setup Traefik to automatically handle ssl and ssl renewals
- [x] add Drone
- [ ] setup Drone to use PostgreSQL instead of SQLite
- [ ] setup Drone to automatically deploy my homepage and other projects
- [x] add PostgreSQL
- [ ] setup PostgreSQL to automatically add multiple databases and users respectively
- [ ] setup web UI for managing PostgreSQL
- [ ] add MongoDB
- [ ] setup web UI for managing MongoDB
- [ ] add Redis
