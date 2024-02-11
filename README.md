# FrankenPHP Add-On for DDEV

This DDEV add-on for FrankenPHP replaces the currently used webserver
with [FrankenPHP](https://frankenphp.dev/).

FrankenPHP is a modern PHP App Server, written in Go.

## Why?

The WHY!

## Installation

```bash
ddev get b13/ddev-frankenphp && ddev restart
```

## Configuration

[config.yaml](frankenphp%2Fconfig.yaml)

`SERVER_NAME` will be set depending on the VIRTUAL_HOST used by ddev.
This way all domains configured by ddev will be used by frankenphp as well.

`MERCURE_PUBLIC_URL` will use the `DDEV_PRIMARY_URL` (`$DDEV_PRIMARY_URL/.well-known/mercure`)



**Maintained by [@b13](https://github.com/b13)**
