Slave Master Fellow V1   
Completes Slave Master quest as a fellowship 

Steps to run:
- Copy files (.met and .utl) into Virindi Tank directory, usually C:\Games\VirindiPlugins\VirindiTank
- Create fellowship with all characters going on quest
- Type the following in chat: /ub bc /vt meta load SlaveMasterFellowV1

Requirements:
- Virindi Tank
- Utility Belt (0.2.7)
- Must have Rynthid recall

Video: 

Info:
- Expects Monster tab of Virindi Tank to be configured for quest mobs
- This meta uses dispel gems liberally if you have them. 
- Uses /ub bc which can impact clients other than those in the current fellowship if running an army
- This meta frequently gets stuck due to various reasons (see below).  It is advised to monitor this meta while it runs to assist when this happens.
- Has navroutes for all 4 Scrying Rod device locations.  Assesses the rod at the start of the quest and determines route accordingly.
- This quest loads a custom loot profile for looting required quest items.  A default loot profile of DefaultLoot.utl is loaded afterward.

How this meta can get stuck/broken:
- The outside jumps to the device locations are tricky.  A random mob respawn can disrupt the jump timing.
- In the Sand Caves dungeon, sometimes the location where the Channeller or Soothsayer dies will be out of range for all characters to loot depending on where they are.  This can require some manual assistance.
- In the Temple dungeon, it is common for a character to get stuck in one of the many rooms/hallways/doorways.  This is the most common cause of getting stuck.  This happens often for melee characters.
- In the Temple dungeon, sometimes mobs can bug and not attack, which then can cause the doors not to open to proceed.  If this happens, need to track down the mob and kill it manually with some assistance.


Other:
- Tested on LeafDawn
- Tested only on ACEmulator.  May or may not work on GDLE.
- Thanks to Eskarina for making metas editable as text files.   This meta would not exist otherwise.