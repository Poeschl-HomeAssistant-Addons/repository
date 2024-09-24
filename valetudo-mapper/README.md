# Valetudo RE Mapper (Home Assistant Supervisor Addon)

This is the adaption of [valetudo-mapper](https://github.com/rand256/valetudo-mapper) as a Supervisor addon.

[![Release][release-badge]][release]
![Addon Stage][stage-badge]

[![Donate][donation-badge]][donation-url]

## Config

The config of the addon is identical to the `mqtt` section described in the README of Valetudo Mapper.
The `webserver` section is fixed to `{ "enabled": true, "port": 3000 }`

If you use the Mosquitto Addon in Home Assistant `core-mosquitto` can be used as broker address like this: `mqtt://<user>:<password>@core-mosquitto`.

## PNG image

The generated image will be served over the Supervisor Ingress feature. So the floor plan can be accessed via the build-in side panel or the auto-configured mqtt camera.


[stage-badge]: https://img.shields.io/badge/Addon%20stage-stable-green.svg

[release-badge]: https://img.shields.io/badge/version-v1.12.0-blue.svg
[release]: https://github.com/Poeschl-HomeAssistant-Addons/valetudo-mapper/tree/v1.12.0

[donation-badge]: https://img.shields.io/badge/Buy%20me%20a%20coffee-%23d32f2f?logo=buy-me-a-coffee&style=for-the-badge&logoColor=white
[donation-url]: https://www.buymeacoffee.com/Poeschl

