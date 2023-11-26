Gauntlet Spectral Gems V1  
Exchanges Colo Coins for Prom Notes for Ancient Mhoire Coins and then buys commonly used Spectral gems used for Gauntlet  
Assesses the character to determine what skills they have trained/specialized to determine how many gems are needed  
All characters are assumed to need Life spectral gems along with gems for whatever their attack skill is (missile, 2H, war, etc.)     

Steps to run:
- Copy .met file into Virindi Tank directory, usually C:\Games\VirindiPlugins\VirindiTank
- Copy .utl files into UtilityBelt autovendor directory, usually C:\Users\<your_path_here>\Documents\Decal Plugins\UtilityBelt\autovendor
- Load the meta in VTank via GUI drop down or type the following in chat: /vt meta load GauntletSpectralGemsV1

Requirements:
- Virindi Tank
- Utility Belt (0.2.7)
- Characters must be in Town Network at start or have tie (primary or secondary) to any Town Network portal

Video: 

Info:
- If the character does not have enough alt currency (Colo, Prom, or Ancient Mhoire), the meta will report what is needed and stop
- Only Colo Coins and Prom Notes are exchanged, no other alt currency is touched
- Before running for the first time, it is recommended to review how many Colo Coins, Prom Notes, Ancient Mhoire Coins, and Spectrals the character has for awareness.
- Because buying things cannot be done by a meta, this meta uses multiple vendor profiles for Absalom Sarraf to dynamically buy the needed amount of Ancient Mhoire Coins.
- For Hurnmel the Smith in Graveyard, you have the option of setting up a character-specific vendor profile (usually under C:\Users\<your_path_here>\Documents\Decal Plugins\UtilityBelt\<server_name>\<character_name>\autovendor) to auto-buy the correct Spectrals...or you can just buy them manually.  The meta opens the vendor window automatically.  A future update to this meta would be to dynamically load vendor profiles for each character based on their skills to make this more seamless.  A few sample profiles for Hurnmel are included. 
- If it is not night time, the meta will stand around in Zaikhal until it is night before going to Graveyard to buy the Spectrals  

How this meta can get stuck/broken:
- 

Other:
- Tested on LeafDawn
- Tested only on ACEmulator.  May or may not work on GDLE.
- Thanks to Eskarina for making metas editable as text files.   This meta would not exist otherwise.