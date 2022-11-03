# Ansible Role FreeTube
This is an Ansible role that installs FreeTube on Linux. It can use the RPM, Deb or Flatpak package.  

Tested on Fedora 36 and Ubuntu 20.04, should work on any Linux distribution that the FreeTube packages or Flatpak package installs.  

## Requirements

### Base requirements
None  

## Variables
| Variable | Default | Description |
|----------|---------|-------------|
| `freetube_version` | `0.18.0` | Version of FreeTube to install. |
| `freetube_release_channel` | `beta` | Release channel for FreeTube. The only one that exists right now is `beta`. |
| `freetube_package_format` | `rpm` for RedHat, `deb` for Debian, falls back to `flatpak` | How to install the package. To use `flatpak` you need `flatpak` installed. |
