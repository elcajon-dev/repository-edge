# Home Assistant Add-on: Advanced Code Server

[![Release][release-shield]][release]
![Project Stage][project-stage-shield]
![Project Maintenance][maintenance-shield]
![Reported Installations][installations-shield-edge]


Code Server experience integrated in the Home Assistant frontend.

## About

This add-on runs Code Server, which
gives you a Visual Studio Code experience straight from the browser. It allows
you to edit your Home Assistant configuration directly from your web browser,
directly from within the Home Assistant frontend.

The add-on has the Home Assistant, MDI icons and YAML extensions pre-installed
and pre-configured right out of the box. This means that auto-completion works
instantly, without the need for configuring anything.

This version of Code Server adds some advanced features compared to the
[HA Community Code Server][hassio-addons] version.

For example:

- Host Docker access
- Material Design icons pre-installed
- Cron installed and configured
- Tailscale installed
- Cloudflare installed
- Rclone installed
- Custom cont-init.d and services.d scripts

Please be aware that when misused you can destroy your whole system with this add-on.

## WARNING! THIS IS AN EDGE VERSION!

This Home Assistant Add-ons repository contains edge builds of add-ons.
Edge builds add-ons are based upon the latest development version.

- They may not work at all.
- They might stop working at any time.
- They could have a negative impact on your system.

This repository was created for:

- Anybody willing to test.
- Anybody interested in trying out upcoming add-ons or add-on features.
- Developers.

[maintenance-shield]: https://img.shields.io/maintenance/yes/2025.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[release-shield]: https://img.shields.io/badge/version-43816da-blue.svg
[release]: https://github.com/elcajon-dev/addon-code-server/tree/43816da
[hassio-addons]: https://github.com/hassio-addons/addon-vscode
[installations-shield-edge]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fanalytics.home-assistant.io%2Faddons.json&query=%24%5B%22dca9deef_code-server%22%5D.total&label=Reported%20Installations&link=https%3A%2F%2Fanalytics.home-assistant.io/add-ons
[installations-shield-stable]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fanalytics.home-assistant.io%2Faddons.json&query=%24%5B%22a03729f7_code-server%22%5D.total&label=Reported%20Installations&link=https%3A%2F%2Fanalytics.home-assistant.io/add-ons
