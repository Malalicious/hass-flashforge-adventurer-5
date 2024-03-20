# FlashForge Adventurer 5M (Pro) for Home Assistant
A fork of Adventurer 4 integration adjusted for the FlashForge Adventurer 5M (Pro) printer.

It adds three entities:

- state, together with nozzle, bed temperatures and layers (being printed and total number) available as attributes
- current print job's progress
- camera feed
<img src="https://raw.githubusercontent.com/Malalicious/hass-flashforge-adventurer-5/master/Adventurer-example-1.PNG" alt="Example" width="800"/>

## Installation

You can install it through [HACS](https://hacs.xyz/). Alternatively, you can
download this repo and add it to your `custom_components` directory.

After the integration is installed, go to Settings -> Integrations, and
configure it through the _Add integration_ button. You will need to provide the
IP address of the printer. It might be a good idea to assign it a static IP
address in your router settings.

## Printer compatibility
Works with Adventurer 5M. Possibly with the Pro too because I do not think there's any difference. Untested on the Pro.
