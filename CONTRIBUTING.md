# Contributing


## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:certbot_0.27.0_amd64.rock docker-daemon:certbot:0.27.0
docker run certbot:0.27.0
```
