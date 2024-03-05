Dream Reaver Fellow V3
Completes Dream Reaver Investigation quest as a multi-client fellowship     

Steps to run:
- Copy files (.met and .utl) into Virindi Tank directory, usually C:\Games\VirindiPlugins\VirindiTank
- Create fellowship with all characters going on quest
- Type the following in chat: /ub bc /vt meta load DreamReaverFellowV1

Requirements:
- Virindi Tank
- Utility Belt (0.2.7)
- Characters completing quest must be in a fellowship, everyone in fellow must complete quest
- Characters must be in Town Network at start or have tie (primary or secondary) to any Town Network portal
- One character must have an Egg in their inventory and are designated as the leader

Video: 

Info:
- Expects Monster tab of Virindi Tank to be configured for quest mobs
- Auto loots legendary chest at the end using currently loaded loot profile
- Uses /ub bc, which can impact multiple fellows/groups if running an army
- Can be completed with just one character in a fellow with an egg
- This quest includes a custom loot profile to loot keys, at the end of the quest a loot profile of "DefaultLoot.utl" is loaded
Be aware of needing to change this back to your preferred profile afterwards (or rename/copy your profile to be named DefaultLoot.utl)
- This meta uses dispel gems liberally if you have them.  This improves survivability as many Virindi cast vulns on this quest
- If the quest leader has the keys from a previous completion of the quest, the meta will skip to just the final part of the quest
- Uses Colosseum Recall at the end to throw away junk.  If a character doesn't have it, meta will stop there

How this meta can get stuck/broken:
- Disconnect of any fellowship member before getting to the dungeon
- If the leader's client glitches and views others as being distant when they are not
- This quest involves looting multiple items from mobs.  This can be unpredictable at times depending on mob behavior.
- The lengendary chests for this quest require some jumping.  The meta will attempt these and should hopefully work for any expected jump skill, but jumps can be unpredictable sometimes

Other:
- Tested on LeafDawn with a fellow of 4
- Tested only on ACEmulator.  May or may not work on GDLE.
- Thanks to Eskarina for making metas editable as text files.   This meta would not exist otherwise.