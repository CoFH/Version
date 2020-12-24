Changelog - Thermal Series
========================================================================================================================
1.16.3-1.1.1
------------------------------------------------------------------------------------------------------------------------
Fix a bug with recipe mangling and dedicated servers.

Fix a couple of incorrect recipes and invalid inputs.

1.16.3-1.1.0
------------------------------------------------------------------------------------------------------------------------
Adds Bitumen and Tar (and Bituminous Sand) as resources.
Adds Crude Oil, Heavy Oil, Light Oil, Refined Fuel, and Creosote Oil as fluids.
Adds the Capacitato - a low-end battery good for moving energy into machines.

Adds 3 new Dies to the Multiservo Press for packing and unpacking recipes.
Adds a new machine - the Pyrolyzer. Generally used for making Coke and Charcoal.
Adds Fluid and Energy Cells (and their respective frames).
Adds the Aqueous Accumulator. Provides lots of water; but does not auto-output.

Coal Coke has been renamed to "Coke" and will probably have the internal ID changed in the future.

Adds Corn as a crop.
Adds Perspicacious Stew, which grants Clarity (+40% XP) for one minute on consumption.

Energy values for tools have been adjusted.
Tools can now be enchanted.

The Tinker Bench can now extract fluid from Potion Bottles.

Localizations and tooltips have been improved.

Prismarine Rails are now faster underwater.

Lots of new recipes have been added.
CraftTweaker support is now provided (thanks Jared!)

Many, many textures have been adjusted and refined.

1.16.3-1.0.3
------------------------------------------------------------------------------------------------------------------------
Adds a couple of extra materials, for future implementation/use.
Adds enable/disable options for Thermal ore generation.

Fixes a recipe desync issue.

Prevents a crash when other mods would incorrectly grab unobtainable items.

1.16.3-1.0.1
------------------------------------------------------------------------------------------------------------------------
Fixes an issue with Patchouli.

1.16.3-1.0.0
------------------------------------------------------------------------------------------------------------------------
Initial 1.16 release! Same as 1.15.2-1.0.0; systems changed to conform to vanilla where necessary.

Added machine recipes to support new vanilla 1.16 features.

Armor no longer shows obscure stat boosts. (eg, Hazard Resistance)

Ore spawn and rarity has been adjusted.

1.15.2-1.0.0
------------------------------------------------------------------------------------------------------------------------
Minor bugfixes involving the Fluid Encapsulator.
Fixed a crash with the FluxoMagnet.

Added JEI support for Catalysts. :)
Added a guidebook! Requires Patchouli.
    -Thanks very much to the team who wrote (and rewrote) this, notably ShinyPorygon and Hekera.
Updated numerous textures, such as Enderium parts and Thermal Innovation tools.

1.15.2-0.3.0b
------------------------------------------------------------------------------------------------------------------------
Added more ways to get rubber. :)

Adjusted augment scaling on the Flux Capacitor.

Fixed an issue with the Tinker Bench and augs duping.

1.15.2-0.2.5b
------------------------------------------------------------------------------------------------------------------------
Fixed an issue with certain recipes not working properly in the Sequential Fabricator.

Elemental mobs no longer spawn above light level 7.

1.15.2-0.2.4b
------------------------------------------------------------------------------------------------------------------------
Added the Sequential Fabricator, an auto-crafting machine.

    -It has 9 slots instead of 18 now, but they are smarter.
    -The tank is included by default.
    -It won't craft complex things involving NBT.

New machine textures! Thanks floofHips! :)

Fixed an issue with the Fluxsaw not using Radius Augments properly.
Minor bugfixes related to recipe processing and tank displays.

1.15.2-0.2.3b
------------------------------------------------------------------------------------------------------------------------
Fixed a recipe error with the Induction Smelter.

Added a lot more mod compatibility and machine recipes. Thanks Porygon!

1.15.2-0.2.2b
------------------------------------------------------------------------------------------------------------------------
Added a huge amount of mod support (Biomes You'll Go, Pams, Refined Storage, Silent's Mechanisms, Traverse).
Added lots of tags to better aid in item filtering.

Adjusted wrench behavior for better interoperability with other mods.

Renamed a couple of items - this will generate a missing item warning if you have an existing world. It's fine, really - you wouldn't have had these legitimately anyway.

Tectonic Grenades now destroy Grass and Mycelium.

Various forms of energy transport should now connect to the coil end of a Dynamo.

1.15.2-0.2.1b
------------------------------------------------------------------------------------------------------------------------
Okay, so now the config option actually works as intended. Ores generate, mobs are more silent.

1.15.2-0.2.0b
------------------------------------------------------------------------------------------------------------------------
Good job - you found bugs! This update has lots of bugfixes.

World generation can now be disabled for any of the given ores. You'll find the config file in the saves/serverconfig folder inside your world save.

Elemental mobs now move, spawn, and have loot tables.
Elemental mob sounds are now quieter with distance. They're still probably too loud but at least it attenuates now.

Phyto-Soil Infuser now has a recipe.
Many recipes were adjusted to have Tag support.
Smelter now uses the correct amounts for all inputs.

Tectonic Grenades, Explosives, and Minecarts no longer break unbreakable things.
Glacial Grenades, Explosives, and Minecarts deal a small amount of damage.

Added Fire Charge crafting recipes for Bronze, Invar, Electrum, Constantan.
Added Tags to various resources.
Added tooltips to the Tinker Bench GUI Mode Button.
Added various machine recipes.

Alchemical Quiver now has proper icons when it has Arrows but no Potion.

Beekeeper and Hazmat armors will take damage when protecting from their respective effects.

Detonator can no longer change to Detonate mode if no TNT is primed.

Diving and Hazmat armors have improved (and no longer bugged) additional air logic. Air lasts roughly 5x and 2.5x longer, respectively.

Elemental mob Spawn Eggs have been moved to the Thermal Series Items tab.
-No, Creative Search cannot find them. JEI can. This is a Mojang issue.

Flux Capacitor now has 2 Augment slots.

Hazmat armor now properly protects from lightning damage, Chilled, and Shocked status effects.
Hazmat armor no longer crashes the game when protecting from Poison or Wither.

Improved the "Clear" tooltip for Tanks and Energy Coil GUI Elements. (Hold Alt or Shift while hovering to see it.)

Perennial crops have had their BlockState, Loot Tables, and growth logic adjusted to be less confusing when using mods that make guesses about BlockStates. ;)

Potion Augments will now only increase Duration up to 1 hour (72000 ticks).
Potion Augments will now only increase Level up to 4 (Amplifier 3).

Shift + Right Click will no longer attempt to insert Augments into the Augmentation Panel.

Retooled a number of backend packages.

1.15.2-0.1.0b
------------------------------------------------------------------------------------------------------------------------
Initial 1.15.2 Release!

It's a beta; have fun and go find bugs.
