[![Yaktor](http://docs.yaktor.io/images/logo-with-text.png)](http://yaktor.io)

> NOTE: THIS REPO IS DEPRECATED.
It is no longer needed or maintained.
It has been superceded by Docker image https://hub.docker.com/r/yaktor/node/ at GitHub repo https://github.com/SciSpike/docker-yaktor-node.
Please do not use this image; it will be removed in the future.

# Docker Base Image

* Provides a base docker image for [yaktor/yaktor](https://hub.docker.com/r/yaktor/yaktor)
* Validates [yaktor](https://github.com/SciSpike/yaktor) via `./run.sh npm test`

## TL;DR

Don't use images from this repo directly.
Use https://hub.docker.com/r/yaktor/yaktor instead.

## Long Story

This repo houses images that contain all Yaktor dependencies.  These base
images make it possible for developers of Yaktor itself to create Yaktor
containers for local testing.
