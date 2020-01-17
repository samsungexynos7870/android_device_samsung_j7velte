# OrangeFox Recovery Project for the Samsung Galaxy J7 Nxt

### How to build ###

```bash
# Create dirs
$ mkdir ofox ; cd ofox

# Init repo
$ repo init --depth=1 -u https://gitlab.com/OrangeFox/Manifest.git -b fox_9.0

# Clone my local repo
$ git clone https://gitlab.com/android_samsung_universal7870/manifest/android_manifest_samsung_j7velte.git -b orangefox .repo/local_manifests

# Sync
$ repo sync --no-repo-verify -c --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune -j`nproc`

# Build
$ mv device/samsung/j7velte/build_ofox.sh .
$ . build_ofox.sh j7velte
```
## Credits
2019 @Astrako

## Contact
Telegram support group: https://t.me/joinchat/D1Jk_VbieGBXOWZt2y8O7A

# Device info
The Samsung J7 Nxt (codenamed _"j7velte"_) is a mid-range smartphone from Samsung.

It was announced and released in July 2017.

## Device specifications

| Device       | Samsung Galaxy J7 Nxt                             |
| -----------: | :----------------------------------------------    |
| SoC          | Samsung Exynos 7870                                |
| CPU          | Octa-core, 1586 MHz, ARM Cortex-A53, 64-bit, 14 nm |
| GPU          | Mali-T830                                          |
| Memory       | 2GB (LPDDR3X)                                      |
| Shipped Android version | 7.0.0                                   |
| Storage      | 16GB eMMC 5.1 flash storage                        |
| Battery      | Removable Li-Po 3000 mAh                           |
| Dimensions   | 152.40 x 78.60 x 7.60 mm                           |
| Display      | 1280 x 720 (16:9), 5.5  inch                       |
| Rear camera 1 | 13MP, f/1.9                                       |
| Front camera  | 5MP                                               |

## Device picture

![Samsung J7 Nxt](https://i.imgur.com/HBYFBI8.jpg)
