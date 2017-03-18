# PHP (SCL) S2I Docker images

[![Build Status](https://travis-ci.org/ausnimbus/s2i-php-scl.svg?branch=master)](https://travis-ci.org/ausnimbus/s2i-php-scl)

This repository contains the source for building various versions of
the PHP application as a reproducible Docker image
[source-to-image](https://github.com/openshift/source-to-image)
to be run on [AusNimbus](https://www.ausnimbus.com.au/).

Images are built with PHP RPM packages from SCL.
The resulting image can be run using [Docker](http://docker.io).

## Versions

The versions currently supported are:

- 5.5 (deprecated)
- 5.6
- 7.0
