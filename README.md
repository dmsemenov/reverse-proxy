# Nginx reverse proxy
Working example of [nginx-proxy](https://github.com/nginx-proxy/nginx-proxy) with letsencrypt companion for your vds/vps.
### Usage

Add external network `net`:
```console
docker network create net
```
Change params to yours:

`[YOUR_EMAIL]` in `./docker-compose.yml` and `./project.example/docker-compose.yml`

`[YOURDOMAIN.COM]` in `./project.example/docker-compose.yml`

Run proxy and project example:
```console
  docker-compose up -d
```