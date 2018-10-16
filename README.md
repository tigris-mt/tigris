# Dependencies
## Minetest Game
* default
* bucket
* fire
* flowers
* wool
* vessels

## 3rd party
* [smartfs](https://github.com/minetest-mods/smartfs)
  * Minetest formspecs are unwieldy.
* [playereffects](https://forum.minetest.net/viewtopic.php?t=9689)
  * Minetest doesn't support player effects.
* [player_monoids](https://github.com/minetest-mods/player_monoids)
  * Minetest doesn't support player monoids.
* [armor_monoid](https://github.com/minetest-mods/armor_monoid)
  * Necessary for compatability between armor mods.

## Optional
* [hudbars](http://repo.or.cz/minetest_hudbars.git)
  * Minetest does not have easy, built-in HUD layouting.

# Goals
* Firstly, provide a base for high-fantasy mods to work from. This is accomplished through mobs and magic.
## Danger
* Mobs.
* Hunger and thirst handled by other existing mods.
* Danger increases further away from (0, 0, 0).
## Exploration
* Require exploration into danger zone for materials.
* Require exploration into danger zone for progression.
  * Perhaps: Locating the most powerful demons which must be summoned at certain locations.
## Creating
* Crafting-based magic.
## Magic
* Detailed magic system.
* Ties into progression, mob taming, and combat.
* Provide utilities through magic (super jumps, short-range teleports, etc.)
## Progression
* Taming mobs.
* Gaining more powerful magic.
* Defeating demons(?) to progress in your conquest (re-conquest?) of the world.
  * Gain power through this.
