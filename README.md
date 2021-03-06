# Plan

![Plan](client/images/logo.png)

Plan is a release management tool suitable for any project based on versionned sub-components. It acts as a gatekeeper 
capable of synchronizing development teams engaged in a delivery process. 

Features:
* projects' time planning: a project is defined basically by a start date, a planned date and a due date
* versions' dependencies: a project can depend on multiple sub-projects. Plan links projects to each other in order to 
  manage versions' dependencies & bottlenecks.
* release management: the tool shows you what are the current statuses of your next software releases

## Pre requisites

* [Docker](https://docs.docker.com)
* [Docker Compose](https://docs.docker.com/compose/)

## Installation

The following steps will build 2 containers with MongoDB and Plan.

### Development

```shell
$ docker-compose up
```

From here, the application is available at the following URL: `http://localhost:3700`.

## License

This project is released under the [MIT license](LICENSE).
