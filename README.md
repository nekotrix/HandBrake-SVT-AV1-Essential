# HandBrake-SVT-AV1-Essential
### Purpose of the project
This project contains the patches needed to replace SVT-AV1 with SVT-AV1-Essential inside HandBrake.\
In addition, using GitHub Actions, nightly build of patched executables will be released.
### Instructions to patch/build
* Run ```patch.sh``` on linux. The script will patch the previously cloned HandBrake repo. If you want to also clone it you can use ```--clone``` argument.
* Compile for the desired platform using the commands provided on the HandBrake wiki ([BSD](https://handbrake.fr/docs/en/latest/developer/build-bsd.html), [Linux](https://handbrake.fr/docs/en/latest/developer/build-linux.html), [Mac](https://handbrake.fr/docs/en/latest/developer/build-mac.html), [Windows](https://handbrake.fr/docs/en/latest/developer/build-windows.html))
### Downloads and Build Status
| Operating System  | Download        | Build Status *1 |
| ----------------- | --------------- | ------------- |
| Windows           | [Download](https://github.com/nekotrix/HandBrake-SVT-AV1-Essential/releases/tag/win) | [![Windows Build](https://github.com/nekotrix/HandBrake-SVT-AV1-Essential/actions/workflows/nightly-win.yml/badge.svg)](https://github.com/nekotrix/HandBrake-SVT-AV1-Essential/actions/workflows/nightly-win.yml)  |
| macOS             | [Download](https://github.com/nekotrix/HandBrake-SVT-AV1-Essential/releases/tag/mac) | [![macOS build](https://github.com/nekotrix/HandBrake-SVT-AV1-Essential/actions/workflows/nightly-mac.yml/badge.svg)](https://github.com/nekotrix/HandBrake-SVT-AV1-Essential/actions/workflows/nightly-mac.yml)  |
| Linux (Flatpak)   | [Download](https://github.com/nekotrix/HandBrake-SVT-AV1-Essential/releases/tag/flatpak) | [![Flatpak Build](https://github.com/nekotrix/HandBrake-SVT-AV1-Essential/actions/workflows/nightly-flatpak.yml/badge.svg)](https://github.com/nekotrix/HandBrake-SVT-AV1-Essential/actions/workflows/nightly-flatpak.yml) |
| Ubuntu            | [Download](https://github.com/nekotrix/HandBrake-SVT-AV1-Essential/releases/tag/ubuntu) | [![Ubuntu Build](https://github.com/nekotrix/HandBrake-SVT-AV1-Essential/actions/workflows/nightly-ubuntu.yml/badge.svg)](https://github.com/nekotrix/HandBrake-SVT-AV1-Essential/actions/workflows/nightly-ubuntu.yml) |
| Arch Linux        | [Download](https://github.com/nekotrix/HandBrake-SVT-AV1-Essential/releases/tag/arch) | [![Arch Linux Build](https://github.com/nekotrix/HandBrake-SVT-AV1-Essential/actions/workflows/nightly-arch.yml/badge.svg)](https://github.com/nekotrix/HandBrake-SVT-AV1-Essential/actions/workflows/nightly-arch.yml) |

*1 Please note that if a build is marked as failed, previous builds may still be available for download!
### Testing
Help for testing on all platforms would be helpful.
### Contributing
I'm looking for people more acquainted than I am with Handbrake's code to implement some -Essential features to the GUI like support for the `--quality` presets
### Special thanks
* [njooobe (HandBrake-SVT-AV1-PSY)](https://github.com/njooobe/HandBrake-SVT-AV1-PSY) — direct upstream repository.
* [Uranite (HandBrake-SVT-AV1-HDR)](https://github.com/Uranite/HandBrake-SVT-AV1-HDR) — CI workflow, toolchain, and patch fixes.
* [vincejv (Docker container for HandBrake)](https://github.com/vincejv/docker-handbrake) — inspiration for some patches.
