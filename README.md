### Razer Edge "Lite" (Razer Phone 2 handheld console conversion)

This is a full conversion mod to turn the Razer Phone 2 into a fully functional handheld console

This mod includes LineageOS, Magisk, Dolby Atmos drivers, as well as various performance tweaks to support better software emulation. It's designed for use with the Razer Kishi V2, but will work with any other android controller.

### Prerequisites
- LineageOS Aura build (20.0-20240119 as of today) from https://download.lineageos.org/devices/aura/builds
- LineagoOS Recovery (boot.img provided with Aura build)
- ADB Platform Tools (Windows, Linux, and Mac versions available in 1.2.1)
- ~ Alternatively you can find them here https://developer.android.com/tools/releases/platform-tools
- Magisk APK (available above, or at https://github.com/topjohnwu/Magisk/releases)
- DolbyAtmos-RazerPhone2-MagiskModule (v7.8 provided)
- Mesa Turnip Adreno Driver for Yuzu Emulator (provided)
- Logo+ apk (Logo+ v1.0.13 provided)

### Get Started
- Follow the LineageOS installation guide found here: https://wiki.lineageos.org/devices/aura/install/
- After installation, launch the recovery again, and install Magisk.apk, as well as Logo+ as an update (from ADB)
- Once rebooted, launch Magisk and follow the installation instructions to get Magisk running properly
- After Magisk is successfully installed, install the "DolbyAtmos-RazerPhone2-MagiskModule.zip" module
- Next, run Logo+ from home screen, and allow root access using Magisk, and set it to permanent
- ~ I'd recommend disabling any power saving proceedures for Logo+ as it may interfere with the way it runs
- Install GLTools and SmartPack for performance modifications (located in RazerLite_SetupFiles.X.zip\Software)

### Stop here for the ultimate Razer Phone 2 (phone) experience
- You can technically stop here if you just want to have a fully upgraded Razer Phone 2
- Continue the guide below for the rest of the handheld conversion

### Finishing touches
- Finally, install Console Launcher (or whatever launcher you prefer), found at https://www.consolelauncher.app/
- For maximum compatibility and build finish, I recommend this case (not required):
- ~https://www.amazon.com/gp/product/B07JN6V3K5/
- Remove plastic inserts in Razer Kishi v2, and place phone and case in the Kishi. 

### Yuzu Setup (Nintendo Switch)
- Install Yuzu (Nintendo Switch emulator)
- Flash the Nintendo Switch firmware (Found online, I cannot provide)
- Navigate to the GPU driver manager, and install "Mesa Turnip Adreno Driver v23.2.0" (provided)
- Provide Switch roms (your own), and play your games! :)

### Fallback (If any issues occure)
- If you have any issues during installation, Razer provides factory images on their website here: https://developer.razer.com/razer-phone-dev-tools/factory-images/
- For help on installing the original factory image, you can refer to their instructions here: https://developer.razer.com/razer-phone-dev-tools/general-instructions/

### Changelogs
- Added GLTools and SmartPack apk files in update 1.2.1
