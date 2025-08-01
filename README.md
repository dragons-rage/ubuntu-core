# Ubuntu Core

## Platforms

- x86_64/amd64 **(Tested on Ubuntu 20.04 LTS - Docker 20.10.21)**
- arm64/aarch64 **(Tested on Apple Silicon M1 Docker Desktop)**

Testing will be conducted on Mac OS X and Ubuntu 22.04 LTS and Raspberry Pi 4
docker instances. RPi4 is a 64-bit ARMv8 CPU and arm64 should be supported. I
have not tested this yet.

## Note / Disclaimer

This isn't the best method to run multiple services. For kubernetes you create
a manifest with multiple containers in the same pod or multiple services. For
docker, it is best to use a docker-compose file to handle multiple
containers/services at once.

I made this as something I thought was a good idea when I didn't know better.
I might even archive soon.

## Description

Base ubuntu-core with customizations for building and running containers.
Ideally this will track the latest LTS release of Ubuntu docker upstream,
but for now I will manually update this as needed.

## Upstream Links

This section has links to used components of core. So we can update versions easier.

- [S6 Overlay](https://github.com/just-containers/s6-overlay)
