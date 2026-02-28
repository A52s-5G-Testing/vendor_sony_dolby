# Sony Dolby Atmos / Camera Apps / Sony Apps Extras Repo

## DISCLAIMER
- Dolby & Sony apps and blobs are owned by Dolby™ and Sony™.

## How to Include?
- Inherit the extra.mk repo from your device as shown
```
$(call inherit-product, vendor/sony/dolby/dolby.mk)
```
- Inherit the BoardConfigDolby.mk from your BoardConfig as shown
```
include vendor/sony/dolby/BoardConfigDolby.mk
```
## Credits
- Thanks to **[@saku-bruh](https://github.com/saku-bruh)** for helping with various things.
- Thanks to **[@hellobbn](https://github.com/hellobbn)** for modifying needed libs.
- Thanks to **[@reiryuki](https://github.com/reiryuki)** for reference README.
- Thanks to everyone else who was involved in making this all work.
