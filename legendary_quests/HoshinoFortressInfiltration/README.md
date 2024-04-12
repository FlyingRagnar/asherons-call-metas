Hoshino Fortress Infiltration Fellow V1
Completes Hoshino Fortress Infiltration quest as a multi-client fellowship

Steps to run:
- Copy files (.met and .utl) into Virindi Tank directory, usually C:\Games\VirindiPlugins\VirindiTank
- Create fellowship with all characters going on quest
- Type the following in chat: /ub bc /vt meta load HoshinoFortressInfiltrationFellowV1

Requirements:
- Virindi Tank
- Utility Belt (0.2.7)
- Characters completing quest must be in a fellowship, everyone in fellow must complete quest
- Characters must be in Town Network at start or have tie (primary or secondary) to any Town Network portal
- One character must have an Egg in their inventory and are designated as the leader
- The leader must have a key to Hoshino Fortress in their inventory.  There is a separate meta for making the key.

Video: 

Info:
- Expects Monster tab of Virindi Tank to be configured for quest mobs
- Auto loots legendary chest at the end using current loot profile
- This quest includes a custom loot profile for the quest item, at the end of the quest a loot profile of "DefaultLoot.utl" is loaded
Be aware of needing to change this back to your preferred profile afterwards (or rename/copy your profile to be named DefaultLoot.utl)
- Uses Colosseum Recall at the end to throw away junk.  If a character doesn't have it, meta will stop at this point
- Uses /ub bc which can impact non-fellow clients if you are running an army.
- Meta does NOT collect quest armor pieces as part of reward.  Must manually interrupt the meta on clients in order to loot one.

How this meta can get stuck/broken:
- This meta does not have handling for death or disconnect.  In general, dying on this quest excludes a character anyway because a new key to the fortress is usually needed.
- This quest is long and sometimes has glitchy NPCs that don't spawn or don't interact like they should.
- Some of the dungeons on this quest are easy to get stuck in narrow doorways.  Recommend watching characters so they can be manually unstuck if this happens.  Usually happens most often in the Mausoleum dungeon.
- Hoshino area is very challenging.  Must have a well equipped team or you will get wiped.

Other:
- Tested on LeafDawn with a fellow of 4
- Tested only on ACEmulator.  May or may not work on GDLE.
- Thanks to Eskarina for making metas editable as text files.   This meta would not exist otherwise.