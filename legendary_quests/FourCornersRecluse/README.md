Four Corners Fellow V1
Completes last part of Four Corners quest as a multi-client fellowship
Does not complete flagging dungeons prior to last part     

Steps to run:
- Copy files (.met and .utl) into Virindi Tank directory, usually C:\Games\VirindiPlugins\VirindiTank
- Create fellowship with all characters going on quest
- Type the following in chat: /ub bc /vt meta load FourCornersRecluseFellowV1

Requirements:
- Virindi Tank
- Utility Belt (0.2.7)
- Characters completing quest must be in a fellowship, everyone in fellow must complete quest
- Characters must be in Town Network at start or have tie (primary or secondary) to any Town Network portal
- One character must have an Egg in their inventory and are designated as the leader
- Must have Neftet recall
- Must be flagged for Sanctuary of the Recluse, meta will stop if character is not

Video: 

Info:
- Expects Monster tab of Virindi Tank to be configured for quest mobs
- Auto loots legendary chest at the end using currently loaded loot profile
- Uses /ub bc, which can impact multiple fellows/groups if running an army
- This quest includes a custom loot profile for the leader to loot a key from the Dust Guardian, after this a loot profile of "DefaultLoot.utl" is loaded
Be aware of needing to change this back to your preferred profile afterwards (or rename/copy your profile to be named DefaultLoot.utl)
- This meta uses dispel gems liberally if you have them.  This improves survivability as many enemies cast vulns.
- Uses Colosseum Recall at the end to throw away junk.  If a character doesn't have it, meta will stop at this point

How this meta can get stuck/broken:
- Disconnect of any fellowship member before getting to the dungeon
- If the leader's client glitches and views others as being distant when they are not
- The jumps in Neftet to enter the dungeon can sometimes be a pain if there are respawns, mobs roaming
- The first boss fight can be tricky to detect when the exit doors have opened

Other:
- Tested on LeafDawn with a fellow of 4
- Tested only on ACEmulator.  May or may not work on GDLE.
- Thanks to Eskarina for making metas editable as text files.   This meta would not exist otherwise.