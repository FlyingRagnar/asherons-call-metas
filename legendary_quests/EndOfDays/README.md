End of Days Fellow V1  
Completes End of Days quest also known as Crimson Scarab Corruption as a multi-client fellowship 
Unlike many other quest metas, this meta requires some manual user input/navigation    

Steps to run:
- Copy files (.met and .utl) into Virindi Tank directory, usually C:\Games\VirindiPlugins\VirindiTank
- Create fellowship with all characters going on quest
- Type the following in chat: /ub bc /vt meta load EndOfDaysFellowV1

Requirements:
- Virindi Tank
- Utility Belt (0.2.7)
- Characters completing quest must be in a fellowship, everyone in fellow must complete quest
- Characters must be in Town Network at start or have tie (primary or secondary) to any Town Network portal
- One character must have an Egg in their inventory and are designated as the leader
- Uses Rynthid Recall to get to the dungeon

Video: 

Info:
- On this quest there are random spawning portal traps in large rooms, the meta stops before entering these rooms and expects the user to guide the leader safely through each room.  All other fellow members will follow them.  Once through the room, the meta will take over again.  It might be feasible to replace this with nav routes in the future.  The more I did this quest, the more it seemed like there was a consistent safe route through each room.
- Expects Monster tab of Virindi Tank to be configured for quest mobs
- Auto loots legendary chest at the end using currently loaded loot profile
- Uses /ub bc, which can impact multiple fellows/groups if running an army
- Can be completed with just one character in a fellow with an egg
- This quest includes a custom loot profile to loot reward item, at the end of the quest a loot profile of "DefaultLoot.utl" is loaded
Be aware of needing to change this back to your preferred profile afterwards (or rename/copy your profile to be named DefaultLoot.utl)
- This meta uses dispel gems liberally if you have them.  Dispel gems are highly recommended for survival.
- Uses Colosseum Recall at the end to throw away junk.  If a character doesn't have it, meta will stop there

How this meta can get stuck/broken:
- Disconnect of any fellowship member before getting to the dungeon
- If the leader's client glitches and views others as being distant when they are not
- This quest involves looting an item from a mob.  This can be unpredictable at times depending on mob behavior.
- The meta includes functionality for the fellowship to recall if someone hits a portal trap and gets portaled.  However this has not been heavily tested.
- The meta has a tendency to have characters miss the corpse for looting the scarab at the end.  They might get stuck walking into a wall and need to be pointed in the right direction to find the corpse of Bak'tar.  Better detection of this is needed in the meta in the future.

Other:
- Tested on LeafDawn with a fellow of 4
- Tested only on ACEmulator.  May or may not work on GDLE.
- Thanks to Eskarina for making metas editable as text files.   This meta would not exist otherwise.