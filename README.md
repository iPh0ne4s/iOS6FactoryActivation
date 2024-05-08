# iOS6FactoryActivation
Untethered factory activate iOS 6 iDevices.

## Usage
* SSH into target iDevice.
* Replace the original `/usr/libexec/lockdownd` (or `/mnt1/usr/libexec/lockdownd` if using SSH ramdisk) with this patched one.
* Change its permission to 0755 (very important).
* Reboot.
