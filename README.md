#Dockerfile for nginx

Trusted build: [mirkokiefer/nginx](https://index.docker.io/u/mirkokiefer/nginx/).

**Build Dependencies**:
- [mirkokiefer/ubuntu-base](https://github.com/mirkokiefer/dockerfile-ubuntu-base)

The image comes with a simple default config for a static http server.
Just place your files in `data/www`.

You can run the container with:

```
docker run -i -t mirkokiefer/nginx
```
