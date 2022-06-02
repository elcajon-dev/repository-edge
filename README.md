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

Use the following URL to add this repository:

```txt
https://github.com/elcajon/repository-edge
```

## Add-ons provided by this repository

### &#10003; [Code Server][addon-code-server]

![Latest Version][code-server-version-shield]
![Supports armhf Architecture][code-server-armhf-shield]
![Supports armv7 Architecture][code-server-armv7-shield]
![Supports aarch64 Architecture][code-server-aarch64-shield]
![Supports amd64 Architecture][code-server-amd64-shield]
![Supports i386 Architecture][code-server-i386-shield]

Code Server experience integrated in the Home Assistant frontend.

[:books: Code Server add-on documentation][addon-doc-code-server]

### &#10003; [Generic][addon-generic]

![Latest Version][generic-version-shield]
![Supports armhf Architecture][generic-armhf-shield]
![Supports armv7 Architecture][generic-armv7-shield]
![Supports aarch64 Architecture][generic-aarch64-shield]
![Supports amd64 Architecture][generic-amd64-shield]
![Supports i386 Architecture][generic-i386-shield]

Generic add-on for development purposes

[:books: Generic add-on documentation][addon-doc-generic]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

- [Open an issue for the add-on: Code Server][code-server-issue]
- [Open an issue for the add-on: Generic][generic-issue]

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

[addon-code-server]: https://github.com/elcajon/addon-code-server/tree/f8aa3d6
[addon-doc-code-server]: https://github.com/elcajon/addon-code-server/blob/f8aa3d6/README.md
[code-server-issue]: https://github.com/elcajon/addon-code-server/issues
[code-server-version-shield]: https://img.shields.io/badge/version-f8aa3d6-blue.svg
[code-server-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[code-server-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[code-server-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[code-server-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[code-server-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-generic]: https://github.com/elcajon/addon-generic/tree/v0.0.14
[addon-doc-generic]: https://github.com/elcajon/addon-generic/blob/v0.0.14/README.md
[generic-issue]: https://github.com/elcajon/addon-generic/issues
[generic-version-shield]: https://img.shields.io/badge/version-v0.0.14-blue.svg
[generic-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[generic-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[generic-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[generic-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[generic-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[issue]: https://github.com/elcajon/repository-edge/issues
[license-shield]: https://img.shields.io/github/license/elcajon/repository-edge.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2022.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-experimental-yellow.svg
[semver]: http://semver.org/spec/v2.0.0.html