# fried rice
Scope of this mod:
- Prepatching for my mods
- Compatibility patches
- (re)Balance patches
- Remove bloat from external mods

This mod should **never** add content to the game. New defs should **always** be added in a separate mod. For example, adding an existing recipe to an existing workbench **is within** the scope of this mod. However, creating a new recipe to add to an existing workbench **is not within** the scope of this mod.

## Changes
### Core
**Bold** items are not toggable.
- **Prepatches tribal facions to allow for custom xenotypes**
- Boomalopes bleed chemfuel
- Allow deconstruction of ancient ruins
- No more electrical breakdowns
- Remove faction requirement from crafting recipes
- **Ensure all buildable floors have statbases**
- Flatten floor market value
- Allow corn in hydroponics basin
- Allow devilstrand in hydroponics basin
- Allow haygrass in hydroponics basin
- Make some incident pawn stats visible
- Make boreal forests less marshy
- Remove compacted machinery
- Remove compacted plasteel
- Metal doesn’t burn
- Gold and silver are beautiful
- Increase steel durability
- Increase uranium durability
- Increase plasteel durability
- Minify cryptosleep caskets
- Remove beards (disabled by default)
- White melanin only
- Remove fat bodies
- Remove female hulks
- Remove narrow heads
- Remove wide female heads
- Longer human pregnancy duration
- Natural enemies do not flee
- Permanent enemies do not flee
- No breacher raids
- No drop pod raids
- No sapper raids
- No siege raids
- Rename industrial components
- Rename spacer components
- Rename xerigium
- Rename megatherium
- Render hair above apparel
- Reduce spike trap cost
- Reduce work to build spike traps
- Buff spouse opinion
- Remove work disabler for slaves

### Royalty
- Add highmates to the empire

### Ideology
- Decrease biosculpter age reversal cycle time
- Decrease biosculpter regeneration cycle time
- Decrease biosculpter medic cycle time
- Decrease biosculpter pleasure cycle time
- Double gauranlen pruning speed
- Remove tribal faction requirement for ideology apparel
- Reduce neural supercharger recharge time
- Allow nutrient paste to be eaten with almost any meme
- Disable preferred apparel when ideologions are generated
- Remove forced styles from memes and cultures
- Specialists can do dumb labor

### Biotech
- Impid settlements only appear in desert biomes
- Double child learning rate factor
- Remove forced recluse trait from mechanitor
- Reduce wastepacks per mechanoid recharge

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