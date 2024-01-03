# Ubuntu + NodeJS base container

This is the base Docker container contains Ubuntu 22.04 and Node.js 20.x.

```
docker buildx build . --push --platform linux/arm64,linux/amd64 -t mntu/node:20.10.0-ubuntu-22.04

```
