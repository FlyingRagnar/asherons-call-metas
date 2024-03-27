Geraines Study Fellow V1
Completes Geraines Study (aka Mhoire Infiltration) quest as a multi-client fellowship

Steps to run:
- Copy files (.met and .utl) into Virindi Tank directory, usually C:\Games\VirindiPlugins\VirindiTank
- Create fellowship with all characters going on quest
- Type the following in chat: /ub bc /vt meta load GerainesStudyFellowV1

Requirements:
- Virindi Tank
- Utility Belt (0.2.7)
- Characters completing quest must be in a fellowship, everyone in fellow must complete quest
- Characters must be in Town Network at start or have tie (primary or secondary) to any Town Network portal
- One character must have an Egg in their inventory and are designated as the leader
- Must have Graveyard recall, used for turning in items for quest reward
- Characters must NOT possess a Legendary Key in inventory.  Looting a Legendary Key is required to get rewards on this quest and the meta is only equipped to detect if the character has 1 Legendary Key in their inventory

Video: 

Info:
- Expects Monster tab of Virindi Tank to be configured for quest mobs
- Auto loots legendary chest at the end using current loot profile
- Uses /ub bc, which can impact multiple fellows/groups if running an army
- This quest includes a custom loot profile for the keys and reward items, at the end of the quest a loot profile of "DefaultLoot.utl" is loaded
Be aware of needing to change this back to your preferred profile afterwards (or rename/copy your profile to be named DefaultLoot.utl)
- Uses Colosseum Recall at the end to throw away junk.  If a character doesn't have it, meta will stop at this point
- This meta completes the tablet puzzle which is random each time the quest is run.  It will attempt to collect more tablets if it does not have the needed ones after getting all the parchment items
- The first character who loots the boss will get their reward book item from him, the others will then search the surrounding rooms to get the book reward item.  This quest supports a maximum of 1 fellow as there are only 9 books per kill.


How this meta can get stuck/broken:
- If the leader's client glitches and views others as being distant when they are not
- This quest involves looting several keys and opening doors.  If the leader somehow fails to loot these or unlock and open a door, it can get stuck

Other:
- Tested on LeafDawn with a fellow of 4
- Tested only on ACEmulator.  May or may not work on GDLE.
- Thanks to Eskarina for making metas editable as text files.   This meta would not exist otherwise.