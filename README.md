# FrankenPHP Add-On for DDEV

This DDEV add-on for FrankenPHP replaces the currently used webserver
with [FrankenPHP](https://frankenphp.dev/).

FrankenPHP is a modern PHP App Server, written in Go.

## Why?

The WHY!

## Installation

For DDEV v1.23.5 or above run

```sh
ddev add-on get ochorocho/ddev-frankenphp && ddev restart
```

For earlier versions of DDEV run

```sh
ddev get ochorocho/ddev-frankenphp && ddev restart
```

## Configuration

[config.yaml](frankenphp%2Fconfig.yaml)

`SERVER_NAME` will be set depending on the VIRTUAL_HOST used by ddev.
This way all domains configured by ddev will be used by frankenphp as well.

`MERCURE_PUBLIC_URL` will use the `DDEV_PRIMARY_URL` (`$DDEV_PRIMARY_URL/.well-known/mercure`)
