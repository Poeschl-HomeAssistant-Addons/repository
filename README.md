# Poeschl Home Assistant Supervisor Add-ons

![Project Stage][project-stage-badge]
![GitHub commit activity][commit-badge]
![Licence][licence-badge]

[![Installation Statistics][statistics-badge]][statistics-url]
[![Donate][donation-badge]][donation-url]

## Addons available

### 🧩 [Home Assistant Git Exporter][git-exporter-files]

![Latest Version][git-exporter-version-badge]
![Supports aarch64 Architecture][git-exporter-aarch64-badge]
![Supports amd64 Architecture][git-exporter-amd64-badge]
![Supports armhf Architecture][git-exporter-armhf-badge]
![Supports armv7 Architecture][git-exporter-armv7-badge]
![Supports i386 Architecture][git-exporter-i386-badge]

Export all of your Home Assistant configuration to a git repository of your choice

[![Home Assistant Git Exporter add-on documentation][addon-docs-badge]][git-exporter-doc]
### 🧩 [ICantBelieveItsNotValetudo][icantbelieveitsnotvaletudo-files]

![Latest Version][icantbelieveitsnotvaletudo-version-badge]
![Supports aarch64 Architecture][icantbelieveitsnotvaletudo-aarch64-badge]
![Supports amd64 Architecture][icantbelieveitsnotvaletudo-amd64-badge]
![Supports armhf Architecture][icantbelieveitsnotvaletudo-armhf-badge]
![Supports armv7 Architecture][icantbelieveitsnotvaletudo-armv7-badge]
![Supports i386 Architecture][icantbelieveitsnotvaletudo-i386-badge]

This is a simple companion service for valetudo which generates the map pngs.

[![ICantBelieveItsNotValetudo add-on documentation][addon-docs-badge]][icantbelieveitsnotvaletudo-doc]
### 🧩 [MaryTTS][marytts-files]

![Latest Version][marytts-version-badge]
![Supports aarch64 Architecture][marytts-aarch64-badge]
![Supports amd64 Architecture][marytts-amd64-badge]
![Supports armhf Architecture][marytts-armhf-badge]
![Supports armv7 Architecture][marytts-armv7-badge]
![Supports i386 Architecture][marytts-i386-badge]

The Mary TTS speech engine as a Hassio-Addon.

[![MaryTTS add-on documentation][addon-docs-badge]][marytts-doc]
### 🧩 [Mopidy][mopidy-files]

![Latest Version][mopidy-version-badge]
![Supports aarch64 Architecture][mopidy-aarch64-badge]
![Supports amd64 Architecture][mopidy-amd64-badge]
![Supports armhf Architecture][mopidy-armhf-badge]
![Supports armv7 Architecture][mopidy-armv7-badge]
![Supports i386 Architecture][mopidy-i386-badge]

Mopidy Music Server

[![Mopidy add-on documentation][addon-docs-badge]][mopidy-doc]
### 🧩 [OWASP Juice Shop][juice-shop-files]

![Latest Version][juice-shop-version-badge]
![Supports aarch64 Architecture][juice-shop-aarch64-badge]
![Supports amd64 Architecture][juice-shop-amd64-badge]
![Supports armhf Architecture][juice-shop-armhf-badge]
![Supports armv7 Architecture][juice-shop-armv7-badge]
![Supports i386 Architecture][juice-shop-i386-badge]

The most trustworthy online shop out there.

[![OWASP Juice Shop add-on documentation][addon-docs-badge]][juice-shop-doc]

## Deprecated Addons

These addons will not be updated anymore. Feel free to fork them.

### 🕸 [Asterisk][asterisk-files]

![Latest Version][asterisk-version-badge]

(Deprecated) Asterisk is an open source framework for building communications applications. Asterisk turns an ordinary computer into a communications server

[![Asterisk add-on documentation][addon-docs-badge]][asterisk-doc]
### 🕸 [Docker Container Stats][container-stats-files]

![Latest Version][container-stats-version-badge]

(Deprecated) A web interface for viewing historical and current statistics per docker container

