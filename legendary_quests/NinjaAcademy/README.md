Ninja Academy Fellow V1
Completes Ninja Academy quest as a multi-client fellowship

Steps to run:
- Copy files (.met and .utl) into Virindi Tank directory, usually C:\Games\VirindiPlugins\VirindiTank
- Create fellowship with all characters going on quest
- Type the following in chat: /ub bc /vt meta load NinjaAcademyFellowV1

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
- Uses /ub bc which can impact non-fellow clients if you are running an army.
- Runs to Hoshino Town #2, talks to Daviss and uses the portal behind him to the Ninja Academy.  This is a very hot run.  The leader of the fellow gets a 5 second head start in an attempt to open the door to the building Daviss is in and avoid a traffic jam.
- If any character dies before getting into the Ninja Academy, they will recall and try again.  If you are not well equipped, this could loop endlessly due to the tough Hoshino mobs which aggro when you try to get into the building.
- This might not work so well with a larger fellow, as Daviss must speak to each character to flag them for the portal.

How this meta can get stuck/broken:
- This meta does not have handling for death or disconnect once inside the Ninja Academy.
- Hoshino area is very challenging.  Must have a well equipped team or you will get wiped.

Other:
- Tested on LeafDawn with a fellow of 4
- Tested only on ACEmulator.  May or may not work on GDLE.
- Thanks to Eskarina for making metas editable as text files.   This meta would not exist otherwise.