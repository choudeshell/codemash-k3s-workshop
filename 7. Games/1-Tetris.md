# Game 1 - Tetris

## Docker
https://hub.docker.com/r/eggplanter/sh-tetris

## Container
eggplanter/sh-tetris

## Overview
Let's play some Tetris! There is a Docker container available at https://hub.docker.com/r/eggplanter/sh-tetris that we should use to play. Unfortunately, it looks like it doesn't work out of the box with Kubernetes. I think there is something we need to override. The Tetris executable is called `tetris` in the container. 