[![Docker Container Stats add-on documentation][addon-docs-badge]][container-stats-doc]
### 🕸 [OWASP ZAP][owasp-zap-files]

![Latest Version][owasp-zap-version-badge]

(Deprecated) The OWASP Zed Attack Proxy (ZAP) is one of the world’s most popular free security tools and is actively maintained by a dedicated international team of volunteers.

[![OWASP ZAP add-on documentation][addon-docs-badge]][owasp-zap-doc]
### 🕸 [mitmproxy][mitmproxy-files]

![Latest Version][mitmproxy-version-badge]

(Deprecated) A free and open source interactive HTTPS proxy for intercepting and inspecting network traffic

[![mitmproxy add-on documentation][addon-docs-badge]][mitmproxy-doc]

## Installation

To install any of the add-ons offered in this repository, you must first add its repository URL to your Home Assistant instance. To do so, click the following button:

[![Add repository to your Home Assistant instance.][repository-badge]][repository-url]

or manually add the following repository URL in the Home Assistant add-on store:

`https://github.com/Poeschl-HomeAssistant-Addons/repository`

Then search for any of the add-ons in our addon store (button below) to install them.

[![Open your Home Assistant instance and show the Supervisor add-on store.][addon-store-badge]][addon-store-url]

You can also install them over the buttons in the Readmes of the addon folders.

## Support

If you are here, seeking help, please look at the issues of the specific addon.

- [Issues of Asterisk][asterisk-issue]
- [Issues of Docker Container Stats][container-stats-issue]
- [Issues of Home Assistant Git Exporter][git-exporter-issue]
- [Issues of ICantBelieveItsNotValetudo][icantbelieveitsnotvaletudo-issue]
- [Issues of MaryTTS][marytts-issue]
- [Issues of Mopidy][mopidy-issue]
- [Issues of OWASP Juice Shop][juice-shop-issue]
- [Issues of OWASP ZAP][owasp-zap-issue]
- [Issues of mitmproxy][mitmproxy-issue]

[project-stage-badge]: https://img.shields.io/badge/project%20stage-✔%20stable-green.svg
[commit-badge]: https://img.shields.io/github/commit-activity/m/Poeschl-HomeAssistant-Addons/repository
[licence-badge]: https://img.shields.io/github/license/Poeschl-HomeAssistant-Addons/repository
[Stable-Repository]: https://github.com/Poeschl-HomeAssistant-Addons/repository

[statistics-badge]: https://img.shields.io/badge/-usage_statistics-41BDF5.svg?style=for-the-badge
[statistics-url]: https://addonstats.poeschl.xyz?filter=68413af6
[donation-badge]: https://img.shields.io/badge/Buy%20me%20a%20coffee-%23d32f2f?logo=buy-me-a-coffee&style=for-the-badge&logoColor=white
[donation-url]: https://www.buymeacoffee.com/Poeschl

[repository-badge]: https://img.shields.io/badge/Add_addon_repository_to_my-Home%20Assistant-41BDF5?logo=home-assistant&style=for-the-badge
[repository-url]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A//github.com/Poeschl-HomeAssistant-Addons/repository
[addon-store-url]: https://my.home-assistant.io/redirect/supervisor_store/
[addon-store-badge]: https://img.shields.io/badge/Open_Addon_store_on_my-Home%20Assistant-41BDF5?logo=home-assistant&style=for-the-badge

[addon-docs-badge]: https://img.shields.io/badge/Documentation-41BDF5?style=for-the-badge

