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
```console
$ cp .env-sample .env
```

Configure `.env` with the values specific to your application

```console
$ docker-compose up -d
```

## Todo

### Add the following services
- [x] Traefik
- [x] Drone
- [x] PostgreSQL
- [ ] MongoDB
- [ ] Redis
