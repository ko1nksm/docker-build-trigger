# docker-build-trigger
Trigger your Docker hub Automated Build

## Usage

```
Usage: docker-build-trigger [Trigger URL]
  Trigger all for this automated build.

Usage: docker-build-trigger DOCKER_TAG [TRIGGER_URL]
  Trigger by docker tag name

Usage: docker-build-trigger [ branch | tag ] SOURCE_NAME [TRIGGER_URL]
  Trigger by source branch/tag name


Environment variables:
  DOCKER_BUILD_TRIGGER_URL    Use as TRIGGER_URL when not specified by argument.
```

## Installation

```console
$ curl -sSfL https://raw.githubusercontent.com/ko1nksm/docker-build-trigger/master/docker-build-trigger | install /dev/stdin ~/bin/docker-build-trigger
```
