# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo rockcraft.skopeo --insecure-policy copy oci-archive:oai-ran-du_2.2.0_amd64.rock docker-daemon:oai-ran-du:2.2.0
docker run -d oai-ran-du:2.2.0
```
