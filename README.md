# docker-coturn

> A docker image for running the coturn STUN/TURN server, based on `debian:jessie`

## Install

Pull this image with `docker pull masm/coturn`.

## Usage

Run it with `docker run masm/coturn <argument> ...`.
You probably need to at least pass the coturn's `--external-ip` argument.
See coturn docs for available arguments.

## License

Copyright (c) 2015 Marco Monteiro. Released under the MIT license. See `LICENSE` file for details.
