Droidian on Xiaomi Redmi 9C/9C NFC (angelica/angelican)
========

Droidian is a GNU/Linux distribution based on top of Mobian, a Debian-based distribution for mobile devices. The goal of Droidian is to be able to run Mobian on Android phones.

## THE INSTRUCTIONS BELLOW WILL WIPE ALL THE DATA ON YOUR DEVICE

# Default password: 1234

## Installation
 * Download the latest build here: https://github.com/droidian-mt6765/droidian-images-angelica/releases
 * Unpack the zip file
 * Boot to fastboot
 * on Linux run flash_all.sh script:
    <pre><code>./flash_all.sh</code></pre>
 * on Windows run flash_all.bat
 * Reboot to system and "DO NOT PRESS THE POWER BUTTON WHEN SCREEN IS BLACK or BLANK, BE PATIENT"
 * Support group: https://t.me/DroidianLinux
 * Device specific support group: https://t.me/ut_angelica

## Bugs and workarounds
- Encryption is broken. Device is not unlockable after encryption is enabled.
* Bluetooth can be used via the terminal using bluetoothctl command or using blueman: sudo apt install blueman but does not work via the settings app.
* Signal strengh is reported at 1% but Mobile data and calls work just fine.
* When a headphone is plugged in it must be changed to be used manually in the settings.
* Device must be unplugged when it's booting.
* GPS does not work.
* Fingerprint does not work.
* Only one sim can be used.
