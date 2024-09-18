# pwnagotchi-plugins
My custom plugins for my pwnagotchi


# Clock
The clock plugin is a fork of [pwnagotchi-plugins-contrib/clock.py](https://github.com/evilsocket/pwnagotchi-plugins-contrib/blob/master/clock.py).
It removes the check for a waveshare v2 screen.

## Installing
**This plugin has only been tested on a waveshare v4 screen with the memtemp plugin on, and moved to `155,70`**
1. Set `main.plugins.memtemp.position="155,70"` - Move the memtemp display up a bit
2. Install clock.py to your plugins directory
3. Enable the plugin via cli/web ui
