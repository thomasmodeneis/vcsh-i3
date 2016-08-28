vcsh-i3
=======
My configuration for the [i3 Window Manager](http://www.i3wm.org).

Dependencies (Arch Linux)
------------
* `aur/i3-gaps-git` (i3wm with gaps support)
* `aur/i3blocks` (nice & light menubar)
* `community/xdotool` (for window title in menubar)
* `extra/cantarell-fonts`
* `community/ttf-font-awesome` (for icons in the menubar)

Recommended dependencies
------------------------
* `aur/autorandr-git` (used to detect screen changes in `.config/i3/scripts/display`)
* `extra/alsa-utils` (for showing volume in i3blocks)
* `extra/xorg-xrandr` (for showing screens in i3blocks, installed through the `xorg` or `xorg-apps` group)
* `community/wifi-radar` (for showing WiFi info in i3blocks)
* A clone of [vcsh-bin](https://github.com/agboom/vcsh-bin) for stayalive support in `.config/i3/scripts/stayalive`

Configuration
-------------
* In [.config/i3/scripts/wifi](.config/i3/scripts/wifi): change the `INTERFACE` to match your 
system's.
* If you want i3 without gaps, you can install `community/i3wm` instead and remove all gaps configuration from `.config/i3/config`.
* Read the [Arch wiki](https://wiki.archlinux.org/index.php/I3) or [documentation](http://i3wm.org/docs/userguide.html) for more customization options

You are free to fork and edit to your liking!

-- Chookies
