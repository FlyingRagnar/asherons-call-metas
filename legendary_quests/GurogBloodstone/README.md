Gurog Bloodstone Fellow V1   
Completes Gurog Creation and Bloodstone Investigation quests as a multi-client fellowship     

Steps to run:
- Copy files (.met and .utl) into Virindi Tank directory, usually C:\Games\VirindiPlugins\VirindiTank
- Create fellowship with all characters going on quest
- Type the following in chat: /ub bc /vt meta load GurogBloodstoneFellowV1

Requirements:
- Virindi Tank
- Utility Belt (0.2.7)
- Characters completing quest must be in a fellowship, everyone in fellow must complete quest
- One character must have an Egg in their inventory and are designated as the leader

Video: 

Info:
- Expects Monster tab of Virindi Tank to be configured for quest mobs
- These quests are long.  Gurog Creation has an item drop which is one per kill.  This requires a several minute respawn for each member of the fellowship.  Bloodstone is just long and redundant.
- This quest loads a custom loot profile in order to loot required items on the quest.  A loot profile of DefaultLoot.utl is loaded at the end of the quest.
- This meta uses a shared global variable to keep track of when the entire fellowship has the Gurog Creation item (Torn Note).  It then proceeds to the next section of the quest.
- Monitoring of this meta is highly recommended.  There are several objects in the initial Gurog dungeon which block doors.  It is easy for a character to get stuck on these and get left behind.  When looting the final Bloodstone boss, it can be tricky for Vtank to find the corpse/treasure because there are so many.  Assistance is recommended to keep fellowship characters from failing to find it fast enough and respawn happening.

How this meta can get stuck/broken:
- Death of any fellowship member
- If the leader's client glitches and views others as being distant when they are not when grouping before the platforms
- Getting stuck somewhere in the many dungeons visited during this quest

Other:
- Tested on LeafDawn with a fellow of 4
- Tested only on ACEmulator.  May or may not work on GDLE.
- Thanks to Eskarina for making metas editable as text files.   This meta would not exist otherwise.