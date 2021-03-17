# Dell Optiplex 3050 EFI
Dell Optiplex 3050 EFI folder for vanilla hackintosh with clover.

This works with macOS Catalina 10.15 on Dell Optiplex 3050 micro (i5-7500T).

**Working:**
* Audio Input/Output
* Hdmi (with audio)
* All USBs
* Ethernet
* Bluetooth
* Wifi. I have not enabled it because I don't need it but you can enable it using this https://openintelwireless.github.io (It's the same project I used to enable the bluetooth)

**Not working:**
* Wake from sleep. This is a common problem with intel HD630, I haven't found a solution yet other than disabling sleep from macOS system settings.

**Not tested:**
* Displayport. You might get the pink screen problem but it's an easy fix, google it.

### Important
If you want working iMessage and FaceTime you must generate new Serial Number and SmUUID with Clover Configurator in the SMBIOS section.
