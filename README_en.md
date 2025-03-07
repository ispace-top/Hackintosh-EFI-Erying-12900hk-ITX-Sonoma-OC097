## Hackintosh OpenCore Guide for Erying ITX i9-12900HK System [![OpenCore](https://img.shields.io/badge/OpenCore-1.0.2-blue)](https://github.com/acidanthera/OpenCorePkg)

> 🌍 **中文版本** → [[点击此处]](./README.md) 

### 📦 Project Overview  
This repository provides OpenCore bootloader configurations for Erying G660I i9-12900HK ITX motherboards to run macOS (Hackintosh).

### 📋 Hardware Specifications

| **Component** | **Brand** | **Model** | **Specifications** |
|---------------|-----------|-----------|--------------------|
| CPU           | Intel     | Core i9-12900HK | Integrated Alder Lake-H (Mobile Processor) |
| RAM           | Samsung   | -         | 3200MHz 16GB×2 DDR4 |
| SSD①          | Kioxia    | RC20      | M.2 NVMe PCIe 1TB |
| SSD②          | Phantom   | HV2000 Pro |M.2 NVMe PCIe 1TB  |
| GPU          |AMD       | Radeon RX5500XT |8GB GDDR6 |
| Wireless Card | Intel    | AX210       | WiFi6/BT5.3 (Batch:006)|


### 💻 Software Environment
- 🛠 OpenCore: v1.0.2
- 🍎 macOS: Sonoma v14.6.1


### ⚠️ Known Issues  
❗ HDMI Audio Output Malfunction



### 📌 Important Notes  
Recommended BIOS Settings:
- VT-d: Disabled ← Must be disabled!
- CFG Lock: Disabled ← Recommended to disable!
- Secure Boot: Disabled ← Secure Boot must be disabled!
