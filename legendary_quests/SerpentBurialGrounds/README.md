Serpent Burial Grounds Fellow V1   
Completes Serpent Burial Grounds quest as a multi-client fellowship    
Level 150+  

Steps to run:
- Copy files (.met and .utl) into Virindi Tank directory, usually C:\Games\VirindiPlugins\VirindiTank
- Create fellowship with all characters going on quest
- Type the following in chat: /ub bc /vt meta load SerpentBurialGroundsFellowV1

Requirements:
- Virindi Tank
- Utility Belt (0.2.7)
- Characters completing quest must be in a fellowship, everyone in fellow must complete quest
- Characters must be in Town Network at start or have tie (primary or secondary) to any Town Network portal
- One character must have an Egg in their inventory and are designated as the leader

Video: 

Info:
- This meta has some custom logic for casting item magic debuffs on the boss's sword.  Characters that have trained/spec War or Void, or spec Item Magic will do this during the boss fight.
- This meta also has some unused states related to debuffing enemy shields (which never worked quite right)
- Expects Monster tab of Virindi Tank to be configured for quest mobs
- Auto loots legendary chest at the end using currently loaded loot profile
- Can be completed with just one character in a fellow with an egg...but not easily
- This quest includes a custom loot profile to loot keys, at the end of the quest a loot profile of "DefaultLoot.utl" is loaded
Be aware of needing to change this back to your preferred profile afterwards (or rename/copy your profile to be named DefaultLoot.utl)

How this meta can get stuck/broken:
- Disconnect of any fellowship member before getting to the dungeon
- If the leader's client glitches and views others as being distant when they are not

Other:
- Tested on LeafDawn with a fellow of 4
- Tested only on ACEmulator.  May or may not work on GDLE.
- Thanks to Eskarina for making metas editable as text files.   This meta would not exist otherwise.