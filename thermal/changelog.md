Changelog - Thermal Series
=============================
1.16.4-1.2.0
-----------------------------
1.16.4 is now the minimum required version of Minecraft.

_Additions_

- Igneous Extruder (Expansion)
  - Generates various types of stone.
  - Requires a lava source and various other adjacent blocks.
  - The block under the Extruder may matter as well (for Basalt, for example).
- Vacuumulator (Expansion)
  - Sucks up Items (and maybe XP) in an area.
  - Can use a Filter augment to restrict what it grabs.
- Nullifier (Expansion)
  - Destroys Items and Fluids inserted into it via automation.
  - Items can be inserted manually via the GUI; a button is used to empty the inventory.
  - Can use a Filter augment to restrict valid items.

- Decoctive Diffuser (Innovation)
  - Spreads potions in an area.
  - Redstone or Glowstone can be used to boost the potion strength or duration.
- Energetic Infuser (Innovation)
  - Charges up to 9 items with Redstone Flux.
  - Automation-compatible, but does not automatically transfer or have side configuration.

- Filter Augment System
  - Filter augments can be used in almost any block and will intelligently restrict input.
  - These work in some tools (Currently the FluxoMagnet).
  - Only a basic Item Filter for now. System is extensible and more filter types are coming.

- XP Storage Augment
  - Can be placed in many different blocks to enable XP collection (from recipes). XP must be manually removed by a player.
  - This system will be elaborated on a bit more.

- Certain blocks will play sounds when active. This can be disabled in the Client-side configuration.

- Creative Augments which affect various aspects of blocks and tools.

- Efficiency Augments for Machines.

- Insightful Crystal
  - Stores XP. Can be enchanted with Holding.
  - Can automatically collect XP that a player picks up.
  - More to come with this. ;)

- Seeds now drop from grass. (Cultivation)

- So. Much. Mod support.

- Two new Casts for the Blast Chiller. No uses yet in Thermal directly, but some are coming. :)

_Changes_

- Augments are generally more intelligent about what they can be installed in.
  - This isn't perfect and can't work on all augments (as custom ones are possible), but it's generally a lot more convenient.

- Basalz now spawn in Basalt Delta biomes.

- Crescent Hammer now applies an effect on hit. ;)

- Cyclical Processing Augment will now work with Catalysts in the Pulverizer and Induction Smelter.

- Loads and loads of refactors and changes under the hood to improve things.

- Lots of Texture updates!

- Potion (bottle) support is much better. :)

- Redstone Control and Side Reconfiguration can be disabled by default and require augments.
  - These augments are hidden and uncraftable unless this option is selected.
  - Recipes for these augments can be adjusted with a datapack, naturally.

_Fixes_

- Energy Cells can no longer be extracted from - they push RF only.

- Machines will no longer complete processes and void fluid if they do not have sufficient space in a tank.

- Mob sounds have been remastered in Mono, which lets Minecraft correctly reduce their volume.

- Watering Can and Phyto-Gro behavior has been adjusted to work more optimally.

1.16.3-1.1.6
-----------------------------
_Changes_

- Localization updates for German, Japanese, and Italian.

_Fixes_

- Corrects an issue with the Tinker Bench crashing with certain fluid containers.

1.16.3-1.1.5
-----------------------------
_Changes_

- Plates and Coins will be hidden from JEI and Creative unless Thermal Expansion is installed. :)

_Fixes_

- Cells will more properly restrict the types of transfer allowed per side.

1.16.3-1.1.4
-----------------------------
_Changes_

- Optimizes backend behavior for Capability handling on most Tile Entities.

_Fixes_

- Blocks should more reliably connect to various transport solutions in all cases.

1.16.3-1.1.3
-----------------------------
_Additions_

- Some mod compatibility for Quark.

_Changes_

- Cells can now have I/O sides.
- Changes sided extraction behavior for I/O sides to be more restrictive (this generally makes automation more intuitive).
- Improves lighting for Cells.
- Overhauls wrench behavior - it rotates more stuff now. :)
  - I'm sure this will break something. Let's see what.

_Fixes_

- Corrected a minor issue with Tinker Bench drain behavior.
- Energy Cells enchanted with Holding will now correctly keep all of their stored energy when placed.

1.16.3-1.1.2
-----------------------------
_Changes_

- Adjusts minimum fuel value limits for dynamos.

1.16.3-1.1.1
-----------------------------
_Fixes_

- Correct a bug with recipe mangling and dedicated servers.
- Correct a couple of incorrect recipes with invalid inputs.

1.16.3-1.1.0
-----------------------------
_Additions_

- CraftTweaker support is now provided. (Thanks Jared!)
- Aqueous Accumulator
  - Provides LOTS of water.
  - Does not auto-output.
- Energy and Fluid Cells
  - Store Energy or Fluids
  - Sides and flow amounts can be configured.
- Pyrolyzer
  - Generally used for making Coke and Charcoal.
  - Base power is 1/4 of other machines (5 RF/t).
- Fluids:
  - Crude Oil
  - Heavy Oil
  - Light Oil
  - Refined Fuel
  - Creosote Oil
- Resources:
  - Bituminous Sand
  - Bitumen
  - Tar
- Capacitato - a basic battery made with a Potato.
- Corn - crop and seeds. Trade with a villager to obtain.
- Many new machine recipes have been added.
- Perspicacious Stew, which grants Clarity (+40% XP) for one minute on consumption.
- Three new Dies for the Multiservo Press for packing and unpacking recipes.

_Changes_

- Coal Coke has been renamed to "Coke" and will probably have the internal ID changed in the future.
- Energy values for tools have been adjusted.
- Many, many textures have been adjusted and refined. (Thanks floofHips!)
- Prismarine Rails are now faster underwater.
- Tinker Bench can now extract fluid from Potion Bottles.
- Tools can now be enchanted.

