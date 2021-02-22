# Heimdall
Dashboard for Self-Hosted Services

### Prerequisistes
- Docker
- Docker Compose
- [Docker Image](https://hub.docker.com/r/linuxserver/heimdall)

#### Docker
See [Ubuntu Docs](https://docs.docker.com/engine/install/ubuntu/) or [Debian Docs](https://docs.docker.com/engine/install/debian/)

#### Docker Compose
See [Install Docs](https://docs.docker.com/compose/install/). *If running on Raspberry PI (ARM) install from apt repo*
```
$ sudo apt install docker-compose
```

### Heimdall Docker Configuration
```
$ sudo mkdir /apps/heimdall/
$ sudo chmod -R johnsoga:johnsoga: /apps
$ cd /apps/heimdall
$ git clone https://github.com/johnsoga/heimdall .
```

### Running/Updates
```
$ cd /apps/heimdall
$ XUID=$(id -u $USER) XGID=$(id -g $USER) docker-compose pull
$ XUID=$(id -u $USER) XGID=$(id -g $USER) docker-compose up -d
```
