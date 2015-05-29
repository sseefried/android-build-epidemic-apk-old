# Scripts to build Epidemic for Android

## Introduction

[Epidemic](https://github.com/sseefried/open-epidemic-game) is a game written for mobile
devices in Haskell. 

This repo contains a script called `build-epidemic-apk.sh` to build the game for Android
devices using ARMv7 (or compatible) chipsets. The repo contains a thin Java wrapper that
calls into the natively compiled code of the game.

## Setting up a development environment

This won't just work out of the box. You will require a GHC cross compiler targetting
ARMv7 and will need to build all the associated libraries. This isn't straightforward at all!

However, I've done all the work for you using Docker. Please see the repo [`docker-epidemic-build-env`](https://github.com/sseefried/docker-epidemic-build-env.git) for more details.