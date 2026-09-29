# LXX506-ORANGEFOX-RECOVERY
<img src = "https://wiki.orangefox.tech/api/wiki/banner.svg" width=500 >
> [!WARNING]
> **Read Carefully !!!**<br>
>
> This is not a recovery image (instead a boot image) and it must be flashed into the /boot partition (since it's a virtual A/B device with no recovery partition). 

### How to Install 
> [!NOTE]
> You must have a backup of the stock boot.img before proceeding !

<ins>**Steps:**</ins>
1. First of all the bootloader needs to be unlocked
2. Hold Vol UP + Power Key it open open a menu with 3 options (select Fastboot)
3. Once in fastboot enter the command `fastboot flash boot ofox.img`
<br>**(On this device booting the image directly isn't supported so we have to directly flash it, if anything goes wrong flash back the stock boot.img and report an issue)**
5. Enter `fastboot reboot recovery` to enter into the newly flashed recovery.
6. After your work is done, reboot to System from Recovery.
7. That's It

![LXX506](https://fdn2.gsmarena.com/vv/pics/lava/lava-blaze-pro-5g-1.jpg)

`For Device Info` - https://devcheck.app/devices/lava/lxx506
