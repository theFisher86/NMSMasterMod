# NMSMasterMod
This is basically a merged mod of some of the most popular No Man's Sky Mods.  I will do my best to keep it up to date but if you have a mod included in this or want to help in any way please feel free to submit a pull request.

This has been overhauled to only include mods that I feel are **essential** to the game and need patches for compatibility.  I have removed a lot of mods from previous versions to actually make this more customizable.  For example, I removed mods that alter the flight mechanics as there are multiple versions of those mods that conflict with each other but no other mods and are really personal preference.

I am working on a big project currently that will require NMSMasterMod as a dependency so I want to make sure NMSMasterMod is as lean and efficient as possible.  Please see the "Recommended Mods" section below for the additional mods I would recommend installing along-side.

### Mods included will:
 * Be fully compatible with each other, this is the number 1 priority
 * Make every effort to follow NMS Vanilla art style and theme.
 * Avoid changing the difficulty of the game drastically (mods that make the game inreasingly easier will not be included).
 * Make every attempt to avoid negatively affecting performance.

# Included Mods

 * [SimCity 5300](https://nomansskymods.com/mods/simcity-5300/) by theFisher86
   - Buildable vehicles, buildings, teleports and more.  All fully customizable with color
 * [Megaliths](https://nomansskymods.com/mods/megaliths/) by MsrSgtShooterPerson
   - Huge towering rocks and plants to make the game way more _alien_
 * [Alien Structures](https://nomansskymods.com/mods/alien-structures-mod/) by Gamer
   - More amazing alien structures, many with interactable landing pads and the ability to build within them!
 * [Dismantle Core Components](https://nomansskymods.com/mods/nms-dismantle-core-components-path-finder-update/) by Koori254
   - Allows you to dismantle all the components on your ship and move them around.  Do Not dismantle something you don't have a recipe for!
 * [Exocraft Scan Booster](https://nomansskymods.com/mods/exocraft-scan-boost/) by Tub0Crisco
   - Remixed to require the vehicle scanner upgrade level 2 (originally worked on normal scanner)
   - Provides more scan options
 * [No Man's Customs](https://nomansskymods.com/mods/roamer-tune-up/) by JakeBurchDev
   - Improvements to vehicle speed, jump, etc.  
   - Makes vehicles more fun to drive.
 * [Origins - A Story Untold](https://nomansskymods.com/mods/origins-a-story-untold/) by Nadalle
   - New models and buildings with a some lore to go along with them!
 * [Efficient Harvesters](https://nomansskymods.com/mods/efficient-harvesters/) by homesick
   - Reduces the cost of harvesters and increases their output making them more useful.  They were a little too much work with not enough payoff in vanilla.
   
# Recommended Mods
 * A flight mechanics overhaul mod
   - While there are a few options of mods that do this I would recommend utilizing one that removes terrain avoidance.  Other than that just choose your favorite from the list below
     - [Spaceflight Overhaul](https://nomansskymods.com/mods/spaceflight-overhaul-pathfinder-edition/)
     - [Darc Flight](https://nomansskymods.com/mods/darc-flight-low-fast-reverse-on-planets-and-in-space-for-pathfinder-update/)
     - [Duds Sky Flight](https://nomansskymods.com/mods/duds-sky/)
 * [More Ships Per System](https://nomansskymods.com/mods/more-ships-per-system/)
   - This was removed becuase it didn't cause any conflicts with other files and caused performance issues for some people.  However, if it doesn't decrease your performance I recommend the 24 ships version.
 * [CJs Warp Mod](https://nomansskymods.com/mods/cjs-warp-mod/) 
   - I think this is way cooler than the vanilla effect but that's my opinion.  Just a cool new textures for the warping effects.
 * [Better Landing](https://nomansskymods.com/mods/better-landing-landing-zones-pathfinder/)
   - This makes the icon for landing pads appear and function from farther away.  Didn't have any conflicts with other mods so it was removed but I think it's invaluable.
 * [Big Quads](https://nomansskymods.com/mods/big-quads/)
   - Just makes Quads larger, looks cool
 * [Constructs](https://nomansskymods.com/mods/constructs/)
   - This is one of my favorite mods, only removed because it didn't require a compatibility patch and some people didn't like it due to a bug it can cause with certain missions.
     

# How To Install
- Download 2 files the most recent CustomModelsAndEffects file and the most recent Data file.  They both not be included in every release but make sure you always have the most recent version of both.  I'll try to include a link to the most recent version where I can.
- If you're installing on an existing save game, PLEASE make sure to save in a space station before installing this mod, otherwise you may end up inside the planet!  There's also a chance your base will be covered by plants or experience some issues.  This is best installed on a new game but by no means requried.
- Put both of these into your /PCBANKS/MODS/ folder in your NMS install directory
- Make sure to delete/rename the DISABLEMODS.TXT file in /PCBANKS/
- Profit!
 
# How to submit your mod / update your mod
1. Submit a pull request onto this GitHub with your __unpacked__ mod.  Please make sure to include all the exml files (unless they're new custom models with a non-vanilla name) in addition to the MBINs.  That'll make it easier to compare.
2. The pull request will be reviewed for conflicts, if there are no conflicts it will be added into the mod with no further issues.
3. If there **are** conflicts they will need resolved via the usual Git methodology.  It is important to note that existing accepted code will most likely not be removed.  However if you're mod is just changing something that is in the same file as another existing mod and the current code is vanilla and your code is new that'll be accepted.  Take a look at the [commit for Alien Structures](https://github.com/theFisher86/NMSMasterMod/commit/153cb5a539bbd644c2a1d34572d433fecee3439b) for an example.
__Note:__PlanetBuildingTable has a limited number of "slots" that can be used in it (1 more than vanilla).  So if you're modifying that it may be trickier to make your mod compatible with others.
