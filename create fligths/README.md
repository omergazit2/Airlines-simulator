to simulate new flights to your app follow the next steps:

1) import docker image
```
docker pull omergazi/flight-load:latest
```
2) download config directory and change fileds in appsync_config.py maching your appsync credentials

3) run container mounting the directory
```
docker run -v <path to config diractory>:/config/ flight-load
```
