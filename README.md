## Razer Edge "Lite" (Razer Phone 2 handheld console conversion)

This is a full conversion mod to turn the Razer Phone 2 into a fully functional handheld console

This mod includes LineageOS, Magisk, Dolby Atmos drivers, as well as various performance tweaks to support better software emulation. It's designed for use with the Razer Kishi V2, but will work with any other android controller.

### Prerequisites
- LineageOS Aura build (20.0-20240119 as of today)
- LineagoOS Recovery (boot.img provided with Aura build)
- ADB Platform Tools (Windows build provided above, Linux and Mac versions available on https://developer.android.com/tools/releases/platform-tools)
- Magisk APK (available above, or at https://github.com/topjohnwu/Magisk/releases)
- DolbyAtmos-RazerPhone2-MagiskModule (v7.8 provided above)
- GPU Drivers for Yuzu (Nintendo Switch Emulator) - Mesa Turnip Adreno Driver based on v23.2.0-devel for A7XX
- Logo+ apk (Logo+ v1.0.13 provided)

### Get Started
- Follow the LineageOS installation guide found here: https://wiki.lineageos.org/devices/aura/install/
- After installation, launch the recovery again, and install Magisk.apk, as well as Logo+ as an update (from ADB)
- Once rebooted, launch Magisk and follow the installation instructions to get Magisk running properly
- After Magisk is successfully installed, install the "DolbyAtmos-RazerPhone2-MagiskModule.zip" module
- Next, run Logo+ from home screen, and allow root access using Magisk, and set it to permanent
- Finally, install Console Launcher (or whatever launcher you prefer), found at https://www.consolelauncher.app/

### Finishing touches
- For maximum compatibility and build finish, get this case (not required) https://www.amazon.com/gp/product/B07JN6V3K5/
- Install trimmed magnet strips on the inside of either wall of the case (top and bottom of device)
- Remove inserts from Razer Kishi, and attatch magnet strips in their place (with trim for USB-C port)
- Place Razer Phone 2 inside of case and insert it in to the Razer Kishi V2

### Yuzu Setup (Nintendo Switch)
- Install Yuzu (Nintendo Switch emulator)
- Flash the Nintendo Switch firmware (Found online, I cannot provide)
- Navigate to the GPU driver manager, and install "Mesa Turnip Adreno Driver v23.2.0" (provided above)
- Provide Switch roms (your own), and play your games! :)
