# Docker Container Stats

It contains [Docker Container Stats](https://github.com/virtualzone/docker-container-stats) to monitor all running containers / addons.

[![Release][release-badge]][release]
![Addon Stage][stage-badge]

[![Donate][donation-badge]][donation-url]

## 🧪 Experimental Addon

During long-term usage I noticed that the addon fills up all available memory when getting the data for a week.
Especially on a Raspberry Pi with Home Assistant this means death in a few minutes.
__Use this addon on your own risk!__

## Security

Since the addon accesses the docker api, the security rating is this low.
Unfortunately there is now way to access the docker api without disabling the *Protection Mode* of the addon.
Technically with disabling it, the addon can access and control other addons and the core on a HA supervised system.
But without it we can not retrieve the statistics of the running container and this addon don't work at all.


[stage-badge]: https://img.shields.io/badge/Addon%20stage-deprecated-lightgrey.svg

[release-badge]: https://img.shields.io/badge/version-v1.5.0-blue.svg
[release]: https://github.com/Poeschl-HomeAssistant-Addons/container-stats/tree/v1.5.0

[donation-badge]: https://img.shields.io/badge/Buy%20me%20a%20coffee-%23d32f2f?logo=buy-me-a-coffee&style=for-the-badge&logoColor=white
[donation-url]: https://www.buymeacoffee.com/Poeschl

