# This is my OpenCore EFI for Lenovo Legion Y520.

### OS:
- macOS BigSur 11.6.1. ✅ tested
- macOS Monterey should work too ⚠ not tested yet

### OpenCore current version is 0.7.6.


## Working almost everything:
- iGPU
- Audio
- Camera
- Keyboard & touchpad
- Brightness control
- Battery status
- Sleep Mode
- USB Type-C
- USB 2/3 port
- Enthernet LAN
- SD card reader
- Dualboot with Windows 10

## Not working:
- dGPU (NVidia GTX1050, NVidia GTX1050 TI, NVidia GTX1060)
- HDMI port
- Build-in WiFi & Bluetooth

## Not tested:
- HDMI port not tested
- Type-C Video. But should work too
- I haven't tried other Wi-Fi cards yet. I use USB Wi-Fi and LAN


## BIOS configuration:

    Set BIOS to defaults.
    Set Graphic Device to Integrated Graphics.
    Enable Intel Virtualization Technology.
    UEFI boot is enabled.
    Secure boot is disabled.
    Fast boot is disabled.
    SATA mode is set to AHCI.

## Note
If your sleep mode still does not work, try disconnecting your USB mouse and keyboard before disconnecting and read the [instructions](https://dortania.github.io/OpenCore-Post-Install/universal/sleep.html#preparations).

## To do:
- Buy a compatible Wi-Fi card and try to fix the Wi-Fi.
- Buy and try USB Type-C to HDMI.

## Credits:
- [adrianjagielak](https://github.com/adrianjagielak)
- [rizanw](https://github.com/rizanw)
