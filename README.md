# Version ALPHA
# Updated 10/28
Fixes to spawn mechanic and added new skills to bosses. New wild mobs added. Warning: boss triggers can bug out with server resets and can either stop or cause multiple bosses to spawn on trigger.

These mobs are used by the TFG Minecraft Server.
# Quick Navigation
Mobs
* [Spiders](#spiders)
* [Creepers](#creepers)
* [Zombies](#zombies)
* [Skeletons](#skeletons)
* [Vexs](#vexs)
* [Bosses](#boss-mobs)

Skills
* [SlownessWebShot](#slowness-web-shot-slownesswebshot)
* [WebCage](#webcage-webcage)
* [PullString](#pull-string-pullstring)
* [WebStuck](#stun-web-webstuck)
* [SpawnWeakSpiderRein](#fang-pounce-fangpounce)
* [SpiderLeap](#spider-leap-spiderleap)
* [SpawnWeakSpiderRein](#spawn-spider-reinforcements-level-1-spawnweakspiderrein)
* [SpawnClusterSpiderRein](#spawn-cluster-spider-reinforcements-level-2-spawnclusterspiderrein)
* [SpawnDirectRandomTargetSpiderRein](#spawn-cluster-spider-reinforcements-direct-level-1-spawndirectrandomtargetspiderrein)
* [SummonBabyZombie](#summon-baby-zombie-summonbabyzombie)
* [LeaperLeap](#leaper-leap-leaperleap)
* [InfectPetrify(Zombie)](#infect-petrify-zombie-infectpetrify)
* [TryFullPetrify(Zombie)](#try-full-petrify-zombie-tryfullpetrify---full-petrify-fullpetrify)
* [HardResistance](#hard-resistance-hardresistance)
* [SlamStrike](#slam-strike-slamstrike)
* [TossMove](#toss-tossmove)
* [Gust](#gust-gust)
* [LevetationShot](#levetation-shot-levetationshot)
* [GrabShot](#grab-shot-grabshot)


# Mobs
Note: Range is measured in blocks. Damage and Health are in hitpoints (1 player heart = 2 hitpoints). Normal labels indicate vanilla stats for whatever category it is placed under. Cooldown times are in seconds. Cooldowns are determined by mob unless stated otherwise.
## Spiders
### Weaver Spider
Type: Cave Spider\
Health: 24\
Base Damage: Normal\
Abilities:
* Slowness Web Shot | Cooldown: 10 | Range: On Sight

### Leaping Spider
Type: Cave Spider\
Health: 24\
Base Damage: Normal\
Abilities:
* Spider Leap | Cooldown: 6.5

## Creepers
### Leaper
Type: Creeper\
Health: Normal\
Base Damage: Normal\
Abilities:
* Leaper Leap | Cooldown: 15 (Skill based)

## Skeletons
### Melee Skeleton
Type: Skeleton\
Health: Normal\
Base Damage: 3.5\
Equipment: Normal\
Abilities: None

### Angry Skeleton
Type: Skeleton\
Health: 50\
Base Damage: 8\
Equipment: Armor vanilla spawn
* Mainhand Stick

Abilities: 
* Summons [Vengeful Soul](#vengeful-soul) on death

## Zombies
### Budding Zombie
Type: Zombie\
Health: Normal\
Base Damage: Normal\
Equipment: Normal\
Abilities:
* Summon Baby Zombie | Cooldown: 10

Notes:
* Runs away from players, wolves, and golems

### Petrifying Zombie
Type: Zombie\
Health: Normal\
Base Damage: 10\
Equipment: Armor Stats - (+3 armor, 50% knockback resistance, -2% movement speed)
* Head CobbledHead
* Chest PetrifiedChest
* Legs PetrifiedLegs
* Feet PetrifiedFeet
* Mainhand None

Abilities:
* Infect Petrify [Zombie] | Passive
* Try Full Petrify [Zombie] | Cooldown: 10

Notes:
* Targets Zombies over players

### Petrifying Zombie Infected
Type: Zombie\
Health: Normal\
Base Damage: 10\
Equipment: Armor Stats - (+3 armor, 50% knockback resistance, -2% movement speed)
* Head CobbledHead
* Chest PetrifiedChest
* Legs PetrifiedLegs
* Feet PetrifiedFeet
* Mainhand None

Abilities:
* Infect Petrify [Zombie] | Passive
* Try Full Petrify [Zombie] | Cooldown: 10

Notes:
* Targets Zombies over players

### Petrified Zombie
Type: Zombie\
Health: 40\
Base Damage: 25\
Equipment: Armor Stats - Chest,Legs,Feet(+3 armor, 50% knockback resistance, -2% movement speed)
* Head StoneHead (+20 armor, 200% knockback resistance, -15% movement speed)
* Chest PetrifiedChest
* Legs PetrifiedLegs
* Feet PetrifiedFeet
* Mainhand None

Abilities:
* Hard Resistance | Passive

## Vexs
### Vengeful Soul
Health: 35\
Base Damage: 10\
Equipment: 
* Mainhand Stick

Abilities:
* Random Pick(66.6% Grabshot, 33.3% Levetation Shot) | Cooldown: 11 | Range: On Sight

Modifiers:
* +40% Movement Speed

## Boss Mobs
### Mira
Type: Spider\
Health: 800\
Base Damage: 14
Abilities: (Pools detect players within a 24 block radius range)
* Pool 1 (1-4 player fights) | Cooldown: 5 | Duration: 0.25 (includes delays)
  * Random Pick(33.3% Slowness Web Shot, 33.3% Spider Leap, 33.3% Spawn Spider Reinforcements Level 1)
  * Random Pick(50% Slowness Web Shot, 50% Web Stuck) | Range: 24 | Target Limit: 2 (Random)
* Pool 2 (5-8 player fights) | Cooldown: 9
  * Random Pick(33.3% Spawn Spider Reinforcements Level 1, 33.3% Spawn Cluster Spider Reinforcements Level 2, 33.3% Fang Pounce)
  * Web Cage | Range: 24 | Target Limit: 2 (Random)
* Pool 3 (7+ player fights) | Cooldown: 15 | Duration: 5.75 (includes delays)
  * Random Pick(33.3% Spawn Spider Reinforcements Level 1, 33.3% Spawn Cluster Spider Reinforcements Level 2, 33.3% Spawn Cluster Spider Reinforcements [Direct] Level 1)
  * Pull String | Range: 24 | Target Limit: 7 (Random) | Repeated: 5 times with 0.25 second intervals
  * Web Stuck | Range: 24 | Target Limit: 7 (Random)
* On Spawn Abilities
  * Spawn Cluster Spider Reinforcements Level 1
  
Notes:
* Mira has 3 separate skill pools. The pools will stack on top of each other as more players fight this boss. This is to scale the difficulty depending on how many players are fighting this boss at the same time. This boss has been tested for up to 10 player fights.
* Mira is currently set to be an easy boss, this is being reconsidered due to changing skill pools

### Ent
Type: Iron Golem\
Damage: 10
Notes:
* This is set to be an easy boss, skills will be defined later

## Skills
Note: Units of range are in blocks; Damage are in hitpoints (1 player heart = 2 hitpoints)
### Slowness web shot (SlownessWebShot)
Range: Determined by mob\
Damage: 1\
Effects: Slowness 3 | 5 seconds\
Description: Visually produces a line of crit particles indicating the skill was used. This shot is hitscan.

### Webcage (WebCage)
Range: Determined by mob\
Damage: 0\
Duration: 5 seconds\
Description: Encases targets inside cobwebs for the duration listed. Players are able to break out of the cage, block materials do not drop when broken. Targets can be hit by this skill while they are off the ground.

### Pull string (PullString)
Range: Determined by mob\
Damage: 1\
Description: Visually produces a line of crit particles indicating the skill was used. Pulls target towards the caster. Strength of pull is determined by the distance between the target and caster, the further away the stronger the pull. This shot is hitscan.

### Stun web (WebStuck)
Range: Range of [Leap's](#leap) velocity; AEO determined by mob\
Damage: 0\
Effects: Blindness | 5 seconds\
Stun: 3 seconds\
Description: Caster leaps towards target(or a random target if selector is set to multiple targets) and causes all targets within a given range to be stunned and blinded.

### Fang pounce (FangPounce)
Range: 3 blocks in a straight line from caster\
Damage: 5 + Effects\
Effects: Poison 3 | 5 seconds\
Description: All targets in front of the caster within a 3 block straight line is thrown away from the caster. Targets are damaged and inflicted with poison.

### Spider leap (SpiderLeap)
Range: Velocity of 400 (not in blocks)\
Description: Caster leaps towards target, landing location is not perfectly accurate

### Spawn spider reinforcements level 1 (SpawnWeakSpiderRein)
Range: 5 block radius around caster\
Reinforcements: 3 Cave Spiders

### Spawn cluster spider reinforcements level 2 (SpawnClusterSpiderRein)
Range: 5 block radius around caster\
Reinforcements: 3 Cave Spiders; 2 [Leaping Spiders](#leaping-spider); 3 [Weaver Spiders](#weaver-spider)

### Spawn cluster spider reinforcements [Direct] level 1 (SpawnDirectRandomTargetSpiderRein)
Range: 24 | 5 block radius around target\
Reinforcements: 2 Cave Spiders; 2 [Weaver Spiders](#weaver-spider)

### Summon baby zombie (SummonBabyZombie)
Range: 1 block radius around caster\
Reinforcements: 1 Baby Zombie

### Leaper leap (LeaperLeap)
Range: Velocity of 500 (not in blocks)\
Cooldown: 15 seconds\
Description: Caster produced an aura of smoke particles around them 0.25 seconds before leaping towards target. This skill was intended for Creepers.

### Infect petrify [Zombie] (InfectPetrify)
Restriction: Can only be used by petrifying mobs\
Range: Melee\
Description: Any Zombies hit will be immediately replaced by a [Petrifying Zombie Infected](#petrifying-zombie). A loud crack sound will be played where the zombie was infected which can be heard 16 blocks away.

### Try full petrify [Zombie] (TryFullPetrify) -> Full petrify [FullPetrify]
Restriction: Can only be used by petrifying mobs\
Success Rate: 5%\
Description: Any Zombie in the infective stage will attempt to convert into a [Petrified Zombie](#petrified-zombie). On a failed conversion, the Zombie will remain in the infective stage. On a successful conversion, a loud crack sound will be played where the zombie was converted which can be heard 16 blocks away.

### Hard resistance (HardResistance)
Note: Fire causes the skill to be triggered, this is an unexpected behaviour and may be removed in the future.\
Restriction: Will only activate if struck by a melee weapon or tool\
Range: Melee\
Description: Throws any entity that hits the caster away from them. An anvil landing sound will be played where the caster was struck. Sound can be heard 1.6 blocks away.

### Slam Strike (SlamStrike)
Range: 50\
Damage: 10\
Description: Jumps up in the air with a velocity of 100 and throws all targets away from caster. Rings of block_crack particles emit from the caster for 50 blocks.

### Toss (TossMove)
Range: Determined by mob\
Damage: 12\
Description: Caster grabs and throws target upwards away from the caster. A sound indicating the skill emits from the caster and can be heard 32 blocks away.

### Gust (Gust)
Range: Determined by mob\
Description: Pulls all targets within the given range towards the caster with a velocity of 50.

### Levetation Shot (LevetationShot)
Range: Determined by mob\
Damage: 2\
Effects: Levetation 1 | 10 seconds\
Description: Visually produces a line of snowballpoof particles indicating the skill was used. This shot is hitscan.

### Grab Shot (GrabShot)
Range: Determined by mob\
Damage: 8\
Description: Visually produces a line of crit particles indicating the skill was used. Pulls target towards the caster when hit with a velocity of 3. This shot is hitscan.
