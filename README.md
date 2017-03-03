# NMSMasterMod
This is basically a merged mod of some of the most popular No Man's Sky Mods.  I will do my best to keep it up to date but if you have a mod included in this or want to help in any way please feel free to submit a pull request.

# Included Mods
 * [Megaliths](https://nomansskymods.com/mods/megaliths/) by MsrSgtShooterPerson
 * [Constructs](https://nomansskymods.com/mods/constructs/) by MsrSgtShooterPerson
 * [Transfer freight to and from freighter on planets](https://nomansskymods.com/mods/transfer-freight-to-and-from-freighter-on-planets/) by Quantus
 * ~~[Find the Blackbox](https://nomansskymods.com/mods/find-the-blackbox/) by Quantus~~
 * [Custom Trees](https://nomansskymods.com/mods/custom-trees-mod-4/) by Gamer
 * [Alien Structures](https://nomansskymods.com/mods/alien-structures-mod/) by Gamer
 * [Spaceflight Overhaul](https://nomansskymods.com/mods/spaceflight-overhaul-foundation-edition/) by 03woodm
 * [Dismantle Core Components](https://nomansskymods.com/mods/nms-dismantle-core-components/) by Koori254
 * [Dark Space](https://nomansskymods.com/mods/dark-space-foundation-update/) by jeveir
 * ~~[Buildmenu Additions](https://nomansskymods.com/mods/buildmenu-additions/) by Mjjstral~~
 * [Buildable Bases](https://nomansskymods.com/mods/buildable-bases/) by MonkeyMan192
 * __New Mods__ by __YOU__ _And by that I mean if you're working on a new mod please let me know and I'll add it or simply submit a pull request to have it merged into the existing code._
 
# How to install
 Don't download each mod separately.  Just go to the [Releases](https://github.com/theFisher86/NMSMasterMod/releases/) page and download the most recent release and place it in your No Man's Sky MODS folder.  If any of the included mods are in your mods folder you should remove them.
 
# How to submit your mod / update your mod
1. Submit a pull request onto this GitHub with your __unpacked__ mod.  Please make sure to include all the exml files (unless they're new custom models with a non-vanilla name) in addition to the MBINs.  That'll make it easier to compare.
2. The pull request will be reviewed for conflicts, if there are no conflicts it will be added into the mod with no further issues.
3. If there **are** conflicts they will need resolved via the usual Git methodology.  It is important to note that existing accepted code will most likely not be removed.  However if you're mod is just changing something that is in the same file as another existing mod and the current code is vanilla and your code is new that'll be accepted.  Take a look at the [commit for Alien Structures](https://github.com/theFisher86/NMSMasterMod/commit/153cb5a539bbd644c2a1d34572d433fecee3439b) for an example.
__Note:__PlanetBuildingTable has a limited number of "slots" that can be used in it (1 more than vanilla).  So if you're modifying that it may be trickier to make your mod compatible with others.
 
# To Do
* ~~Create splash banner to show included mods, mod authors and title during startup.~~
* Write a script to check for mod updates and send notifications when mods are updated to make sure that they're updated here as well.
* Build GitHub Pages site with pretty formatting and whatnot.
* Build user-friendly GUI and app so that this can be done custom by users without code.
* If all of the above works out and there is enough user interest possibly build a new NMS Modding website that automatically does all this.
