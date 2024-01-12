# 技嘉 Z790M AORUS ELITE AX 黑苹果 OpenCore EFI

![image](ScreenShot/Gigabyte-Z790M-Aorus-Elite-AX.jpg)

### [English](https://github.com/hackintosh-efi/ASRock-DeskMini-310)

### OpenCore

[OpenCore 0.9.7](https://github.com/acidanthera/OpenCorePkg)

### 可安装系统

- macOS Monterey 12.x 
- macOS Ventura  13.x 
- macOS Sonoma  14.x 


### 硬件

- BIOS版本: F5  2023-08-28
- 主  板: Gigabyte Z790M Aorus Elite AX
- 处理器: 英特尔 13代 i5-13600KF
- 独   显: Gigabyte Radeon RX 6600 EAGLE 8G
- 内   存: 三星 32G（16G*2）DDR5 5600 Mhz B-die
- 固   态: Intel S4520 960G Windows 11
- 固   态: Intel S4520 960G MacOS Sonoma
- 声   卡: 瑞昱 ALC1220
- 有   线: 瑞昱 RTL8125 2.5GB
- 无   线: Intel AX211

### BIOS设置

```
Settings
  |-- IO Ports
      |-- Above 4G Decoding: Enabled
      |-- IOAPIC 24-119 Entries: Disabled
      |-- Super IO Configuration
          |-- Serial Port: Disabled
      |-- USB Configuration
          |-- XHCI Hand-off: Enabled 
          |-- Port 60/64 Emulation: Disabled
      |-- SATA Configuration
          |-- SATA Controllers): Enabled 
  |-- Miscellaneous 
      |-- VT-D: Enabled    
Boot 
  |-- CFG Lock: Disabled
  |-- Fast Boot: Disable Link
  |-- CSM Support: Disabled
  |-- Secure Boot
      |-- Secure Boot: Disabled
```



### 注意事项

 - 安装完成后请使用 [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools/releases) 生成自己的三码
 - 如需使用没有小核心的CPU，必须取消勾选配置文件中Kernel--ProvideCurrentCpuinfo选项
 - 请使用电源键进行睡眠唤醒
 - 此EFI中的英特尔无线网卡驱动[AirportItlwm.kext](https://github.com/OpenIntelWireless/itlwm/releases)仅适用于 MacOS 14 Sonoma,安装其它版本请自行下载替换此驱动
 - 英特尔无线网卡无法使用隔空投送等功能



### 联系我们

- QQ群: 23304408

![image](ScreenShot/QRCode.png)