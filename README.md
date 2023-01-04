## Recovery Device Tree for the Samsung Galaxy Z Flip (Snapdragon)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_bloomq-eng
make recoveryimage
```

Kernel source:
https://github.com/mohammad92/android_kernel_samsung_bloomq
