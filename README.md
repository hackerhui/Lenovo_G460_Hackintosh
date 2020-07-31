# Lenovo_G460_Hackintosh

本项目为研究计算机原理使用

## 配置信息

型号：Lenovo G460  
处理器：Intel(R) Core(TM) i3 350M @ 2.27GHz  
主板芯片组：Intel HM55  
内存:4G DDR3 1066MHZ x2  
主硬盘：Samsung SSD 750 EVO 120GB  
数据盘：WDC WD5000BEVT-24A0RT0  
显卡：Nvidia GeForce GT310M  
声卡：Realtek ALC269  
有线网卡：Realtek RTL8103E PCI Express Fast Ethernet  
无线网卡：AR9285  

## 适用系统

MacOS Catalina 10.15.x
macOS Mojave 10.14.x
macOS High Sierra 10.13.x  
macOS Sierra 10.12.x  
OS X El Capitan 10.11.x  
OS X Yosemite 10.10.x  
OS X Mavericks 10.10.x  

## 已知问题（待解决）

电池驱动问题  

## 详细说明

引导：Clover r5094 传统BIOS引导  
显卡：免驱  
声卡：AppleALC.kext注入13驱动  
无线网卡：FakePCIID.kext与FakePCIID_AR9280_as_AR9285.kext仿冒驱动  
macOS 10.14以上版本需要修改机型，第二种办法是使用macOS patcher