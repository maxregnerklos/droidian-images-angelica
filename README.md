Droidian on Xiaomi Redmi 7 (onclite)
========

Droidian is a GNU/Linux distribution based on top of Mobian, a Debian-based distribution for mobile devices. The goal of Droidian is to be able to run Mobian on Android phones.

## THE INSTRUCTIONS BELLOW WILL WIPE ALL THE DATA ON YOUR DEVICE

# Default password: 1234

## Installation
 * Download the latest build here: https://github.com/droidian-onclite/droidian-images/releases
 * Unpack the zip file
 * Boot to fastboot:
   <pre><code>adb reboot fastboot</code></pre>
 * Using fastboot flash following partitions:
    <pre><code>fastboot flash boot data/boot.img
   fastboot flash userdata data/userdata.img</code></pre>
 * Reboot to system and "DO NOT PRESS THE POWER BUTTON WHEN SCREEN IS BLACK or BLANK, BE PATIENT"
 * Support group: https://t.me/DroidianLinux

## Bugs and workarounds
* Camera not working, is a common issue on droidian. Some devices have camera working with waydroid. But does not work on sofia.
* Brightness is currently only adjustable via the applet on the appdrawer
