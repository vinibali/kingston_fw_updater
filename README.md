Read-only, for updates please look at: https://gitlab.com/vinibali/kingston_fw_updater

# kingston_fw_updater
Kingston Firmware Updater Revision 2_0_5_build_010

Kingston's utility to update SSD firware on Sandforce based drives, created by James Huey.
Binary is from the Tinycore based V300 ISO updater(CD_V300_603.iso), the firmwares are coming from Kingston's official updaters. According to the ISO updater, both bin and firmware directories (hardcoded to the binary as well) are stored under the /custom/.

FW version and product chart:
507: KC300, SVP200
519: E100
525: V300
526: KC300, SH103
580: SHF
603: V300
608: V300 

Arch AUR package: https://aur.archlinux.org/packages/kingston_fw_updater
Youtube video: https://www.youtube.com/watch?v=Vg7NTqmWxAk

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

File structure in the AUR package, exactely the same like in the ISO updater.

/custom/bin -> /opt/kfu/bin
/custom/firmware -> /opt/kfu/firmware
/opt/kfu/bin/kfu  
/opt/kfu/firmware/507/22665_fw.vic  
/opt/kfu/firmware/507/22666_fw.vic  
/opt/kfu/firmware/507/22673_fw.vic  
/opt/kfu/firmware/507/22679_fw.vic  
/opt/kfu/firmware/507/22739_fw.vic  
/opt/kfu/firmware/507/22740_fw.vic  
/opt/kfu/firmware/507/22747_fw.vic  
/opt/kfu/firmware/507/22751_fw.vic  
/opt/kfu/firmware/507/22753_fw.vic  
/opt/kfu/firmware/507/22788_fw.vic  
/opt/kfu/firmware/507/22789_fw.vic  
/opt/kfu/firmware/507/22790_fw.vic  
/opt/kfu/firmware/507/22793_fw.vic  
/opt/kfu/firmware/507/22795_fw.vic  
/opt/kfu/firmware/507/22848_fw.vic  
/opt/kfu/firmware/507/27091_fw.vic  
/opt/kfu/firmware/507/27096_fw.vic  
/opt/kfu/firmware/507/27098_fw.vic  
/opt/kfu/firmware/507/27108_fw.vic  
/opt/kfu/firmware/507/27109_fw.vic  
/opt/kfu/firmware/507/27111_fw.vic  
/opt/kfu/firmware/507/27114_fw.vic  
/opt/kfu/firmware/507/27474_fw.vic  
/opt/kfu/firmware/507/27475_fw.vic  
/opt/kfu/firmware/507/27787_fw.vic  
/opt/kfu/firmware/507/27788_fw.vic  
/opt/kfu/firmware/507/27795_fw.vic  
/opt/kfu/firmware/507/27800_fw.vic  
/opt/kfu/firmware/507/29221_fw.vic  
/opt/kfu/firmware/507/29222_fw.vic  
/opt/kfu/firmware/507/29224_fw.vic  
/opt/kfu/firmware/519/25022_fw.vic  
/opt/kfu/firmware/519/25028_fw.vic  
/opt/kfu/firmware/519/25034_fw.vic  
/opt/kfu/firmware/519/25236_fw.vic  
/opt/kfu/firmware/519/25237_fw.vic  
/opt/kfu/firmware/519/25241_fw.vic  
/opt/kfu/firmware/525/22848_fw.vic  
/opt/kfu/firmware/525/27073_fw.vic  
/opt/kfu/firmware/525/27076_fw.vic  
/opt/kfu/firmware/525/27091_fw.vic  
/opt/kfu/firmware/525/27096_fw.vic  
/opt/kfu/firmware/525/27445_fw.vic  
/opt/kfu/firmware/525/27448_fw.vic  
/opt/kfu/firmware/525/27470_fw.vic  
/opt/kfu/firmware/525/27488_fw.vic  
/opt/kfu/firmware/525/27735_fw.vic  
/opt/kfu/firmware/525/27738_fw.vic  
/opt/kfu/firmware/525/27739_fw.vic  
/opt/kfu/firmware/525/27751_fw.vic  
/opt/kfu/firmware/525/27787_fw.vic  
/opt/kfu/firmware/525/27788_fw.vic  
/opt/kfu/firmware/525/29222_fw.vic  
/opt/kfu/firmware/526/22666_fw.vic  
/opt/kfu/firmware/526/22673_fw.vic  
/opt/kfu/firmware/526/22677_fw.vic  
/opt/kfu/firmware/526/22756_fw.vic  
/opt/kfu/firmware/526/22878_fw.vic  
/opt/kfu/firmware/526/22879_fw.vic  
/opt/kfu/firmware/526/22881_fw.vic  
/opt/kfu/firmware/526/22882_fw.vic  
/opt/kfu/firmware/526/22883_fw.vic  
/opt/kfu/firmware/526/27135_fw.vic  
/opt/kfu/firmware/526/27136_fw.vic  
/opt/kfu/firmware/526/27143_fw.vic  
/opt/kfu/firmware/526/27474_fw.vic  
/opt/kfu/firmware/526/27475_fw.vic  
/opt/kfu/firmware/526/27787_fw.vic  
/opt/kfu/firmware/526/27788_fw.vic  
/opt/kfu/firmware/526/27795_fw.vic  
/opt/kfu/firmware/526/29221_fw.vic  
/opt/kfu/firmware/526/29222_fw.vic  
/opt/kfu/firmware/526/29224_fw.vic  
/opt/kfu/firmware/580/33078_fw.vic  
/opt/kfu/firmware/580/33174_fw.vic  
/opt/kfu/firmware/603/22848_fw.vic  
/opt/kfu/firmware/603/27091_fw.vic  
/opt/kfu/firmware/603/27096_fw.vic  
/opt/kfu/firmware/603/27438_fw.vic  
/opt/kfu/firmware/603/27448_fw.vic  
/opt/kfu/firmware/603/27735_fw.vic  
/opt/kfu/firmware/603/27738_fw.vic  
/opt/kfu/firmware/603/27739_fw.vic  
/opt/kfu/firmware/603/27751_fw.vic  
/opt/kfu/firmware/603/27753_fw.vic  
/opt/kfu/firmware/603/27796_fw.vic  
/opt/kfu/firmware/603/27799_fw.vic  
/opt/kfu/firmware/603/29427_fw.vic  
/opt/kfu/firmware/603/29496_fw.vic  
/opt/kfu/firmware/603/29498_fw.vic  
/opt/kfu/firmware/603/33078_fw.vic  
/opt/kfu/firmware/603/33080_fw.vic  
/opt/kfu/firmware/603/33174_fw.vic  
/opt/kfu/firmware/603/33203_fw.vic  
/opt/kfu/firmware/603/33205_fw.vic  
/opt/kfu/firmware/603/33206_fw.vic  
/opt/kfu/firmware/608/33468_fw.vic  
/opt/kfu/firmware/608/33510_fw.vic  
/opt/kfu/firmware/608/33511_fw.vic  
/opt/kfu/firmware/608/33512_fw.vic  
/opt/kfu/firmware/608/33513_fw.vic  
/opt/kfu/firmware/608/33514_fw.vic  
/opt/kfu/firmware/608/33558_fw.vic  
/opt/kfu/firmware/608/33567_fw.vic  
/usr/bin/kfu -> /opt/kfu/bin/kfu
