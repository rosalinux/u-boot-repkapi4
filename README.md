```
sudo dnf in arm-trusted-firmware-armv8 crust-firmware binutils-aarch64-linux-gnu gcc-aarch64-linux-gnu dtc
make repka_pi4_optimal_defconfig
export BL31=/usr/share/arm-trusted-firmware/sun50i_h6/bl31.bin
export SCP=/usr/share/crust-firmware/h6/scp.bin
```
