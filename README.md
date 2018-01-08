# DevOps Starter

DevOps toolkit starter pack.

## Features

* Node.js API
* CircleCI
* Docker

## Development

```zsh
$ npm test # run tests

$ npm start # start app locally
```

### Docker

```zsh
$ docker image build -t devops-starter:0.1.0 . # build container image with name and tag

$ docker images # list container images

$ docker container run --name devops-starter -it devops-starter:0.1.0 # run container image

$ docker container ps -a # list all containers
```

### Cleanup

```zsh
$ docker container rm devops-starter # remove container

$ docker image rmi devops-starter:0.1.0 # remove container image

$ docker image rmi node:carbon-alpine# remove container base image
```
