Rynthid Assessment V1   
Completes Rynthid Assessment quest     

Steps to run:
- Copy files (.met and .utl) into Virindi Tank directory, usually C:\Games\VirindiPlugins\VirindiTank
- Create fellowship with all characters going on quest
- Type the following in chat: /ub bc /vt meta load RynthidAssessmentV1

Requirements:
- Virindi Tank
- Utility Belt (0.2.7)
- Must have Rynthid recall

Video: 

Info:
- Expects Monster tab of Virindi Tank to be configured for quest mobs
- This meta uses dispel gems liberally if you have them. 
- This metas has navs/logic for all the different rooms you can get on Rynthid Assessment.  
- You are guaranteed to get at least one jump puzzle room.  The meta has navs for them all which have been tested, but also has logic to reset to the bottom of the jump puzzle and try again if it get stuck somewhere.
- This meta skips attempting rooms which contain Gurogs and random portal traps.  There is no way (currently) that a nav could either brute force or avoid portal traps, so the meta instead waits for a different portal instead.  This can cause the meta to take a while.  You also have the option of manually completing the Gurog room and the meta will take over again automatically.  Leave Vtank on while doing so.
- One room contains Mites that drop 3 different keys.  If you get this room, the meta will load a loot profile to ensure it loots the keys.  It will then load a DefaultLoot.utl profile when done.  
- This meta has handling for death.  It will recall and retry the assessment dungeon.  This can happen often when completing the rooms with training dummies that shoot lightning spells.  It is safer if doing the quest with a group, as there will be more targets for the dummies.  However, you can also assist the meta manually by dodging or healing while it is navigating to try to stay alive.

How this meta can get stuck/broken:
- The levers at the end can be done incorrectly if you get stuck in a death loop and do the dungeon many times.  Not sure if this is a bug in the meta or glitch in the quest.
- Missing a key in the mite room can cause a character to get stuck in the hallway with 3 locked doors.  This depends on where the mite corpses end up.
- Jump puzzle navs were tested a lot, but there could still be jump skill levels they will not work with.

Other:
- Tested on LeafDawn
- Tested only on ACEmulator.  May or may not work on GDLE.
- Thanks to Eskarina for making metas editable as text files.   This meta would not exist otherwise.