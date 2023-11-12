Save Karul Fellow V1  
Completes Save Karul quest (aka Deconstruction) as a multi-client fellowship  
This quest is very lum efficient  
Runtime is around 10 minutes with a fellow of 4  
Save Karul is level 200+  

Steps to run:
- Copy files (.met and .utl) into Virindi Tank directory, usually C:\Games\VirindiPlugins\VirindiTank
- Create fellowship with all characters going on quest
- Type the following in chat: /ub bc /vt meta load SaveKarulFellowV1

Requirements:
- Virindi Tank
- Utility Belt (0.2.7)
- Characters completing quest must be in a fellowship, everyone in fellow must complete quest
- Characters must be in Town Network at start or have tie (primary or secondary) to any Town Network portal
- One character must have an Egg in their inventory and are designated as the leader

Video: https://youtu.be/ADyOfIVw4HA

Info:
- Expects Monster tab of Virindi Tank to be configured for quest mobs
- Auto loots legendary chest at the end using currently loaded loot profile
- Uses /ub bc, which can impact multiple fellows/groups if running an army
- Can be completed with just one character in a fellow with an egg
- If any character dies during the dangerous run into the house to use the portal, they will portal recall and try again
- During testing it was rare that a character would fail to make it into portal in more than two attempts
- This quest includes a custom loot profile to loot a key, at the end of the quest a loot profile of "DefaultLoot.utl" is loaded
Be aware of needing to change this back to your preferred profile afterwards (or rename/copy your profile to be named DefaultLoot.utl)


How this meta can get stuck/broken:
- Disconnect of any fellowship member before getting to the dungeon
- If the leader's client glitches and views others as being distant when they are not
- If your characters are too soft and the Hoshino mobs wipe them out

Other:
- Tested on LeafDawn with a fellow of 4
- Tested only on ACEmulator.  May or may not work on GDLE.
- Thanks to Eskarina for making metas editable as text files.   This meta would not exist otherwise.