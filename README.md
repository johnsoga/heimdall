# Heimdall
Dashboard for Self-Hosted Services

### Prerequisistes
- Docker
- Docker Compose
- [Docker Image](https://hub.docker.com/r/linuxserver/heimdall)
- [Portainer](https://www.portainer.io/) 

#### Docker
See [Ubuntu Docs](https://docs.docker.com/engine/install/ubuntu/) or [Debian Docs](https://docs.docker.com/engine/install/debian/)

#### Docker Compose
See [Install Docs](https://docs.docker.com/compose/install/).
```
$ sudo apt install docker-compose
```

### Host Configuration
```
$ mkdir /apps/heimdall
$ cd /apps/heimdall
$ git clone https://github.com/johnsoga/heimdall .
```

### Docker Configuration
Managed via [Portainer](https://www.portainer.io/)
