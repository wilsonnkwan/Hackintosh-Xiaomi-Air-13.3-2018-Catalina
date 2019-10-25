# Hackintosh-Xiaomi-Air-13.3-2018-Catalina
Hackintosh - Catalina for Xiaomi Notebook Air 13.3 (2018)

I directly copied from Johnnync13's repo, please give him credit.
Please do not submit issues here, it will be ignored because I am not trained to troubleshoot. This repo serves two purposes, primarily a record for myself and secondarily, a testimony to tell you that johnnync13's repo works.
Refer to https://github.com/johnnync13/Xiaomi-Mi-Air
You should refer to his repo for the latest updates.

The EFI will work for Catalina, however, do note that Catalina do not have drivers for USB Wifi or USB LAN, so my suggestion to you is to get a USB Wifi that is in the Chris1111's https://github.com/chris1111/Wireless-USB-Adapter-Clover

# Usage for Clover EFI
Install latest Clover from https://sourceforge.net/projects/cloverefiboot/
copy the CLover EFI folder as "EFI" into the EFI

# Usage for ALCPlugFix
You can run the install.command directly but it will keep asking you for Password because of the sudo command.
An easier way is to do "sudo -i" to escalate yourself to root user. Then run the install.command.
This is to fix your headphone jack. If you plug in your headphone and the sound is muffled, run this. You most likely will face the situation.

#MacOS Versions Supported:
High Sierra
Mojave
Catalina(Beta)

#CPUs Supported:
I7-8550u
I5-8250u

#What is Working
Native power management
Intel GPU
Audio (AppleALC)
TrackPad
HDMI video and audio
USB 3.0
Brightness keys
Usb speed
Built-in camera (Doesn't work for the i7 version. Not sure why)
Built-in mic

#What is Not Working
Wifi & Bluetooth Intel
