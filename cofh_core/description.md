__Active Development__: Minecraft 1.16.5

__Website: [Team CoFH](https://teamcofh.com)__

__Discord: [Team CoFH Discord](https://discordapp.com/invite/uRKrnbH)__

---

CoFH Core has been around a long time (Since 2013!) and has changed throughout its various iterations.

__Information that you read on various wikis may be outdated or no longer apply.__

Please read the overviews under "Historical" to get an idea what the mod offers for a given version of Minecraft. Note that required and optional dependencies have changed with time. We apologize for the changes, but the nature of Minecraft modding is such that flexibility is required to maintain features in an ever-changing codebase.

### __Configuration__

- _Client_: `cofh_core-client.toml` file located in `/config`
- _Server_: `cofh_core-server.toml` located in the `/saves/WORLD_NAME/serverconfigs` folder.

Copying this file to your `/defaultsconfig` folder will apply those configs to all newly created worlds.

Dedicated servers will have this file in `/world/serverconfigs`

## __Features__

This section describes features available for the version under active development. Older versions may have different features.

- Contains core functionality used in Team CoFH mods. 
- Adds a small number of objects to the game's registry which may optionally be used in various capacities.

_Commands_

Syntax: `/cofh COMMAND {PARAMS}`

- friend: Allows for management of the CoFH Friend List, used for securing various objects in game.
- heal: Restores all health, hunger, and cures all negative status effects.
- ignite: Sets the target(s) on fire.
- invis {true|false}: Makes the target(s) invisible, or removes it.
- invuln {true|false}: Makes the target(s) invulnerable, or removes it.
- zap: Strikes the target(s) with lightning, if they can see the sky.

_Enchantments_

- Holding: Increases the capacity of various storage items.

_Fluids_

These currently do not have associated in-world blocks.

- Experience (Essence of Knowledge)
- Honey
- Potion
- Steam

## __Historical__

_1.14+_

- Contains core functionality used in Team CoFH mods. 
- Adds a small number of objects to the game's registry which may optionally be used in various capacities.
- Includes a number of commands which are useful for server admins and packmakers.

__The Redstone Flux API has been deprecated and is no longer required as Forge has effectively incorporated it as the Forge Energy System.__

Enchantments which were previously in this mod are now in Ensorcellation, a more fully-featured mod. It can be found here:

__[Ensorcellation](https://www.curseforge.com/minecraft/mc-mods/ensorcellation)__

_1.12_

- Contains core functionality used in Team CoFH mods.
- Adds a small number of objects (Potions, Enchantments) to the game's registry.
- Includes a number of commands which are useful for server admins and packmakers.

For this version of CoFH Core, the Redstone Flux API is required! It can be found here:

__[Redstone Flux API](https://www.curseforge.com/minecraft/mc-mods/redstone-flux)__

World generation which was previously found in this mod is now in CoFH World, a more fully-featured standalone mod. It can be found here:

__[CoFH World](https://www.curseforge.com/minecraft/mc-mods/cofh-world)__

_1.11_

This version is considered a "stepping" stone version. It has the same features as the 1.10 versions but was modernized to fit Mojang's backend changes.

__It is not recommended that you play a 1.11 modpack.__

_1.10_

- Contains core functionality used in Team CoFH mods.
- Adds a small number of objects (Potions, Enchantments) to the game's registry.
- Includes a number of commands which are useful for server admins and packmakers.

This version of CoFH Core also includes an early-version Redstone Flux API, and no standalone jar is required.

This version of CoFH Core has some world generation controls which allow for ore generation customization.
