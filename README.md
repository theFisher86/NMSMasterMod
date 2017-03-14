# NMSMasterMod
This is basically a merged mod of some of the most popular No Man's Sky Mods.  I will do my best to keep it up to date but if you have a mod included in this or want to help in any way please feel free to submit a pull request.
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
 * [Constructs](https://nomansskymods.com/mods/constructs/) by MsrSgtShooterPerson
   - Great structures that follow the vanilla art style perfectly (most use freighter textures).
 * [Alien Structures](https://nomansskymods.com/mods/alien-structures-mod/) by Gamer
   - More amazing alien structures, many with interactable landing pads and the ability to build within them!
 * [Spaceflight Overhaul](https://nomansskymods.com/mods/spaceflight-overhaul-pathfinder-edition/) by 03woodm
   - A complete overhaul of the spaceship flight systems.  Allowing more control over your ship.
 * [Dark Space](https://nomansskymods.com/mods/dark-space/) by jeveir
   - Removes the excess color from space, while the nebulas and stars still provide color when you're in space you'll feel like you're in space.
 * [Everything Tradeable](https://nomansskymods.com/mods/everything-tradeable/) by Rapta
   - Allows all items to be bought and sold.
 * [More Ships per System](https://nomansskymods.com/mods/more-ships-per-system/) by jaszhix
   - Increases the number of possible ship types in a system for more variety.
 * [Dismantle Core Components](https://nomansskymods.com/mods/nms-dismantle-core-components-path-finder-update/) by Koori254
   - Allows you to dismantle all the components on your ship and move them around.  Do Not dismantle something you don't have a recipe for!
 * [Duds Sky Asteroids & Flight Atmosphere](https://nomansskymods.com/mods/duds-sky/) by jasondude7116
   - Tweaks to the atmospher and asteroid settings to provide a more realistic and enjoyable experience.

# Adapted Features
 * Custom Warp adapted from [CJs Warp Mod](https://nomansskymods.com/mods/cjs-warp-mod/) by cjhaley
   - A customized Warp Effect exclusive to NMS Master Mod
 * Megaliths/Alien Structures merge by theFisher86
   - These two previously incompatbile mods now work together.

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
