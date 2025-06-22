# device-features-emerald.xml

This repository contains the `device_features` XML file specifically for the POCO M6 Pro 4G, codenamed **emerald**.

## 📄 File Location

The `emerald.xml` file is intended to be placed in:

system/product/etc/device_features/emerald.xml

## 📱 Device Information

- **Device Name**: POCO M6 Pro 4G  
- **Codename**: `emerald`  
- **Chipset**: MediaTek Helio G99 Ultra  

## 🔧 Purpose

This file defines hardware and software feature flags used by the Android system to configure behavior specific to the device.  
It is essential for proper functionality and compatibility of system components, particularly within AOSP-based ROMs or custom builds.

## 📥 Usage

1. Clone or download this repository.
2. Copy `emerald.xml` into your Android source tree:

system/product/etc/device_features/

3. Ensure your build system includes this file during compilation for the `emerald` target.

## ⚠️ Notes

- Make sure the path and filename match exactly for proper integration in the build system.

## 📃 License

This project is licensed under the [MIT License](LICENSE).

---

[Fakeri](https://github.com/fakerieh)
