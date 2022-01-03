# Jay's Home Assistant Add-ons

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)


## About

My Home Assistant repository provides you a way to add additional capabilites
to your Home Assistant installation by adding add-ons that provide additional
functionality.

This is only 1 such example of a Home Assistant repository and there are many
others including the [Home Assistant Community Add-ons][repositoryCommunity] project.

## Installation

This add-on isn't included in Home Assistant by default and needs to be added from a GitHub repository. Don't worry - the process isn't too hard!

1. Within Home Assistant, navigate to **Configuration** > ** Add-ons, Backups & Supervisor** 
1. Click **ADD-ON STORE** > **Menu** (3 dot elipsis, top right) > **Repositories**
1. Add the following Repository

```txt
https://github.com/Jays-Home-Assistant-Add-ons/repository
```

## Add-ons provided by this repository

### &#10003; [InfluxDB2][influxdb2-addon]

![Latest Version][influxdb2-releases-shield]
![Supports amd64 Architecture][influxdb2-amd64-shield]
![Supports aarch64 Architecture][influxdb2-aarch64-shield]
![Supports armhf Architecture][influxdb2-armhf-shield]
![Supports armv7 Architecture][influxdb2-armv7-shield]
![Supports i386 Architecture][influxdb2-i386-shield]

![HA Ingress Support][influxdb2-ingressSupport]
![Local Build][influxdb2-local-build]

InfluxDB is an open source time series database optimized for high-write-volume.
It's useful for recording metrics, sensor data, events,
and performing analytics. It exposes an HTTP API for client interaction and is
often used in combination with Grafana to visualize the data.

InfluxDB v2.x \
If you're after InfluxDB v1.x [see here][influxdbv1]

[:books: InfluxDB2 add-on documentation][influxdb2-doc]



[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2022.svg
[license-shield]: https://img.shields.io/github/license/Jays-Home-Assistant-Add-ons/repository.svg
[influxdbv1]: https://github.com/hassio-addons/addon-influxdb
[repositoryCommunity]: https://github.com/hassio-addons/repository

[comment]: <> (-- INFLUXDB2 --)
[influxdb2-releases-shield]: https://img.shields.io/github/release/Jays-Home-Assistant-Add-ons/j-addon-influxdb2.svg
[influxdb2-local-build]: https://img.shields.io/badge/Home%20Assistant%20--%20local%20build-YES-orange.svg
[influxdb2-ingressSupport]: https://img.shields.io/badge/Home%20Assistant%20--%20ingress%20support-NO-red
[influxdb2-aarch64-shield]: https://img.shields.io/badge/aarch64-untested-orange.svg
[influxdb2-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[influxdb2-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[influxdb2-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[influxdb2-i386-shield]: https://img.shields.io/badge/i386-no-red.svg

[influxdb2-doc]: https://github.com/Jays-Home-Assistant-Add-ons/j-addon-influxdb2/blob/main/README.md
[influxdb2-addon]: https://github.com/Jays-Home-Assistant-Add-ons/j-addon-influxdb2
