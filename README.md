# iOS 5 - 6 Hacktivation

## Features
* Untethered hacktivate iOS 5 - 6 devices
* Useful for bypassed A5 - A6 (X) devices
* Supports sideloading .ipa files with AppSync installed

## Usage
* Make sure target device has an untethered jailbreak
* Enter pwnDFU mode, boot an SSH ramdisk, SSH into the device, mount filesystems
* Replace original `/mnt1/usr/libexec/lockdownd` with this patched one
* Chmod it to 0755, reboot
* Enjoy!
