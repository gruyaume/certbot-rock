# Contributing


## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:certbot_1.6.0_amd64.rock docker-daemon:certbot:1.6
docker run certbot:1.6
```
