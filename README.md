# openHAB Frontail AGM Theme

These are my versions of the themes for the **openHAB Log Viewer** (*Frontail*).
There are two themes available:
- Light
and
- Dark.
My themes are based on basic themes available in openHAB 3x, but there are some changes in colors and displaying which makes logs very readable.
I also corrected wrong *INFO* logs displaying as error lines.
I hope you will like them.

### Dark Theme:

![dark theme](Frontail_AGM Dark.jpg)

### Light Theme:

![light theme](Frontail_AGM Light.jpg)

## How to change Theme in openhabian 3x.
The `openhab_AEM.css` file should be uploaded to the directory: `/opt/frontail/web/assets/styles` (overwrite the existing file).
And the file `openhab_AEM.json` should be uploaded to the directory: `/opt/frontail/preset` (overwrite the existing file).
You need to restart the Frontail service by issuing the commands:
- `sudo systemctl daemon-reload`
- `sudo service frontail restart`
