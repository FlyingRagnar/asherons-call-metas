Fear Factory Fellow V1   
Completes Fear Factory quest as a multi-client fellowship     

Steps to run:
- Copy files (.met and .utl) into Virindi Tank directory, usually C:\Games\VirindiPlugins\VirindiTank
- Create fellowship with all characters going on quest
- Type the following in chat: /ub bc /vt meta load FearFactoryFellowV1

Requirements:
- Virindi Tank
- Utility Belt (0.2.7)
- Characters completing quest must be in a fellowship, everyone in fellow must complete quest
- One character must have an Egg in their inventory and are designated as the leader
- Must have Rynthid recall

Video: 

Info:
- Expects Monster tab of Virindi Tank to be configured for quest mobs
- Uses /ub bc, which can impact multiple fellows/groups if running an army
- Can be completed with just one character in a fellow with an egg (but would be pretty hard)
- This meta uses dispel gems liberally if you have them.  This improves survivability as the Rynthid mobs are dangerous
- This quest requires each character to free 5 shadows.  The fellowship will continuing running laps in the dungeon until all fellow member have done this.  Shared global variables are used in utility belt for tracking.  Watch fellowship chat for updates from each character on their progress.
- This quest can take a long time with a full fellow, as you must wait for shadows to respawn.

How this meta can get stuck/broken:
- Disconnect of any fellowship member
- Someone dies (Lugians throwing rocks is usually the cause).  A future update would be useful to have whoever dies drop fellow and make updates as needed to allow others to finish.
- If the leader's client glitches and views others as being distant when they are not when grouping before the platforms
- The jump on the Rynthid platforms to reach the dungeon can sometimes be a problem depending on mobs/respawn
- Something goes wrong with setting the shared variable to track progress for each character
- Getting stuck on ledges/ramps when entering/exiting rooms due to mobs


Other:
- Tested on LeafDawn with a fellow of 4
- Tested only on ACEmulator.  May or may not work on GDLE.
- Thanks to Eskarina for making metas editable as text files.   This meta would not exist otherwise.