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

You have several options to get them answered:

- The Home Assistant Community Add-ons [Discord Chat Server][discord]
- The Home Assistant [Community Forum][forum].
- The Home Assistant [Discord Chat Server][discord-ha].
- Join the [Reddit subreddit][reddit] in [/r/homeassistant][reddit]

You could also open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

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

For questions, please contact [Franck Nijhof][frenck]:

- Drop him an email: frenck@addons.community
- Chat with him on [Discord Chat][discord]
- Message him via the forums: [frenck][forum-frenck]

## License

MIT License

Copyright (c) 2018-2024 Franck Nijhof

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[addon-ser2net]: https://github.com/jhollowe-addons/addon-ser2net/tree/881925c
[addon-doc-ser2net]: https://github.com/jhollowe-addons/addon-ser2net/blob/881925c/README.md
[ser2net-issue]: https://github.com/jhollowe-addons/addon-ser2net/issues
[ser2net-version-shield]: https://img.shields.io/badge/version-881925c-blue.svg
[ser2net-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[ser2net-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[ser2net-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[ser2net-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[ser2net-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[issue]: https://github.com/jhollowe-addons/repository-edge/issues
[license-shield]: https://img.shields.io/github/license/jhollowe-addons/repository-edge.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2024.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-experimental-yellow.svg
[semver]: http://semver.org/spec/v2.0.0.html
[third-party-addons]: https://home-assistant.io/hassio/installing_third_party_addons/