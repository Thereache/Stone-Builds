# Stone-Builds

Roms for Redwood By @Thereache any problem tag me in my chat
(https://t.me/thereachebuildchat)

# Flashing Guide
## Recovery Method
1. Unlock Bootloader
2. Reboot Recovery
3. wipe dalvik,cache,internal storage 
4. Flash Rom Zip
5. Flash Recovery On Remdisk
6. Format Data
7. Reboot Recovery
8. Flash Magisk.zip(optional),Flash Gapps (optional)
9. Format Data & Reboot to System 
## Fastboot Method
1. Unlock Bootloader
2. Reboot Fastboot
3. Flash boot.img -->> fastboot flash boot boot.img
4. Flash dtbo.img -->> fastboot flash dtbo dtbo.img (Optional)
5. Flash vendor_boot.img -->> fastboot flash vendor_boot vendor_boot.img
6. Reboot Recovery -->> fastboot reboot recovery
7. In the recovery, press Apply Update
8. It will wait for sideload
9. Sideload desired ROM file using -->> adb sideload < ROM >

# Enjoy Your Flashing 
