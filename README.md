[![yaktor image](yaktor.png)](http://yaktor.io)


# Docker Base Image

## TL;DR

Don't use this repo directly.  Use https://github.com/SciSpike/docker-yaktor.

## Long Story

This repo produces a Docker image that simply adds dependencies Yaktor has
above and beyond Node.js, which are built into Docker image
https://hub.docker.com/r/scispike/node.  Its existence facilitates developers
of Yaktor itself to create Yaktor containers for local testing.
