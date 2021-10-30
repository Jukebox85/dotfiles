#!/bin/sh

# Touchpad
xinput set-prop $(xinput list --id-only "SYNA3255:00 06CB:7F27 Touchpad") "libinput Natural Scrolling Enabled" 1
xinput set-prop $(xinput list --id-only "SYNA3255:00 06CB:7F27 Touchpad") "libinput Tapping Enabled" 1

# Restoring wallpaper
find ~/Pictures/wallpapers/ -type f | shuf -n 1 | xargs xwallpaper --stretch &
