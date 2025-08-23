# Pi-Gen Image Packs
This repository contains pi images (RPi Images) for supported RPis

> [!IMPORTANT]
> **no guarantee that the packages are up-to-date and functional**
> (there is no influence on some things)

See the [releases](https://github.com/LizenzFass78851/pi-gen_imagepacks/releases) to download the releases

## armhf Update Packs
| Release | Link |
|:------------------:|:--------------:|
| Bullseye | [armhf-bullseye](https://github.com/LizenzFass78851/pi-gen_imagepacks/releases/tag/armhf-bullseye) |
| Bookworm | [armhf-bookworm](https://github.com/LizenzFass78851/pi-gen_imagepacks/releases/tag/armhf-bookworm) |
| Trixie | [armhf-trixie](https://github.com/LizenzFass78851/pi-gen_imagepacks/releases/tag/armhf-trixie) |

## arm64 Update Packs
| Release | Link |
|:------------------:|:--------------:|
| Bullseye | [arm64-bullseye](https://github.com/LizenzFass78851/pi-gen_imagepacks/releases/tag/arm64-bullseye) |
| Bookworm | [arm64-bookworm](https://github.com/LizenzFass78851/pi-gen_imagepacks/releases/tag/arm64-bookworm) |
| Trixie | [arm64-trixie](https://github.com/LizenzFass78851/pi-gen_imagepacks/releases/tag/arm64-trixie) |

### Build state: 
[![generate_products](https://github.com/LizenzFass78851/pi-gen_imagepacks/actions/workflows/generate_products.yml/badge.svg?branch=main)](https://github.com/LizenzFass78851/pi-gen_imagepacks/actions/workflows/generate_products.yml)

> [!NOTE]
> - The IMGs published there are split into 1.9 GB files each when the IMGs are bigger then 1.9 GB.
>   - Put these back together under Linux using the cut command.
>   - On Windows this is possible with 7zip.
> - This automation uses the source code from [pi-gen](https://github.com/RPi-Distro/pi-gen) and this repository contains the source code for pi-gen so that the automation can provide these packages for the above-mentioned systems
