# Ubuntu + NodeJS base container

This is the base Docker container contains Ubuntu 20.04 and Node.js 16.x.

```
docker buildx build --push --platform linux/arm64,linux/amd64 -t mntu/node-16.13.2:ubuntu-20.04

```
