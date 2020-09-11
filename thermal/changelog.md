Changelog - Thermal Series
========================================================================================================================

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
