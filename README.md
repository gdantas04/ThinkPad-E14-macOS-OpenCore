# OpenCore EFI for ThinkPad E14 Gen 1 (macOS 15 Sequoia)

This repository provides an **OpenCore EFI configuration** for the **Lenovo ThinkPad E14 Gen 1** to run **macOS 15 (Sequoia)**.  
The setup is tailored to achieve near-native macOS performance while maintaining stability and usability for daily use.

---

## 💻 Hardware Overview

| Component        | Specification                      | Status |
|------------------|------------------------------------|--------|
| Model            | ThinkPad E14 Gen 1                 | ✅     |
| CPU              | Intel Core i7 10th Gen (Comet Lake) | ✅     |
| SSD              | NVMe / SATA                        | ✅     |
| Audio            | Realtek ALC257                     | ✅     |
| Wi-Fi/Bluetooth  | Intel AX201 (requires itlwm/IntelBluetooth) | ⚠️ Partial |
| Ethernet         | Realtek RTL8111                    | ✅     |
| Trackpad/TrackPoint | PS2 + SMBus                      | ✅     |
| Camera & Mic     | Integrated                         | ✅     |
| Fingerprint      | Synaptics                          | ❌     |

---

## ✨ Features Working
- Graphics acceleration
- Brightness control with hotkeys  
- Audio (internal speakers, mic, and headphone jack)  
- Ethernet and Wi-Fi
- Bluetooth
- Sleep/Wake  
- Trackpad, TrackPoint, and keyboard (with function keys)  
- Battery status  

---

## 🚫 Not Working / Limitations
- Fingerprint reader   
- DRM content

