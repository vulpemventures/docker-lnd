# Docker LND

Dockerfile of the public image [ghcr.io/vulpemventures/lnd:latest](https://github.com/vulpemventures/docker-lnd/pkgs/container/lnd)

Based on the Dockerfile in the `lnd` repo: [https://github.com/lightningnetwork/lnd/blob/master/docker/lnd/Dockerfile](https://github.com/lightningnetwork/lnd/blob/master/docker/lnd/Dockerfile)

Pull the image:

```bash
$ docker pull ghcr.io/vulpemventures/lnd
```

Run the container:

```bash
$ docker run -p 9735:9735 -p 10009:10009 -d ghcr.io/vulpemventures/lnd <lnd options>
```