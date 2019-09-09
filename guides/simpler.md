# Quicker and easier installation

## Prerequisites:
- EasyBox 904 xDSL
- Working internet connection (for example from a mobile)
- Computer with Windows 10, Linux or macOS

1. Downlaod this opened firmware image with SSH enabled by default: [opened Firmware sshAlwaysOn](https://github.com/ropasch/easybox904/raw/master/resources/fullimage_sshAlwaysOn.img)
2. Start the EasyBox normally and connect via LAN or WLAN to it. Browse to the webinterface at: `192.168.2.1` and confirm it's responding. Now press the reset button on the back for at least 5 seconds. The Box will reset completely and restart. Once again browse to the webinterface.
3. On the interface you are presented with the buttons, choose the last "Firmware Update" and select the downloaded fullimage file. Press install then confirm to flash.
4. You can now ssh into your easybox with `ssh root@192.168.2.1` 

see [1. Quick and easy](https://github.com/majuss/easybox904/blob/master/guides/simple.md) for the DSL/VOIP settings, or if you have problems with setting up your ssh-client
