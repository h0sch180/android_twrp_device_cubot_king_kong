TWRP Device Tree for Cubot KING KONG 
===========
Unoffical Build for MT6580 TWRP 
------------------

the way to do:
```
- repo init -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-6.0

- repo sync

- git clone
  https://github.com/h0sch180/android_twrp_device_cubot_king_kong device/CUBOT/KING_KONG

- . build/envsetup.sh

- lunch omni_KING_KONG-eng

- make -j# recoveryimage [# : no. of cpu core]
```


### Note:
**Touch does only work with sideload**
```
fastboot boot recovery.img
```
