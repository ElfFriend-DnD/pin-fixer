## Pin Fixer
Modifies the behaviour of map pins so that they do not become too small to see when the map is zoomed out, or so large that they cover everything when zoomed in.

Scale factors and limits are configurable per-scene via the Scene Config menu.

![Config Options](config.png)

With the default settings above, pins will remain the same on-screen size at all times. By increasing the Max Scale, they will become larger when zoomed it, by decreasing the Min Scale, they will become smaller when zoomed out. The Zoom Floor and Ceiling are hard cut-offs, beyond which no further scaling will occur.

*Example:* If you wish to have pins get no larger than 2x normal size, no smaller than .75x normal size, and not get smaller when the canvas is scaled smaller than .5, your settings are (in order): `.75, 2, .5, 3`.

The last setting pertains only to other modules that add a HUD to map pins. It tweaks these HUDs so they remain the same size as the map zooms in and out, you can configure this static size to be larger/smaller than normal by setting the scale value. A value of 1 is the default size that the module normally shows its HUD.

Install Via Manifest:
> [https://raw.githubusercontent.com/zeel01/pin-fixer/master/module.json](https://raw.githubusercontent.com/zeel01/pin-fixer/master/module.json)

#### *Commissioned by GloriousGe0rge from CORSAIR*