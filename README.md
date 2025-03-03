# fried rice
Scope of this mod:
- Prepatching for my mods
- Compatibility patches
- (re)Balance patches
- Remove bloat from external mods

This mod should **never** add content to the game. New defs should **always** be added in a separate mod. For example, adding an existing recipe to an existing workbench **is within** the scope of this mod. However, creating a new recipe to add to an existing workbench **is not within** the scope of this mod.

## Supported Mods
Mod patches are balanced around the default value for toggable patches because I'm not writing a million lines of patch logic for every toggle. For example, [gene expansion](https://github.com/boomersama/boomer.genes) removes genetic aptitudes by default and the VRE Phytokins patch compensates for that metabolism loss. If aptitudes are toggled back on, Phytokin will have +1 metabolism.

### Combat Extended
- Prevents backpacks from spawning on non-player pawns
### GiTS Cyberbrains
- Removes abilities to make the brains less OP and reduce gizmo clutter
### Vanilla Apparel Expanded
- Removes most non-specialized apparel
- Prevents most mod apparel from spawning on non-player pawns
- Nerfs non-specialized apparel like jumpsuits and boots
- Prevents military uniforms from spawning on non-combatants
- Allows jumpsuits to spawn on non-player pawns
### Vanilla Factions Expanded - Mechanoids
- Removes drones since we now have player mechanoids
### Vanilla Factions Expanded - Pirates
- Renames rum to pruno (toilet wine)
### Vanilla Furniture Expanded - Security
- Removes everything but ammo crates, artillery, decoys, EMP cannons, and shield generators
- - Note: C# assemblies call for removed defs which results in harmless red errors
- Allows the player to build ammo crates without researching fabrication
### Vanilla Psycasts Expanded
- Removes psycaster raids to prevent spacer armor raids (mainly from VFE - Deserters) on my day 20 colony
### Vanilla Races Expanded - Archon
- Removes extremely aggressive and long pregnancy genes (fried rice increases pregnancy duration)
- Uses vanilla heads
### Vanilla Races Expanded - Phytokin
- Adjusts metabolism gain from photosynthesis to compensate for removed aptitudes
- Uses vanilla heads
### Vanilla Weapons Expanded - Coilguns
- Prevents coilguns from spawning on non-player pawns

## To-do:
- Debloat [RimThunder Functional Furniture Expanded](https://steamcommunity.com/sharedfiles/filedetails/?id=3430151040)
- Debloat [Vanilla Factions Expanded Settlers](https://steamcommunity.com/sharedfiles/filedetails/?id=2052918119)
- Remove skill buff from Brawler trait
- Remove skill buff from Gourmand trait and replace with CookSpeed buff and/or FoodPoisonChance debuff
- Remove skill buff from Sickly trait

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg