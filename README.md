# docker-compose-mtproxy
Deploy Telegram MTProto proxy with ease. Original work by iShift: https://github.com/iShift/docker-compose-mtproxy, Forked & improved so it works.

# Requirements
* Docker
* docker-compose

# Usage
```
$ git clone https://github.com/iShift/docker-compose-mtproxy.git
$ cd docker-compose-mtproxy
```

Edit `config.env` first if you wish to change default settings. The proxy will work in default settings, so if you don't have any special needs you won't need to modify it.

By default, proxy listens on port **943**. If you wish to change - edit *docker-compose.yml*:
- "**943**:443" 

When you're done, run:

```
$ docker-compose up -d
```

## Get logs and connection info
```
$ docker-compose logs
```

## Stop the proxy
```
$ docker-compose down
```

# Links
Original work by iShift: https://github.com/iShift/docker-compose-mtproxy
telegrammessenger/proxy @ Docker Hub: https://hub.docker.com/r/telegrammessenger/proxy/
MTProxy: https://github.com/TelegramMessenger/MTProxy
