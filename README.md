# Home Assistant custom component for GE Cync wifi lights

## This is a work in progress and not yet working

** This has only been tested with the GE Cync Light strip but it should work with any GE Cync wifi lights. **

[GE Cync ](https://www.gelighting.com/)

Big thanks to [https://github.com/unixpickle/cbyge](https://github.com/unixpickle/cbyge) for reverse engineering the API.

# Installation

This custom component can be installed in two different ways: `manually` or `using HACS` (coming)

## 1. Manual Installation

1. Download the `.zip` file from the
   [latest release](https://github.com/<insert link>/releases/latest).
2. Unpack the release and copy the `custom_components/home-assistant-cync` directory
   into the `custom_components` directory of your Home Assistant
   installation.
----------
3. install bluepy in the HA virtual environment
4. Add the `yeelight_bt` lights as described in next section.