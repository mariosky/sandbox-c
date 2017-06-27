## sandbox-go

A docker container based on alpine (golang:alpine) for running experiments in sandbox.

It includes:

* go
* sandbox worker

## Working with this container

Build
`docker build -t mariosky/sandbox-go sandbox-go/`

Run Interactively
`docker run -t -i mariosky/sandbox-go /bin/sh`
