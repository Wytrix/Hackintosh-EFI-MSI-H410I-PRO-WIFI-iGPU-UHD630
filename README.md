# Hackintosh-EFI-MSI-H410I-PRO-WIFI-iGPU-UHD630
EFI file for MSI motherboard with iGPU  

----------------------------------------------------------------  
2021.12.31 update OpenCore 0.6.4  

----------------------------------------------------------------  
## 版本信息（Version infomation）  
OpenCore：0.6.3  
macOS：macOS Big Sur 11.0.1（20B29）

## 配置信息（Hardware infomation）  

| 硬件部件（Hardware ）     | 型号（model）                      |
| :------------------------ | ---------------------------------- |
| 主板（Motherboard）       | MSI H410I Pro Wifi                 |
| CPU                       | Intel Core i3 10100                |
| 内存（Memory）            | Crucial 32GB（16GB * 2）           |
| 显卡（Graphics card）     | Intel UHD Graphics 630             |
| 硬盘（Disk）              | 铠侠（KIOXIA） RC10 500GB          |
| 声卡（Sound card）        | Realtek ALC1200                    |
| 以太网卡（Ethernet card） | Intel 1219V Gigabit LAN Controller |
| Wifi & Bluetooth          | Broadcom BCM94360CS2               |
## BIOS设置（BIOS Settings）

建议关闭VT-d、CFG Lock和SGX选项。

## 说明

默认config文件为DP接口输出，完全正常。

UHD630 4K HDMI.plist 为HDMI输出文件，未验证是否正常可用。



本EFI由此[EFI文件](https://github.com/cheneyxx/Hackintosh-10400-B460M-MORTAR)修改而来。