1.16.3-1.0.3
-----------------------------
_Additions_

- New extra materials, for future implementation/use.
- Adds enable/disable options for Thermal ore generation.

_Fixes_

- Fixes a recipe desync issue.
- Prevents a crash when other mods would incorrectly grab unobtainable items.

1.16.3-1.0.1
-----------------------------
_Fixes_

- Fixes a minor issue with Patchouli integration.

1.16.3-1.0.0
-----------------------------
__Initial 1.16 release!__ Same as 1.15.2-1.0.0; systems changed to conform to vanilla where necessary.

_Additions_

- New machine recipes to support new vanilla 1.16 features.

_Changes_

- Armor no longer shows obscure stat boosts (such as Hazard Resistance).
- Ore generation parameters and rarity have been adjusted.

1.15.2-1.0.0
-----------------------------
_Additions_

- JEI support for Catalysts. :)
- Thermalpedia - a guidebook!
  - Requires Patchouli.
  - Thanks very much to the team who wrote (and rewrote) this, notably ShinyPorygon and Hekera.

_Changes_

- Updated numerous textures, such as Enderium parts and Thermal Innovation tools.

_Fixes_

- Fixed a crash with the FluxoMagnet.
- Minor bugfixes involving the Fluid Encapsulator.

1.15.2-0.3.0b
-----------------------------
_Additions_

- Added more ways to get rubber. :)

_Changes_

- Adjusted augment scaling on the Flux Capacitor.

_Fixes_

- Fixed a corner case issue which allowed the Tinker Bench to overwrite an augment with a different one.

1.15.2-0.2.5b
-----------------------------
_Changes_

- Elemental mobs no longer spawn above light level 7.

_Fixes_

- Corrected an issue with certain recipes not working properly in the Sequential Fabricator.

1.15.2-0.2.4b
-----------------------------
_Additions_

- Sequential Fabricator
  - It has 9 slots instead of 18 now, but they are smarter.
  - The tank is included by default.
  - It will not craft complex things involving NBT data.

_Changes_

- New machine textures! Thanks floofHips! :)

_Fixes_

- Corrected an issue with the Fluxsaw not using Radius Augments properly.
- Minor bugfixes related to recipe processing and tank displays.

1.15.2-0.2.3b
-----------------------------
_Additions_

- A lot more mod compatibility recipes for Thermal machines. Thanks ShinyPorygon!

_Fixes_

- Corrected a recipe error with the Induction Smelter.

1.15.2-0.2.2b
-----------------------------
_Additions_

- A lot of mod compatibility recipes for Thermal machines.
- Many new Tags to better aid in item filtering.

_Changes_

- Adjusted wrench behavior for better interoperability with other mods.
- Renamed a couple of items - this will generate a missing item warning if you have an existing world. It's fine, really - you wouldn't have had these legitimately anyway.
- Tectonic Grenades now destroy Grass and Mycelium.

_Fixes_

- Various forms of energy transport should now connect to the coil end of a Dynamo.

1.15.2-0.2.1b
-----------------------------
_Changes_

- Reduced mob volume even more.

_Fixes_

- Config option actually works as intended; ores generate.

1.15.2-0.2.0b
-----------------------------
__Good job - you found bugs! This update has lots of bugfixes.__

_Additions_

- Fire Charge crafting recipes for Bronze, Invar, Electrum, Constantan.
- Various machine recipes.
- World generation can now be disabled for any of the given ores. You'll find the config file in the saves/serverconfig folder inside your world save.

_Changes_

- Beekeeper and Hazmat armors will take damage when protecting from their respective effects.
- Detonator can no longer change to Detonate mode if no TNT is primed.
- Diving and Hazmat armors have improved (and no longer bugged) additional air logic. Air lasts roughly 5x and 2.5x longer, respectively.
- Elemental mob Spawn Eggs have been moved to the Thermal Series Items tab. No, Creative Search cannot find them. JEI can. This is a Mojang issue.
- Flux Capacitor now has 2 Augment slots.
- Glacial Grenades, Explosives, and Minecarts deal a small amount of damage.
- Hazmat armor now properly protects from lightning damage, Chilled, and Shocked status effects.
- Hazmat armor no longer crashes the game when protecting from Poison or Wither.
- Improved the "Clear" tooltip for Tanks and Energy Coil GUI Elements. (Hold Alt or Shift while hovering to see it.)
- Perennial crops have had their BlockState, Loot Tables, and growth logic adjusted to be less confusing when using mods that make guesses about BlockStates. ;)
- Potion Augments will now only increase Duration up to 1 hour (72000 ticks).
- Potion Augments will now only increase Level up to 4 (Amplifier 3).
- Retooled a number of backend packages.
- Shift + Right Click will no longer attempt to insert Augments into the Augmentation Panel.
- Tinker Bench GUI Mode Button now has tooltips.
- Various items now have Tags.
- Various recipes adjusted for Tag support.

_Fixes_

- Alchemical Quiver now has proper icons when it has Arrows but no Potion.
- Elemental mobs now move, spawn, and have loot tables.
- Elemental mob sounds are now quieter with distance. They're still probably too loud but at least it attenuates now.
- Phyto-Soil Infuser is now craftable.
- Smelter now uses the correct amounts for all inputs.
- Tectonic Grenades, Explosives, and Minecarts no longer break unbreakable things.

1.15.2-0.1.0b
-----------------------------
__Initial 1.15.2 Release!__

- It's a beta; have fun and go find bugs.

Version
-----------------------------
_Additions_

_Changes_

_Fixes_