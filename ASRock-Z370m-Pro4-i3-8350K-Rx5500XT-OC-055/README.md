# ASRock-Z370m-Pro4-i3-8350K-Rx5500XT-OC-055

## 配置情况

- 主板：ASRock-Z370m-Pro4
- CPU：i3-8350K
- 显卡：蓝宝石 Rx5500XT 8G
- 内存：海盗船 8GX2

## 安装版本

Catalina10.15.3 Beta版(19D49f)

## OpenCore版本

OpenCore-0.5.5-RELEASE

## BIOS设置

- BIOS版本：4.20

- DRAM → XMP

- 高级-CPU配置-CFG Lock → 禁用

- 高级-芯片组配置-Above 4G  Decoding → 启用

- 高级-芯片组配置-共享内存 → 256M

- 高级-芯片组配置-板载显卡多显示器支持 → 启用

- 高级-USB配置-XHCI Hand-off → 启用 

- 引导-快速启动 → 禁用

- 引导-CMS → 禁用

- F10 → 保存

## 工作状况

- 独显：正常 （5K+4K双屏）

- 集显：加速正常

- 声卡：正常(Realtek ALC892) 

- 无线：正常（BCM94331CD）

- 蓝牙：正常 （BCM94331CD）

- 随航：正常

- 关机/重启：正常

- 睡眠：正常

## 驱动/机型

- 核心：采用FakeSMC.kext/VirtualSMC.kext均可。

- 网卡：AirportBrcmFixup.kext/版本2.0.4

- USB：定制

- ALC：AppleALC.kext/版本1.4.3

- Lilu：Lilu.kext/版本1.3.9

- WhateverGreen：WhateverGreen.kext/版本1.3.5

- 机型：iMacPro1.1/iMac19.1均可

## 其他：

更新时间：2020-01-27

单独下载：

终端里面输入：

        1.cd 你指定文件夹
        2.svn checkout https://github.com/shuiyunxc/OC-EFI/trunk/ASRock-Z370m-Pro4-i3-8350K-Rx5500XT-OC-055/

A ASRock-Z370m-Pro4-i3-8350K-Rx5500XT-OC-055/XXX

A ASRock-Z370m-Pro4-i3-8350K-Rx5500XT-OC-055XXXX

.

.

.

A ASRock-Z370m-Pro4-i3-8350K-Rx5500XT-OC-055/XXXXX


完成后，就在指定文件夹有你下载的文件。
