# Soul Gem Level Scaling

# Changelog
1.0
	* Initial Release
1.0a
	* Fixed initial Release
1.1
	* Added MCM functionality for player to configure the scaling factor that the Soul Gem level scaling uses.
1.1a 
	* Fixed Dependency Issue
1.2
	* Added scaling for Enchant Charge level 

## Description
![Charge Level](/image/Grand_Soul_Gem.png "Grand Soul Gem")

* Automatically Scales Soul Gem power based on player level. This is accomplished using a quest script running in the background that runs once per level up. The quest script utilizes MadAborModdings ObScript Extender to set the related game settings.
* Please see [GitHub](https://github.com/justv316/SoulGem_Level_Scaling) for complete table of values.
* You can check the console for the most recent values as they are printed there when the script runs. This also verifies if it's working. 

### Prerequisites
1. [UE4SS](https://www.nexusmods.com/oblivionremastered/mods/32)
	1. [Mad OBScript Extender v2.0a or Later](https://www.nexusmods.com/oblivionremastered/mods/4819)
	2. [Mad Config Menu MCM](https://www.nexusmods.com/oblivionremastered/mods/4810)

### Installation
0. Install Prerequisites
1. Copy Soul_Gem_Scaling.esp to `\Oblivion Remastered\OblivionRemastered\Content\Dev\ObvData\Data`
	1. Add `Soul_Gem_Scaling.esp` to your Plugins.txt
2. Copy SoulGem_Level_Scaling.ini to `\Oblivion Remastered\OblivionRemastered\Binaries\Win64\MadConfigs`

### Uninstallation
0. This mod alters Game Settings. If you need to uninstall this, do the following after the plugin is removed.
	1. Download uninstall.txt from GitHub [Link](https://github.com/justv316/SoulGem_Level_Scaling/blob/b624726ef6124cffd85467e973121e6b942aa70a/src/OblivionRemastered/uninstall.txt)
	2. Copy the txt file to `\Oblivion Remastered\OblivionRemastered\Binaries`
	3. While In-game, press the ~ key to open the console, type `exec uninstall` and press enter.
	4. The default settings have now been restored
	
### Compatibility
0. Mods that manually set GameSettings seemingly will overwrite anything set by console command
1. This also applies to Settings set by [GameSettings Loader](https://www.nexusmods.com/oblivionremastered/mods/746) ini files.


## Credits
1. Utilizes ObScript Extender created by [MadAborModding](https://next.nexusmods.com/profile/MadAborModding)
2. Utilizes MCM created by [MadAborModding](https://next.nexusmods.com/profile/MadAborModding)