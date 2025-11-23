# DHCP Kea Template

This repository provides a Dockerized setup for the Kea DHCPv4 server. It is designed to be a simple starting point for running a DHCP server using Docker Compose.

## Getting Started

To start the DHCP server, run the following command:

```bash
docker compose up -d
```

This will build the image and start the service in `host` network mode.

## Config

The main configuration file is `kea-dhcp4.conf`. This file is mounted into the container at runtime.

If you want to customize the DHCP server settings (e.g., subnets, pools, options), edit `kea-dhcp4.conf`.

A default configuration file `kea-dhcp4.conf.default` is also provided for reference.
