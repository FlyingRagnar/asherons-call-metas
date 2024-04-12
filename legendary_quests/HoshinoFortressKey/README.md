Hoshino Fortress Key Fellow V1
Collects and constructs a key to Hoshino Fortress from the 3 different Hoshino towns
This key is used on the Hoshino Fortress Infiltration and Hoshino Must Die quests
The key only lasts for a few hours.

Steps to run:
- Copy files (.met and .utl) into Virindi Tank directory, usually C:\Games\VirindiPlugins\VirindiTank
- Create fellowship with all characters going on quest
- Type the following in chat: /ub bc /vt meta load HoshinoFortressKeyFellowV1

Requirements:
- Virindi Tank
- Utility Belt (0.2.7)
- Characters completing quest must be in a fellowship, everyone in fellow must complete quest
- Characters must be in Town Network at start or have tie (primary or secondary) to any Town Network portal
- One character must have an Egg in their inventory and are designated as the leader

Video: 

Info:
- Expects Monster tab of Virindi Tank to be configured for quest mobs
- This quest includes a custom loot profile for the key parts, at the end of the quest a loot profile of "DefaultLoot.utl" is loaded
Be aware of needing to change this back to your preferred profile afterwards (or rename/copy your profile to be named DefaultLoot.utl)
- Uses dispel gems if they exist in the player's inventory.  You need these to realistically survive the Hoshino area.  Recommend having at least 50 per character.
- This meta uses /ub bc which can have an impact on non-fellow clients if you are running an army.

How this meta can get stuck/broken:
- This meta has no handling for death or disconnect.  This should probably be added in the future.  If a non-leader character dies, the meta will stall when grouping up for the next town.  The character can be removed from the fellow to continue.  If the leader dies, the meta does not recover.
- Hoshino towns are very challenging.  High end equipment is recommended for all characters.
- Getting into the buildings in Hoshino towns can be a problem due to the number of mobs.  May need to manually assist at some points to get characters unstuck.  
- The more characters in a fellow, the better chance of everyone surviving.

Other:
- Tested on LeafDawn with a fellow of 4
- Tested only on ACEmulator.  May or may not work on GDLE.
- Thanks to Eskarina for making metas editable as text files.   This meta would not exist otherwise.