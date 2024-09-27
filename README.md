## TWRP tree for Samsung Galaxy Tab A9+ 5G (gta9p)
Build your first custom recovery from TeamWin Recovery Project.


# Clone
    git clone https://github.com/MFO-STAGING/android_device_samsung_gta9p_vboot.git -b staging device/samsung/gta9p

# Build
    export ALLOW_MISSING_DEPENDENCIES=true; . build/envsetup.sh; lunch twrp_gta9p-eng; mka vendorbootimage

## Credits
- [cd-Crypton](https://github.com/cd-Crypton) who made this tree and wrote nearly all the code
- [nazephyrus](https://github.com/naden01) who fixed a build issue for vendor_boot
