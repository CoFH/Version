__Active Development__: Minecraft 1.16.5

__Website: [Team CoFH](https://teamcofh.com)__

__Discord: [Team CoFH Discord](https://discordapp.com/invite/uRKrnbH)__

---

Ensorcellation adds a bunch of new enchantments, appropriate for both lightly and heavily modded gameplay. It also provides improved versions of many vanilla enchantments as well.

__This mod requires CoFH Core. It can be found here: [CoFH Core](https://www.curseforge.com/minecraft/mc-mods/cofh-core)__

### __Configuration__

- _Client_: `ensorcellation-client.toml` file located in `/config`
- _Server_: `ensorcellation-server.toml` located in the `/saves/WORLD_NAME/serverconfigs` folder.

Copying this file to your `/defaultsconfig` folder will apply those configs to all newly created worlds.

Dedicated servers will have this file in `/world/serverconfigs`

## __Features__

This section describes features available for the version under active development. Older versions may have different features.

### __Enchantments__

__Any/Misc__

- Soulbound: The item will remain with the owner after an untimely demise.

__Armor__

- Magic Protection: Reduces damage taken from magical sources.

_Chestplate_

- Displacement: Randomly teleports attackers away.
- Flaming Rebuke: Sets attackers on fire while knocking them away.
- Chilling Rebuke: Slows and weakens attackers while knocking them away.
- Reach: Increases the distance that the wielder can interact with things.
- Vitality: Increases maximum health.

_Helmet_

- Air Affinity: Removes the mining speed penalty when not on the ground.
- Gourmand: Food is more nourishing and satisfying when consumed.
- Insight: Increases experience gain when using the item.

__Weapons__

- Cavalier: Increases damage when riding something.
- Ender Disruption: Increases damage dealt to Ender mobs and inhibits teleportation.
- Frost Aspect: Slows and weakens the target.
- Leech: Restores health when a mob is killed.
- Instigating: Deal 2x damage if the target is at full health.
- Magic Edge: Slightly increases damage dealt and converts it to magic.
- Outlaw: Increases damage dealt to Villager mobs (and Iron Golems).
- Vigilante: Increases damage dealt to Illager mobs (and Ravagers).
- Vorpal: Randomly performs powerful attacks and decapitations.

__Tools__

- Excavating: Harvests additional blocks in a radius.

_Hoes_

- Furrowing: Tills additional blocks in a line.
- Tilling: Tills additional blocks in a radius.
- Weeding: Clears plants while tilling blocks.

__Bows__:

- Hunter's Bounty: Provides a chance of additional drops from slain animals.
- Quick Draw: Decreases the amount of time needed to fully draw a bow.
- Trueshot: Increases the accuracy and speed of arrows, and allows them to pierce.
- Volley: Additional arrows are fired with each shot. Only one arrow is consumed.

__Fishing Rods__

- Angler's Bounty: Provides a chance of catching extra items when fishing.
- Pilfering: Steals armor from a hooked target.

__Shields__

- Bulwark: Prevents the wielder from being knocked back.
- Phalanx: Allows the wielder to move faster while using a shield.

__Curses__

- Curse of Foolishness - _Helmet_: Prevents experience gain when using the item.
- Curse of Mercy - _Weapon_: Prevents a weapon from dealing a lethal blow.

### __Overrides__

For the most part, vanilla enchantment overrides simply allow the enchantment to apply to more items - Protection enchantments can apply to Horse Armor. Many Sword-only enchantments can apply to Axes as well. Two enchantments with large changes, however are Mending and Frost Walker.

If the Mending override is enabled (disabled by default), Mending is replaced with Preservation - XP orbs no longer repair the item, but the item can be repaired (and only repaired, not upgraded) at an Anvil for no additional cost. Essentially, the stacking penalty is removed, and the item can last indefinitely but requires manual repair.

If the Frost Walker override is enabled (enabled by default), then Frost Walker will also work when on Horse Armor! There is an additional configuration option to allow Frost Walker to work on Lava blocks (for both Players and Horses), creating Glossed Magma.
