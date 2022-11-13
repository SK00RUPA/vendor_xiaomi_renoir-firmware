# android_vendor_xiaomi_renoir-firmware

Firmware images for Mi 11 Lite 5G (renoir), to include in custom ROM builds.

**Current version**: fw_RENOIRGlobal_V13.0.4.0.SKIMIXM_e66cdbaec5_12.0

### How to use?

1. Clone this repo to `vendor/xiaomi/renoir-firmware`

2. Include it from `BoardConfig.mk` in device or common tree:

```
# Firmware
-include vendor/xiaomi/renoir-firmware/BoardConfigVendor.mk
```