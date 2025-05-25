# Roboto for Pixel OS

Does what it says.

## Modules

Here's an explanation of what prefix mean.

* [**`roboto`**](/modules/roboto) — simply replaces system fonts. Some Google apps will still use Google Sans. 
* [**`roboto-killgmsfont`**](/modules/roboto-killgmsfont) — replaces system fonts and kills internal GMS Font API Service to ensure Google apps rely on custom installed fonts.  

Module version indicates which OS version the module is designed for (e.g. v15.1 is for Android 15 QPR1). However, it should usually be compatible with the latest Android versions.

## Compatibility

This module is compatible with stock Pixel OS and other Pixel-like ROMs that use Google Sans or other fonts for the UI using the same implementation as stock one.  

____

Tested on stock Pixel OS (AP4A.250205.002) and helluvaOS (BP1A.250505.005). It is unlikely to work with vendor ROMs such as HyperOS or ColorOS.

## Credits

* [MrCarb0n/killgmsfont](https://github.com/MrCarb0n/killgmsfont) for logic of disabling GMS Font API Service.
