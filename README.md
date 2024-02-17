
# SMA Data Manager

[![GitHub Release][releases-shield]][releases]
[![GitHub Activity][commits-shield]][commits]
[![License][license-shield]](LICENSE)

[![hacs][hacsbadge]][hacs]
![Project Maintenance][maintenance-shield]


_Integration to integrate with the [SMA Data Manager][sma_data_manager]._


## Installation

## HACS (recommended)

1. Add `https://github.com/thorsten/homeassistant_sma_data_manager` as a custom repository, choose `Integration` as Category and add.
2. In the HACS UI, search for `SMA Data Manager` and install it.
3. Restart Home Assistant
4. In the HA UI go to "Configuration" -> "Integrations" click "+" and search for "SMA Data manager"

## Manual

1. Using the tool of choice open the directory for your HA configuration (where you find `configuration.yaml`).
1. If you do not have a `custom_components` directory there, you need to create it.
2. In the `custom_components` directory create a new folder called `sma_data_manager`.
3. Download _all_ the files from the `custom_components/sma_data_manager/` directory in this repository.
4. Place the files you downloaded in the new directory you created.
5. Restart Home Assistant
6. In the HA UI go to "Configuration" -> "Integrations" click "+" and search for "Integration blueprint"

# Configuration

Configuration is done using the UI.
You'll be prompted to enter the IP and credentials to the SMA Data Manager.
After the initial setup, you'll have to configure the channels you want to use in the integration options.
To find available channels, take a look in the "Instantaneous Values" menu of the SMA Data Manager web interface.


# Contributions are welcome!

If you want to contribute to this please read the [Contribution guidelines](CONTRIBUTING.md)


# Notice

This integration is not affiliated with SMA Solar Technology AG in any way.
The SMA and SMA Data Manager names and logos are trademarks of SMA Solar Technology AG.
Use at your own risk.

***

[sma_data_manager]: https://www.sma.de/en/products/monitoring-control/data-manager-m
[commits-shield]: https://img.shields.io/github/commit-activity/y/thorsten/homeassistant_sma_data_manager.svg?style=for-the-badge
[commits]: https://github.com/thorsten/homeassistant_sma_data_manager/commits/main
[hacs]: https://github.com/hacs/integration
[hacsbadge]: https://img.shields.io/badge/HACS-Custom-orange.svg?style=for-the-badge
[license-shield]: https://img.shields.io/github/license/thorsten/homeassistant_sma_data_manager.svg?style=for-the-badge
[maintenance-shield]: https://img.shields.io/badge/maintainer-%40thorsten-blue.svg?style=for-the-badge


[releases-shield]: https://img.shields.io/github/release/thorsten/homeassistant_sma_data_manager.svg?style=for-the-badge
[releases]: https://github.com/thorsten/homeassistant_sma_data_manager/releases
