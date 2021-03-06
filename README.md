![Lenovo_Opencore](https://github.com/Hayo-Tee/Lenovo-Legion-Y520-OpenCore/blob/main/Lenovo_Opencore.jpg?raw=true)
# This is my OpenCore EFI for Lenovo Legion Y520.

### OS:
- macOS BigSur 11.6.1. ✅ tested
- macOS Monterey should work too ⚠ not tested yet
##
### OpenCore current version is 0.7.6.
##

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

## Note:
If your sleep mode still does not work, try disconnecting your USB mouse and keyboard before go to sleep, and read the [instructions](https://dortania.github.io/OpenCore-Post-Install/universal/sleep.html#preparations).

## To do:
- Buy a compatible Wi-Fi card and try to fix the Wi-Fi.
- Buy and try USB Type-C to HDMI.

## Credits:
- [adrianjagielak](https://github.com/adrianjagielak)
- [rizanw](https://github.com/rizanw)

## If something doesn't work for you, I can help you fix it.

### Please donate to me. This stimulates me to further develop, and to buy additional laptop accessories.

<a href="https://yoomoney.ru/to/4100117434738484"><img src="https://yoomoney.ru/transfer/balance-informer/balance?id=2325540116582991&key=944AD068AAC1CF47" width="100" alt="YooMoney Donate button" /> </a>
