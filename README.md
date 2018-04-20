# kingston_fw_updater
Kingston Firmware Updater Revision 2_0_5_build_010

Kingston's utility to update SSD firware on Sandforce based drives, created by James Huey.
Binary is from the Tinycore based V300 ISO updater(CD_V300_603.iso), the firmwares are coming from Kingston's official updaters. According to the ISO updater, both bin and firmware directories (hardcoded to the binary as well) are stored under the /custom .

FW version and product chart:
507: KC300, SVP200
519: E100
525: V300
526: KC300, SH103
580: SHF
603: V300
608: V300 

Arch AUR package: https://aur.archlinux.org/packages/kingston_fw_updater

Needed 32bit (!) libraries:

libbz2.so.1.0
libc.so.6
libdl.so.2
libexpat.so.1
libfontconfig.so.1
libfreetype.so.6
libgcc_s.so.1
libglib-2.0.so.0
libharfbuzz.so.0
libICE.so.6
libjpeg.so.62
libm.so.6
libpcre.so.1
libpng12.so.0
libpng16.so.16
libpthread.so.0
librt.so.1
libSM.so.6
libstdc++.so.6
libuuid.so.1
libX11.so.6
libXau.so.6
libxcb.so.1
libXdmcp.so.6
libXext.so.6
libXrender.so.1
libz.so.1

Optional 64bit lib:
ld-linux.so.2
