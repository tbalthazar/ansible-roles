# Traefik Role

## Remarks

The Traefik Dashboard is only exposed on `127.0.0.1:8080`, and the port is not open to the outside world.  
To access the Dasbhoard, create a SSH tunnel from your local computer:
```
$ ssh -NTL 2000:127.0.0.1:8080 user@traefik-server
$ curl localhost:2000 # you should see the Dashboard now
```

## Config Vars

- traefik_docker_image_tag
- traefik_log_level
- traefik_le_env
- hostname