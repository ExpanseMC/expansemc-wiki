# Acrobatics

Acrobatics is a skill focused around moving gracefully, reducing fall damage and avoiding attacks. Experience in Acrobatics is gained by taking fall damage, successfully rolling on the ground, or successfully dodging attacks.

120XP per half heart of damage is gained when taking fall damage. Assuming no damage is being reduced, it can also be calculated as (b - 3) * 120 where b is the amount of blocks fallen before taking damage. Any reduction of damage by use of hay bales, potions, enchantments etc. will reduce the amount of experience gained. If a roll or graceful roll as been executed, you will gain 80XP per half heart of damage instead of 120XP. This calculation uses the damage that would have been taken if you had not rolled.

Feather falling will double the amount of XP you earn from falling, regardless of its enchantment level. Keep in mind that feather falling will also reduce the amount of base damage dealt when you fall.

Dodging an attack will give 120XP per half heart of damage dodged. So if you dodged an attack that would have dealt you 3 damage, it would give you 360XP.

## Abilities

### Roll

Rolling is an active sub-skill with a passive component. It provides a chance to negate fall damage based on the player's Acrobatics skill level. At level 50, the player has a 50% chance to negate damage, or 100% if Graceful Roll is activated. The chance for success is scaled against the Acrobatics skill level in a linear curve. Every level increases the chance to roll successfully by 1%. Therefore, it will always trigger at level 100.

A normal roll can be transformed into a Graceful Roll by sneaking while falling. Doing so will double the odds to roll and the amount of damage prevented.

// todo: make table

### Dodge

Unlocks at Level 2

Dodge will give you a chance of reducing incoming damage by half. For instance, if you are receiving 6 damage, you will only receive 3 damage when successfully dodging. You will never dodge an attack if the incoming damage would be lethal, this check is done before dodge reduces incoming damage. Dodge also has a cooldown before it will award XP if the player recently respawned from a death.

Dodge reduces the players damage from various harmful sources.
