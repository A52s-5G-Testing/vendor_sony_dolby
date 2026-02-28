# Sony Dolby Atmos

## DISCLAIMER
- Dolby & Sony apps and blobs are owned by Dolby™ and Sony™.

## How to Include?
- Inherit the dolby.mk repo from your device as shown
```
$(call inherit-product, vendor/sony/dolby/dolby.mk)
```
- Inherit the BoardConfigDolby.mk from your BoardConfig as shown
```
include vendor/sony/dolby/BoardConfigDolby.mk
```
- Inherit the codecs in your media_codecs file in vendor *(depends on device what file is being loaded. Check logcat for more information)*
```
<Include href="media_codecs_dolby_audio.xml" />
```

**Example commit: [here](https://github.com/realahnet/device_oneplus_sm8650-common/commit/dbae2e67636e669ae311db8f096a2c63974dda46)**
#
# Credits
- Thanks to **[@saku-bruh](https://github.com/saku-bruh)** for helping with various things.
- Thanks to **[@hellobbn](https://github.com/hellobbn)** for modifying needed libs.
- Thanks to **[@reiryuki](https://github.com/reiryuki)** for reference README.
- Thanks to everyone else who was involved in making this all work.
