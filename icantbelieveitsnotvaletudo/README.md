# ICantBelieveItsNotValetudo Addon

This is the adaption of [ICantBelieveItsNotValetudo](https://github.com/Hypfer/ICantBelieveItsNotValetudo) as a Supervisor addon.

[![Release][release-badge]][release]
![Addon Stage][stage-badge]

[![Donate][donation-badge]][donation-url]

## Config

The configuration keys are identical to the [configuration of ICantBelieveItsNotValetudo](https://github.com/Hypfer/ICantBelieveItsNotValetudo/blob/main/README.md).
Please get the meaning for them from there.
It's normal that the structure of the addon differs from the official config file, this is nessesary because of the Supervisor Addon config structure.

If you use the Mosquitto Addon in Home Assistant `core-mosquitto` can be used as broker address like this: `mqtt://<user>:<password>@core-mosquitto`. Keep in mind to set proper `mapDataTopic` value. As of Valetudo 2021.04.0, it's `${topicPrefix}/${identifier}/MapData/map-data`, which with default values is equal to `valetudo/rockrobo/MapData/map-data`.

## PNG image

The generated image will be served over the Supervisor Ingress feature. So the floor plan can be accessed via the build-in side panel and the auto-configured mqtt camera.


[stage-badge]: https://img.shields.io/badge/Addon%20stage-stable-green.svg

[release-badge]: https://img.shields.io/badge/version-v4.0.1-blue.svg
[release]: https://github.com/Poeschl-HomeAssistant-Addons/ICantBelieveItsNotValetudo/tree/v4.0.1

[donation-badge]: https://img.shields.io/badge/Buy%20me%20a%20coffee-%23d32f2f?logo=buy-me-a-coffee&style=for-the-badge&logoColor=white
[donation-url]: https://www.buymeacoffee.com/Poeschl

