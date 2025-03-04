# 尔英 ITX i9-12900HK 主机黑苹果引导 [![OpenCore](https://img.shields.io/badge/OpenCore-0.9.7-blue)](https://github.com/acidanthera/OpenCorePkg)

> 🌍 **English Version Available** → [[Click Here]](./README_en.md) 

## 📦 项目简介
本仓库提供适用于尔英i9-12900HK ITX主机的黑苹果（Hackintosh）OpenCore引导文件支持macOS Sonoma系统当前更新至14.2.1版本

## 🚀 快速导航
[📋 硬件配置](#-硬件配置) | 
[💻 软件环境](#-软件环境) | 
[✅ 功能状态](#-功能状态) | 
[⚠️已知问题](#️已知问题)


## 📋 硬件配置
| **组件**| **品牌型号**| **规格参数**|
|--|--|--|
| CPU            | Intel Core i9-12900HK     | 主板集成Alder Lake-H (移动版处理器) |
| RAM            | Samsung DDR4              | 3200MHz 16GB×2          |
| Primary SSD    | Kioxia RC20               | M.2 NVMe PCIe 1TB       |
| Secondary SSD  丨Phantom HV2000 Pro     丨M.2 NVMe PCIe 1TB      丨
｜GPU            丨AMD Radeon RX5500XT     丨8GB GDDR6                丨
｜Wireless Card  丨Intel AX210            ｜WiFi6/BT5.3 (批次006)     |


## 💻 软件环境
- 🛠 OpenCore: v0.9.7
- 🍎 macOS: Sonoma v14.2.1


## ⚠️已知问题  
❗ HDMI音频输出异常



<summary>📌注意事项</summary>
BIOS设置建议：
- VT-d: Disabled ←必须关闭！
- CFG Lock: Disabled ←推荐禁用！
- Secure Boot: Disabled ←安全启动必须关闭！
