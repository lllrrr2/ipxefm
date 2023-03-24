# ipxefm
a file manager for IPXE that supports booting templates for WIM, ISO, IMG, RAMOS, and ISCSI in both BIOS and UEFI environments. The script automatically detects the environment and uses different methods to boot WIM, ISO, IMG, and RAMOS. The files ipxe.bios and ipxe.efi are used for TinyPXE or PXELinux menu calls. The files in the nas directory are suitable for use in a soft router or Linux environment. The files ipxeboot.pcbios and ipxeboot.efi are universal boot files that can be used with various network boot loaders such as Synology and OpenWrt. The complete ipxefm.7z package can be downloaded from Tencent QQ group 146859089, which includes a demo of mini.wim.


IPXE文件管理器!支持启动WIM、ISO、IMG、RAMOS、ISCSI的网启模板(BIOS/UEFI) 
使用ipxe，自动判断legacybios和uefi(64位)环境，用不同方式启动WIM、ISO、IMG、RAMOS

ipxe.bios和ipxe.efi为tinypxe或pxelinux菜单调用专用文件(原版无嵌入脚本)

nas目录下的文件适合在软路由或linux系系统环境用

ipxeboot.pcbios和ipxeboot.efi为通用启动文件，各种网启启动器通用(群晖&openwrt等)

可以从腾讯QQ群146859089下载完整的ipxefm.7z包，里面包含演示的mini.wim


 
![image](https://github.com/zwj4031/ipxefm/blob/main/bin/ipxefm.gif)

 a video tutorial on how to use a file manager for IPXE that supports booting templates for WIM, ISO, IMG, RAMOS, and ISCSI in both BIOS and UEFI environments. The tutorial also explains how to add network card drivers to the IPXE environment if the PE cannot obtain an IP address due to a lack of network card drivers. The drivers can be added to the "drivers.7z" file located in the "app\inject\default" directory, or the driver package can be renamed to "drivers.7z" and placed in the same directory. The video tutorial can be found at https://www.bilibili.com/video/BV1Sf4y1x7ea.

应用视频https://www.bilibili.com/video/BV1Sf4y1x7ea

如果pe无法取得IP地址是因为缺少网卡驱动，可以加入你的驱动目录到app\inject\default下的   drivers.7z
或者直接把你的驱动包改名为drivers.7z
