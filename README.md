# EFI-FOR-RAPTOR-LAKE-13TH-14TH-GEN-LAPTOP
A personally tested and verified OpenCore EFI built specifically for Intel 13th and 14th Gen Raptor Lake desktop systems.
This configuration provides a stable, near-native macOS experience, whether you use an integrated GPU or a discrete one.

✨ Features

✅ Fully Working macOS Installation — Tested successfully on Ventura, Sonoma, and Sequoia.

⚙️ Optimized for 13th & 14th Gen Only — Tailored for Raptor Lake / Raptor Lake Refresh CPUs.

💡 Functional iGPU with Full Graphics Acceleration — iGPU spoofed for macOS compatibility and hardware acceleration.

🚫 Optional dGPU Disable (SSDT-dGPU-Off) — Works perfectly with or without discrete GPUs.

🎧 Audio Working — Clean and stable with AppleALC layout injection.

🔋 Backlight Control Fixed — Smooth brightness adjustment on compatible displays.

🧠 USB Ports Properly Mapped — Sleep/wake, power, and input devices behave natively.

📶 Wi-Fi & Bluetooth Working — Configured and tested with compatible Intel and Broadcom chipsets.

⌨️ Keyboard / Input Devices Fully Functional — VoodooPS2 & USB input stack configured.

🧩 Stable PlatformInfo Configuration — Generated via GenSMBIOS; ready for iMessage, FaceTime, App Store, and more.

🧬 Compatibility

CPUs: Intel Core 13th Gen & 14th Gen (Raptor Lake / Raptor Lake Refresh)

Graphics:

iGPU (UHD 770 → spoofed as UHD 630 for full acceleration)

dGPU optional (disabled in macOS via SSDT-dGPU-Off if unsupported)

💽 macOS Versions Tested

macOS Ventura

macOS Sonoma

macOS Sequoia (Beta)

All builds tested successfully with graphics acceleration, Wi-Fi/Bluetooth, and native sleep/wake functionality.

🧰 Setup Notes

Generate your own serials (SystemSerialNumber, MLB, ROM, SystemUUID) using GenSMBIOS
.

Ensure SSDT-dGPU-Off.aml is enabled if using an unsupported or NVIDIA GPU.

Works best with clean installers from Apple using Dortania’s recovery image method
.

🧠 Credits

OpenCore Team

Dortania Guides

Acidanthera Projects

Bumblebee Project for dGPU power-off inspiration

Community testers and developers for Raptor Lake support

⚠️ Disclaimer

This EFI is released for educational and experimental use.
Tested personally and verified to work on Intel 13th and 14th Gen desktops.
Use responsibly, and always customize serials before logging into Apple services
