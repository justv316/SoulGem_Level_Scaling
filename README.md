# Soul Gem Level Scaling

# Changelog
1. 1.0
	a. Initial Release
2. 1.0a
	a. Fixed initial Release
3. 1.1
	a. Added MCM functionality for player to configure the scaling factor that the Soul Gem level scaling uses.

## Description
Automatically Scales Soul Gem power based on player level. This is accomplished using a quest script running in the background that runs once per level up. The quest script utilizes MadAborModdings ObScript Extender to set the related game settings.

As of 1.1: Adds MCM functionality

Soul Gem power will be 10x default at player level 50.
Please see [GitHub](https://github.com/justv316/SoulGem_Level_Scaling) for complete table of values.
You can check the console for the most recent values as they are printed there when the script runs. This also verifies if it's working. 

### Prerequisites
1. [UE4SS](https://www.nexusmods.com/oblivionremastered/mods/32)
	1. [Mad OBScript Extender v2.0a or Later](https://www.nexusmods.com/oblivionremastered/mods/4819)
	2. [Mad Config Menu MCM](https://www.nexusmods.com/oblivionremastered/mods/4810)

### Installation
0. Install Prerequisites
1. Copy Soul_Gem_Scaling.esp to `\Oblivion Remastered\OblivionRemastered\Content\Dev\ObvData\Data`
	1. Add 'Soul_Gem_Scaling.esp' to your Plugins.txt
2. Copy SoulGem_Level_Scaling.ini to `\Oblivion Remastered\OblivionRemastered\Binaries\Win64\MadConfigs`

## Credits

1. Utilizes ObScript Extender created by [MadAborModding](https://next.nexusmods.com/profile/MadAborModding)
2. Utilized MCM created by [MadAborModding](https://next.nexusmods.com/profile/MadAborModding)