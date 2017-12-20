# Mac-OS-X-High-Sierra

**create-iso.sh** is just an adapted script to create an ISO image from the Apple App Store Mac OS X High Sierra installer download. So one must have previously downloaded the installer before running the script.

**chromium.api.plist** is the file i use to load, at boot time, the needed Google API Keys in order to give Chromium browser the ability to sync with Gmail accounts and other features. The file is located at */Users/<username>/Library/LaunchAgents*. To get the needed Google API keys one must follow those instructions [https://www.chromium.org/developers/how-tos/api-keys](https://www.chromium.org/developers/how-tos/api-keys)
