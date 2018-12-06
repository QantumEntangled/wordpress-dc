# Kong & Konga Docker-Compose

Kong is easiest to use when paired with GUI management interface. This FLOSS pairing works well and can be scaled in an enterprise environment.

*Auto-scaling is WIP and will be added soon.

## Setup

_**Optional**_

Edit the `docker-compose.yml` file to adjust the ports exposed on the host machine by the service.

```Dockerfile
- "8000:8000/tcp"
- "8001:8001/tcp"
- "8443:8443/tcp"
- "8444:8444/tcp"
```

\* _The left number is the host machine port, the right number is the container port, the last part is the packet type allowed to pass._ `host:container/packet_type`

## Starting

To start the service run the following in the `/` root directory.

```Bash
docker-compose up -d
```

## Configuration

Coming Soon

## Intro to Wordpress

For information on how to use [Coming Soon]().
