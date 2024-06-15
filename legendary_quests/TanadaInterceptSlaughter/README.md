Tanada Intercept and Slaughter Fellow V1   
Completes Tanada Intercept and Slaughter quest as a multi-client fellowship     

Steps to run:
- Copy files (.met and .utl) into Virindi Tank directory, usually C:\Games\VirindiPlugins\VirindiTank
- Create fellowship with all characters going on quest
- Type the following in chat: /ub bc /vt meta load TanadaInterceptSlaughterFellowV1

Requirements:
- Virindi Tank
- Utility Belt (0.2.7)
- Characters completing quest must be in a fellowship, everyone in fellow must complete quest
- One character must have an Egg in their inventory and are designated as the leader

Video: 

Info:
- Expects Monster tab of Virindi Tank to be configured for quest mobs
- This meta uses dispel gems liberally if you have them.
- This quest is not good.  It is also long, very long with a large fellowship since each character must collect 6 mask items.  Takes about an hour for a group of 4.
- This quest loads a custom loot profile in order to loot required items on the quest.  A loot profile of DefaultLoot.utl is loaded at the end of the quest.
- This meta uses a shared global variable to keep track of when the entire fellowship has collected enough masks.  It then proceeds to the next section of the quest.  Fellowship chat is used to make it easy to track the progress of each character.
- This quest has one of the worst starting and ending NPCs of any quest.  They are located on the upper floor of a building in Hoshino Town #3.
- This quest has 2 different alternate endings.  This meta does the version which gives the masks to Tanada Nanjou Kutekei inside the dungeon.  The alternate ending has a cool, but laggy animation which doesn't work as well when completing at the same time with multiple characters.


How this meta can get stuck/broken:
- Death of any fellowship member
- If the leader's client glitches and views others as being distant when they are not when grouping before the platforms
- Getting into the NPC building at the start and end of the quest is difficult and dangerous.  Easy for a character to get blocked by mobs or for melee characters to run too far away chasing mobs in the house.  This can be helped by manually guiding any characters that get off track.

Other:
- Tested on LeafDawn with a fellow of 4
- Tested only on ACEmulator.  May or may not work on GDLE.
- Thanks to Eskarina for making metas editable as text files.   This meta would not exist otherwise.