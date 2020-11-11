# nginx-docker

## Configure
Rename `nginx.conf.example` to `nginx.conf`, edit the setting with your own settings.

## Run
```
docker build -t nginx-server .
docker run -it -d --name nginx-server --restart=always --network=host -p 80:80 nginx-server
```
