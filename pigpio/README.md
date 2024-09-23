# pigpio

Wraps the C control lib [pigpio](https://github.com/joan2937/pigpio) in a Home Assistant addon to allow an easy installation.

[![Release][release-badge]][release]
![Addon Stage][stage-badge]

[![Donate][donation-badge]][donation-url]

## Usage

This addon runs the pigpio deamon which listens on http commands and control the GPIO on a Raspberry Pi accordingly (currently only up to PI 4).
Running this and using the [remote_rpi_pgio integration](https://www.home-assistant.io/integrations/remote_rpi_gpio/) in your Home Assistant configuration pointing to `localhost` will connect both worlds.

For additional options for the deamon use the optional addon setting `additional_options`.
The options`-g -f` will be always set!

## Security

It accesses `/dev/mem` on the host and also has full access to the raw io data.


[stage-badge]: https://img.shields.io/badge/Addon%20stage-stable-green.svg

[release-badge]: https://img.shields.io/badge/version-v1.5.3-blue.svg
[release]: https://github.com/Poeschl-HomeAssistant-Addons/pigpio/tree/v1.5.3

[donation-badge]: https://img.shields.io/badge/Buy%20me%20a%20coffee-%23d32f2f?logo=buy-me-a-coffee&style=for-the-badge&logoColor=white
[donation-url]: https://www.buymeacoffee.com/Poeschl

