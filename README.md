# Ubuntu + NodeJS base container

This is the base Docker container contains Ubuntu 22.04 and Node.js 18.x.

```
docker buildx build . --push --platform linux/arm64,linux/amd64 -t mntu/node:18.16.1-ubuntu-22.04

```
