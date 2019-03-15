# hass.aioheos.media_player

Denon Heos media player for Home Assistant.

## install

    > cp heos.py ~/.homeassistant/custom_component/heos/media_player.py

## configuration
## Give info on one of the heos devices on your network.  The others should be discovered

    media_player:
        platform: heos
        host: <hostname>
        name: Name of the device

