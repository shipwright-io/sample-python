# sample-python

A collection of Python based sample code.

## Overview

This repository host minimal assets for the Python programming language.

## Structure

This repository consists of multiple directories, each directory is intended to work with a particular set of tools that are currently supported in [Shipwright/Build](https://github.com/shipwright-io/build).

### `/docker-build`

Assets with a Dockerfile, which indicates how to compile the specified source file.
This asset is intended to work with tools like [BuildKit](https://github.com/moby/buildkit), [Kaniko](https://github.com/GoogleContainerTools/kaniko), or [Buildah](https://github.com/containers/buildah).

### `/source-build`

Assets with pure source code, without any knowledge about Docker.
This asset is intended to work with [Buildpacks](https://buildpacks.io/), like the [Paketo](https://paketo.io/) or [Heroku](https://www.heroku.com/) implementation.
