# incognito
Wipes some personal information from your Nintendo Switch by removing it from PRODINFO (CAL0).

NOTE: Atmosphere blocks writes to PRODINFO, so you must use ReiNX, SX OS, or a custom KIP to install this. Once installed, you can switch back to Atmosphere.

## Purpose
a) It enables your switch to go online while worrying slightly less about a ban.
b) It prevents malicious homebrew applications from stealing your personal certificate.

## Disclaimers
* This application does not remove all personal information from your Switch, and should not be treated as a true preventative measure against getting banned.

* ALWAYS have a NAND backup. I am not responsible for any bricks or bans. Use at your own risk, as this is an experimental program.

* This application backs up your PRODINFO to the SD card, as `backup/PRODINFO.bin` You should keep this backup in a more secure location, and not leave it on the SD card where it could be subject to corruption or be read by malicious applications.

## License
* Incognito - GNU General Public License version 2 - by https://github.com/blawar

* icon.jpg (from Chromium/ui/webui/resources/images/incognito_splash.svg@0a1feb6e910e7e0befe6a37d148e6b3db5f8b9be) - The BSD 3-Clause License - Copyright 2015 The Chromium Authors. All rights reserved.
