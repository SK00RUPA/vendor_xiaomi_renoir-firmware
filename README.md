# vendor_xiaomi_renoir-firmware

Firmware images for Mi 11 Lite 5G (renoir), to include in custom ROM builds.


**Current version**: fw_RENOIRGlobal_V13.0.9.0.SKIMIXM_b0613244de_12.0

### How to use?

1. Install Git LFS by `git lfs install --skip-repo`
 
2. Clone this repo to `vendor/xiaomi/renoir-firmware` using `git lfs clone` command

3. Check if cloned images have a proper size - `modem.img` should be around 200MB

4. Include it from `BoardConfig.mk` in the device tree:

```
# Firmware
-include vendor/xiaomi/renoir-firmware/BoardConfigVendor.mk
```