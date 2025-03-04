## 尔英 ITX i9-12900HK 主机黑苹果引导 [![OpenCore](https://img.shields.io/badge/OpenCore-0.9.7-blue)](https://github.com/acidanthera/OpenCorePkg)

> 🌍 **English Version Available** → [[Click Here]](./README_en.md) 

### 📦 项目简介
本仓库提供了适用于尔英 G660I i9-12900HK ITX主板的黑苹果（Hackintosh）OpenCore引导文件。

### 📋 硬件配置

| **组件**| **品牌**|**型号**| **规格参数**|
|--|--|--|--|
| CPU | Intel|  Core i9-12900HK| 主板集成Alder Lake-H (移动版处理器)|
| 内存|三星 | - |3200MHz 16GB×2 DDR4|
| SSD①| 铠侠|  RC20| M.2 NVMe PCIe 1TB|
| SSD② |幻影|  HV2000 Pro|M.2 NVMe PCIe 1TB| 
|显卡| AMD|  Radeon RX5500XT| 8GB GDDR6| 
|无线网卡| Intel| Intel AX210| WiFi6/BT5.3 (批次006)| 


### 💻 软件环境
- 🛠 OpenCore: v0.9.7
- 🍎 macOS: Sonoma v14.2.1


### ⚠️已知问题  
❗ HDMI音频输出异常



### 📌注意事项
BIOS设置建议：
- VT-d: Disabled  ← 必须关闭！
- CFG Lock: Disabled  ← 推荐禁用！
- Secure Boot: Disabled  ← 安全启动必须关闭！
