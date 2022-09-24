# J7-prime-stereo-sound-mod
* This audio modification module enables the earpiece to work along with the main speaker, thereby giving a stereo effect.

## DISCLAIMER: Read this carefully.
* The warranty of your device is now void and I'm not responsible for any damage you made to your device. You have been warned!

## FEATURES
* This sound mod boosts the main speaker slightly and sets the earpiece to the max volume possible without damaging them.
* This module creates backup of original `mixer_paths.xml` during installation and can be found in `system/etc`, file ending with .bak0

## SUPPORTED DEVICES
* Samsung Galaxy J7 Prime (Exynos)

## PREREQUISITES
* A rooted J7 Prime with TWRP installed.

## INSTRUCTIONS
* Reboot to recovery
* Install `TWRP_Stereo_sound_mod_J7_Prime.zip`
* Reboot system

## RESTORING DEFAULT AUDIO CONFIG
* Reboot to recovery
* Install `TWRP_Restore_default_mixer_J7_Prime.zip`
* Reboot system

### Note:
* Alternatively, you can rename `mixer_paths.xml.bak0` located in `system/etc` as `mixer_paths.xml`.
* Don't forget to change the file permissions to 644 (rw- r-- r--), else you may end up in a bootloop. 
* If that happens, you'll need to go to the files and change their permissions via file manager in TWRP.
