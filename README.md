# Version ALPHA
# Updated 10/28
Fixes to spawn mechanic and added new skills to bosses. New wild mobs added. Warning: boss triggers can bug out with server resets and can either stop or cause multiple bosses to spawn on trigger.

## Spiders
### Weaver Spider
Type: Cave Spider\
Damage: Normal\
Abilities:
* Shoots slowing web every 10 seconds and applies slowness 2 on the target for 3 seconds
* Damages player for 1 hp

### Leaping Spider
Type: Cave Spider\
Damage: Normal\
Abilities:
* Leaps towards target every 6.5 seconds

## WildSpawn Mobs
### Leaper
Type: Creeper\
Damage: Normal\
Notes:
* Gives a visual queue when creeper is about to leap
Abilities:
* Leaps towards the target at medium distance
* Can only leap once

### Melee Skeleton
Type: Skeleton\
Damage: 3.5\
Notes:
* Does not spawn with a weapon on hand
Abilities:
* Runs faster than zombies

### Budding Zombie
Type: Zombie\
Damage: Normal\
Notes:
* Runs away from players
* Creates a pop sound when a baby zombie is spawned
Abilities:
* Spawns a baby zombie every 10 seconds

### Petrifying Zombie
Type: Zombie\
Damage: 4.5\
Notes:
* Infected state has cobbled head
* Has a medium amount of armor
Abilities:
* Attacks nearby zombies to infect them
* Turns into a Petrified Zombie after 30 seconds of infection
* Reduced knockback

### Petrified Zombie
Type: Zombie\
Health: 30\
Damage: 10\
Notes:
* Has high amount of armor
* Is not infectious
* Is very slow
Abilities:
* Knock enemies back when melee attacked
* Reduced knockback

## Boss Mobs
### Mira
Type: Spider\
Damage: 10
Notes:
* Mira has 3 separate skill pools. The pools will stack on top of each other as more players fight this boss. This is to scale the difficulty depending on how many players are fighting this boss at the same time. This boss has been tested for up to 10 player fights.
* Mira is currently set to be an easy boss, this is being reconsidered due to changing skill pools

### Ent
Type: Iron Golem\
Damage: 10
Notes:
* This is set to be an easy boss, skills will be defined later
