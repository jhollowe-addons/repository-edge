# EDGE - jhollowe's Home Assistant Addons

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

## WARNING! THIS IS AN EDGE REPOSITORY

This Home Assistant Add-ons repository contains edge builds of add-ons. Edge
builds add-ons are based upon the latest development version.

- They may not work at all.
- They might stop working at any time.
- They could have a negative impact on your system.

This repository was created for:

- Anybody willing to test.
- Anybody interested in trying out upcoming add-ons or add-on features.
- Developers.

If you are more interested in stable releases of our add-ons:

<https://github.com/jhollowe-addons/repository>

## Installation

Adding this add-ons repository to your Home Assistant instance is
pretty straightforward. In the Home Assistant add-on store,
a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
https://github.com/jhollowe-addons/repository-edge
```

## Add-ons provided by this repository

### &#10003; [MQTT IO][addon-mqtt-io]

![Latest Version][mqtt-io-version-shield]
![Supports armhf Architecture][mqtt-io-armhf-shield]
![Supports armv7 Architecture][mqtt-io-armv7-shield]
![Supports aarch64 Architecture][mqtt-io-aarch64-shield]
![Supports amd64 Architecture][mqtt-io-amd64-shield]
![Supports i386 Architecture][mqtt-io-i386-shield]

Expose GPIO modules and digital sensors via MQTT for remote control and monitoring.

[:books: MQTT IO add-on documentation][addon-doc-mqtt-io]

### &#10003; [ser2net server][addon-ser2net]

![Latest Version][ser2net-version-shield]
![Supports armhf Architecture][ser2net-armhf-shield]
![Supports armv7 Architecture][ser2net-armv7-shield]
![Supports aarch64 Architecture][ser2net-aarch64-shield]
![Supports amd64 Architecture][ser2net-amd64-shield]
![Supports i386 Architecture][ser2net-i386-shield]

Expose serial ports over the network, including RFC2217 support for remote port settings change (e.g. baud rate or RTS)


[:books: ser2net server add-on documentation][addon-doc-ser2net]

## Releases

Add-on releases are **NOT** based on [Semantic Versioning][semver], unlike
all our other repositories. The latest build commit SHA hash of each
add-on, represents the version number.

## Support

Got questions?

You can open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: MQTT IO][mqtt-io-issue]
- [Open an issue for the add-on: ser2net server][ser2net-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## Contributing

This is an active open-source project. We are always open to people who want to
use the code or contribute to it.

We have set up a separate document containing our
[contribution guidelines](.github/CONTRIBUTING.md).

Thank you for being involved! :heart_eyes:

## Adding a new add-on

We are currently not accepting third party add-ons to this repository.

[addon-mqtt-io]: https://github.com/jhollowe-addons/addon-mqtt-io/tree/26bc863
[addon-doc-mqtt-io]: https://github.com/jhollowe-addons/addon-mqtt-io/blob/26bc863/README.md
[mqtt-io-issue]: https://github.com/jhollowe-addons/addon-mqtt-io/issues
[mqtt-io-version-shield]: https://img.shields.io/badge/version-26bc863-blue.svg
[mqtt-io-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[mqtt-io-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[mqtt-io-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[mqtt-io-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[mqtt-io-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-ser2net]: https://github.com/jhollowe-addons/addon-ser2net/tree/v0.0.3
[addon-doc-ser2net]: https://github.com/jhollowe-addons/addon-ser2net/blob/v0.0.3/README.md
[ser2net-issue]: https://github.com/jhollowe-addons/addon-ser2net/issues
[ser2net-version-shield]: https://img.shields.io/badge/version-v0.0.3-blue.svg
[ser2net-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[ser2net-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[ser2net-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[ser2net-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[ser2net-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[issue]: https://github.com/jhollowe-addons/repository-edge/issues
[license-shield]: https://img.shields.io/github/license/jhollowe-addons/repository-edge.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2025.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-experimental-yellow.svg
[semver]: http://semver.org/spec/v2.0.0.html
[third-party-addons]: https://home-assistant.io/hassio/installing_third_party_addons/