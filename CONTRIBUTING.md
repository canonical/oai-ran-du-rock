# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:oai_ran_du_0.1_amd64.rock docker-daemon:oai-ran-du:2.1.1
docker run -d oai-ran-du:2.1.1
```
