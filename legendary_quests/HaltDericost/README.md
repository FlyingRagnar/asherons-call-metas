Halt Dericost Fellow V1
Completes Halt Dericost Ritual quest as a multi-client fellowship

Steps to run:
- Copy files (.met and .utl) into Virindi Tank directory, usually C:\Games\VirindiPlugins\VirindiTank
- Create fellowship with all characters going on quest
- Type the following in chat: /ub bc /vt meta load HaltDericostFellowV1

Requirements:
- Virindi Tank
- Utility Belt (0.2.7)
- Characters completing quest must be in a fellowship, everyone in fellow must complete quest
- Characters must be in Town Network at start or have tie (primary or secondary) to any Town Network portal
- One character must have an Egg in their inventory and are designated as the leader

Video: 

Info:
- Expects Monster tab of Virindi Tank to be configured for quest mobs
- Auto loots legendary chest at the end using current loot profile
- This quest includes a custom loot profile for the quest item, at the end of the quest a loot profile of "DefaultLoot.utl" is loaded
Be aware of needing to change this back to your preferred profile afterwards (or rename/copy your profile to be named DefaultLoot.utl)
- Uses Colosseum Recall at the end to throw away junk.  If a character doesn't have it, meta will stop at this point


How this meta can get stuck/broken:
- If the leader's client glitches and views others as being distant when they are not
- The portal to the reward room is on a timer, with a larger fellow having everyone loot a book and take portal before it disappears can be tricky.  If possible, manual assistance is useful here.  A future update to this meta might ensure that all characters get the book before taking portal.

Other:
- Tested on LeafDawn with a fellow of 4
- Tested only on ACEmulator.  May or may not work on GDLE.
- Thanks to Eskarina for making metas editable as text files.   This meta would not exist otherwise.