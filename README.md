# Precision-M6800-EFI
An OpenCore EFI for the Dell Precision M6800 for macOS Monterey.

## Specs

| Component | Specification                |
|-----------|------------------------------|
| CPU       | Intel Core i7-4800MQ Haswell |
| GPU       | AMD FirePro M6100 Mobility   |
| RAM       | 8GB + 4GB DDR3L @ 1600MHz    |
| Storage   | 256GB SATA SSD               |
| Display   | 1920x1080 @ 60Hz             |
| Audio     | Realtek ALC292               |
| Wi-Fi     | Intel Wireless AC 7260       |
| Ethernet  | Intel Ethernet I217 LM       |

---

### What works
- Keyboard
- Mouse Stick
- dGPU
- Wi-Fi
- Ethernet
- Internal Speakers
- Internal Mic
- Sleep
### What partially works
- Touchpad (a bit hard to control)
- Bluetooth (mostly works but unstable, acts weird after sleep)
- Brightness (works up to 50% and past that it starts to act weird)
### What doesn't work
- Webcam
- iGPU
- iServices
### What's untested
- DRM
- External audio output
- External audio input

---
> [!NOTE]
> Make sure to disable "Switchable Graphics" in BIOS.
