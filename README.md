# Septentrio RxTools

UNOFFICIAL Debian packaging of Septentrio RxTools.

## Install

1. Download .deb package from [Releases](../../releases).
2. Install .deb package:
```sh
sudo apt update
sudo apt install "$PWD"/rxtools*.deb
```
3. Add current user to dialout group to access serial devices:
```sh
sudo usermod -aG dialout "$USER"
```
4. Reboot or logout/login.
