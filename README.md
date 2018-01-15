TWRP device tree for Xiaomi Redmi 5 (rosy)
========================================================

To build:

```sh
make clean
. build/envsetup.sh
lunch omni_rosy-userdebug
make recoveryimage -j16


For building TWRP for MSM8953 models only.