[asterisk-files]: https://github.com/Poeschl-HomeAssistant-Addons/asterisk/tree/1.1.1
[asterisk-doc]: https://github.com/Poeschl-HomeAssistant-Addons/asterisk/blob/1.1.1/README.md
[asterisk-issue]: https://github.com/Poeschl-HomeAssistant-Addons/asterisk/issues
[asterisk-version-badge]: https://img.shields.io/badge/version-1.1.1-blue.svg
[asterisk-aarch64-badge]: https://img.shields.io/badge/aarch64-yes-green.svg
[asterisk-amd64-badge]: https://img.shields.io/badge/amd64-yes-green.svg
[asterisk-armhf-badge]: https://img.shields.io/badge/armhf-yes-green.svg
[asterisk-armv7-badge]: https://img.shields.io/badge/armv7-yes-green.svg
[asterisk-i386-badge]: https://img.shields.io/badge/i386-yes-green.svg
[container-stats-files]: https://github.com/Poeschl-HomeAssistant-Addons/container-stats/tree/1.5.0
[container-stats-doc]: https://github.com/Poeschl-HomeAssistant-Addons/container-stats/blob/1.5.0/README.md
[container-stats-issue]: https://github.com/Poeschl-HomeAssistant-Addons/container-stats/issues
[container-stats-version-badge]: https://img.shields.io/badge/version-1.5.0-blue.svg
[container-stats-aarch64-badge]: https://img.shields.io/badge/aarch64-yes-green.svg
[container-stats-amd64-badge]: https://img.shields.io/badge/amd64-yes-green.svg
[container-stats-armhf-badge]: https://img.shields.io/badge/armhf-yes-green.svg
[container-stats-armv7-badge]: https://img.shields.io/badge/armv7-yes-green.svg
[container-stats-i386-badge]: https://img.shields.io/badge/i386-yes-green.svg
[git-exporter-files]: https://github.com/Poeschl-HomeAssistant-Addons/git-exporter/tree/1.17.1
[git-exporter-doc]: https://github.com/Poeschl-HomeAssistant-Addons/git-exporter/blob/1.17.1/README.md
[git-exporter-issue]: https://github.com/Poeschl-HomeAssistant-Addons/git-exporter/issues
[git-exporter-version-badge]: https://img.shields.io/badge/version-1.17.1-blue.svg
[git-exporter-aarch64-badge]: https://img.shields.io/badge/aarch64-yes-green.svg
[git-exporter-amd64-badge]: https://img.shields.io/badge/amd64-yes-green.svg
[git-exporter-armhf-badge]: https://img.shields.io/badge/armhf-yes-green.svg
[git-exporter-armv7-badge]: https://img.shields.io/badge/armv7-yes-green.svg
[git-exporter-i386-badge]: https://img.shields.io/badge/i386-yes-green.svg
[icantbelieveitsnotvaletudo-files]: https://github.com/Poeschl-HomeAssistant-Addons/icantbelieveitsnotvaletudo/tree/4.0.1
[icantbelieveitsnotvaletudo-doc]: https://github.com/Poeschl-HomeAssistant-Addons/icantbelieveitsnotvaletudo/blob/4.0.1/README.md
[icantbelieveitsnotvaletudo-issue]: https://github.com/Poeschl-HomeAssistant-Addons/icantbelieveitsnotvaletudo/issues
[icantbelieveitsnotvaletudo-version-badge]: https://img.shields.io/badge/version-4.0.1-blue.svg
[icantbelieveitsnotvaletudo-aarch64-badge]: https://img.shields.io/badge/aarch64-yes-green.svg
[icantbelieveitsnotvaletudo-amd64-badge]: https://img.shields.io/badge/amd64-yes-green.svg
[icantbelieveitsnotvaletudo-armhf-badge]: https://img.shields.io/badge/armhf-no-red.svg
[icantbelieveitsnotvaletudo-armv7-badge]: https://img.shields.io/badge/armv7-yes-green.svg
[icantbelieveitsnotvaletudo-i386-badge]: https://img.shields.io/badge/i386-yes-green.svg
[marytts-files]: https://github.com/Poeschl-HomeAssistant-Addons/marytts/tree/1.5.2
[marytts-doc]: https://github.com/Poeschl-HomeAssistant-Addons/marytts/blob/1.5.2/README.md
[marytts-issue]: https://github.com/Poeschl-HomeAssistant-Addons/marytts/issues
[marytts-version-badge]: https://img.shields.io/badge/version-1.5.2-blue.svg
[marytts-aarch64-badge]: https://img.shields.io/badge/aarch64-yes-green.svg
[marytts-amd64-badge]: https://img.shields.io/badge/amd64-yes-green.svg
[marytts-armhf-badge]: https://img.shields.io/badge/armhf-yes-green.svg
[marytts-armv7-badge]: https://img.shields.io/badge/armv7-yes-green.svg
[marytts-i386-badge]: https://img.shields.io/badge/i386-yes-green.svg
[mopidy-files]: https://github.com/Poeschl-HomeAssistant-Addons/mopidy/tree/2.2.1
[mopidy-doc]: https://github.com/Poeschl-HomeAssistant-Addons/mopidy/blob/2.2.1/README.md
[mopidy-issue]: https://github.com/Poeschl-HomeAssistant-Addons/mopidy/issues
[mopidy-version-badge]: https://img.shields.io/badge/version-2.2.1-blue.svg
[mopidy-aarch64-badge]: https://img.shields.io/badge/aarch64-no-red.svg
[mopidy-amd64-badge]: https://img.shields.io/badge/amd64-yes-green.svg
[mopidy-armhf-badge]: https://img.shields.io/badge/armhf-yes-green.svg
[mopidy-armv7-badge]: https://img.shields.io/badge/armv7-yes-green.svg
[mopidy-i386-badge]: https://img.shields.io/badge/i386-yes-green.svg
[juice-shop-files]: https://github.com/Poeschl-HomeAssistant-Addons/juice-shop/tree/1.2.1
[juice-shop-doc]: https://github.com/Poeschl-HomeAssistant-Addons/juice-shop/blob/1.2.1/README.md
[juice-shop-issue]: https://github.com/Poeschl-HomeAssistant-Addons/juice-shop/issues
[juice-shop-version-badge]: https://img.shields.io/badge/version-1.2.1-blue.svg
[juice-shop-aarch64-badge]: https://img.shields.io/badge/aarch64-no-red.svg
[juice-shop-amd64-badge]: https://img.shields.io/badge/amd64-yes-green.svg
[juice-shop-armhf-badge]: https://img.shields.io/badge/armhf-no-red.svg
[juice-shop-armv7-badge]: https://img.shields.io/badge/armv7-no-red.svg
[juice-shop-i386-badge]: https://img.shields.io/badge/i386-no-red.svg
[owasp-zap-files]: https://github.com/Poeschl-HomeAssistant-Addons/owasp-zap/tree/2.2.0
[owasp-zap-doc]: https://github.com/Poeschl-HomeAssistant-Addons/owasp-zap/blob/2.2.0/README.md
[owasp-zap-issue]: https://github.com/Poeschl-HomeAssistant-Addons/owasp-zap/issues
[owasp-zap-version-badge]: https://img.shields.io/badge/version-2.2.0-blue.svg
[owasp-zap-aarch64-badge]: https://img.shields.io/badge/aarch64-no-red.svg
[owasp-zap-amd64-badge]: https://img.shields.io/badge/amd64-yes-green.svg
[owasp-zap-armhf-badge]: https://img.shields.io/badge/armhf-no-red.svg
[owasp-zap-armv7-badge]: https://img.shields.io/badge/armv7-yes-green.svg
[owasp-zap-i386-badge]: https://img.shields.io/badge/i386-no-red.svg
[mitmproxy-files]: https://github.com/Poeschl-HomeAssistant-Addons/mitmproxy/tree/1.2.0
[mitmproxy-doc]: https://github.com/Poeschl-HomeAssistant-Addons/mitmproxy/blob/1.2.0/README.md
[mitmproxy-issue]: https://github.com/Poeschl-HomeAssistant-Addons/mitmproxy/issues
[mitmproxy-version-badge]: https://img.shields.io/badge/version-1.2.0-blue.svg
[mitmproxy-aarch64-badge]: https://img.shields.io/badge/aarch64-yes-green.svg
[mitmproxy-amd64-badge]: https://img.shields.io/badge/amd64-yes-green.svg
[mitmproxy-armhf-badge]: https://img.shields.io/badge/armhf-yes-green.svg
[mitmproxy-armv7-badge]: https://img.shields.io/badge/armv7-yes-green.svg
[mitmproxy-i386-badge]: https://img.shields.io/badge/i386-yes-green.svg
