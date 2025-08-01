# EDGE - Home Assistant Add-ons

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)


## WARNING! THIS IS AN EDGE REPOSITORY

This Home Assistant Add-ons repository contains edge builds of add-ons. Edge
builds add-ons are based upon the latest development version.

- They may not work at all.
- They might stop working at any time.
- They could have a negative impact on your system.

## Installation

Use the following button to quickly add the repository:

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Felcajon%2Frepository-edge)

Or use the following URL to add this repository:

```txt
https://github.com/elcajon-dev/repository-edge
```

## Add-ons provided by this repository

### &#10003; [Advanced Code Server][addon-code-server]

![Latest Version][code-server-version-shield]
![Reported Installations][code-server-installations-shield-edge]
![Supports armhf Architecture][code-server-armhf-shield]
![Supports armv7 Architecture][code-server-armv7-shield]
![Supports aarch64 Architecture][code-server-aarch64-shield]
![Supports amd64 Architecture][code-server-amd64-shield]
![Supports i386 Architecture][code-server-i386-shield]
Code Server experience integrated in the Home Assistant frontend.

[:books: Advanced Code Server add-on documentation][addon-doc-code-server]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

- [Open an issue for the add-on: Advanced Code Server][code-server-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## License

MIT License

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

[addon-code-server]: https://github.com/elcajon-dev/addon-code-server/tree/43816da
[addon-doc-code-server]: https://github.com/elcajon-dev/addon-code-server/blob/43816da/README.md
[code-server-issue]: https://github.com/elcajon-dev/addon-code-server/issues
[code-server-version-shield]: https://img.shields.io/badge/version-43816da-blue.svg
[code-server-installations-shield-edge]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fanalytics.home-assistant.io%2Faddons.json&query=%24%5B%22dca9deef_code-server%22%5D.total&label=Reported%20Installations&link=https%3A%2F%2Fanalytics.home-assistant.io/add-ons
[code-server-aarch64-shield]: https://img.shields.io/badge/aarch64-no-red.svg
[code-server-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[code-server-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[code-server-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[code-server-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[issue]: https://github.com/elcajon-dev/repository-edge/issues
[license-shield]: https://img.shields.io/github/license/elcajon-dev/repository-edge.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2025.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-experimental-yellow.svg
[semver]: http://semver.org/spec/v2.0.0.html