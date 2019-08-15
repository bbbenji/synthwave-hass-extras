# synthwave-hass-extras

[![Version](https://img.shields.io/badge/version-0.2.0-green.svg?style=flat-square&labelColor=2a2139&color=f92aad)](#)
[![maintained](https://img.shields.io/maintenance/yes/2019.svg?style=flat-square&labelColor=2a2139&color=f92aad)](#)

This is an extra for the [Synthwave Home Assistant theme](https://github.com/bbbenji/synthwave-hass) which adds some additional styling not possible using the a .yaml theme file.

## Installation

* Find your homeassistant directory containing your configuration (let's say `~/.homeassistant/`)
* Change into `~/.homeassistant/www` (create the `www` directory, if it does not exist, you then might have to restart HA)
* `$ wget https://raw.githubusercontent.com/bbbenji/synthwave-hass/master/synthwave.js` downloads the `.js` file directly where it should reside
* Add the following to the top of your UI Lovelace configuration (means either via Config UI or .yaml)
``` yaml
resources:
  - type: js
    url: /local/synthwave.js
```

**Screenshots**

See the main theme repository: [https://github.com/bbbenji/synthwave-hass](https://github.com/bbbenji/synthwave-hass)
