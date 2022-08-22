---
title: "King's Fall"
category: destiny
tags: raids
---
{% if site.data.destiny.power.min > 1560 %}
{% assign power = site.data.destiny.power.min %}
{% else %}
{% assign power = 1560 %}
{% endif %}

King's Fall is back. Long live the king.

# Prereading

- This isn't a guide, this is a mechanic explanation. There's many ways to handle these mechanics - do whatever's best for your raid team.
- Light for final encounter is {{power}}.

## Ammo Generation
This section is for you, Aeon users.
- Presumably no to few champions on Legend. Hive and Taken are in this raid, so any of the three Champion types could be present.
- Presumably many champions on Master.

---

# Hall of Souls {#outside}

## Objective
Activate all six statues.

## Mechanics
**Statues**
: Six statues are in the center of the map - activating each of them will spawn a portal and end the encounter. Only statues marked by "dark energy" (Taken particles) can be activated. To activate a statue, it must be deposited at twice in quick succession. Successful rapid dunks will open up the next statue. Taking too long will cause the last completed statue to revert. The text log "A statue hums with dark energy" appears when the eligible statue to dunk at has changed.

### Interactables
**Relics**
: Relics are used to deposit at statues and spawn in sets of two. Relic holders gain the normal relic melee. When a relic is picked up from its starting position, a barrier spawns. The first set of relics are near the statues in the middle of the map and get progressively further away from the center, scaling with how many statues are activated. If they are on the ground for too long, they respawn at their initial pickup location. When they are dunked at a statue, they will spawn again after the current statue resolves.

**Barriers**
: The barriers that are triggered by relics spawn in doorways depending on which position that the relic has been acquired. They are immune to damage from relics and are vulnerable to gunfire. Barriers are impassible to players.
---

# The Crux {#platforming}
jump lol, also barriers can be held open by plates. chest here somewhere.

---

# Basilica {#totems}

Encounter starts by picking up the Brand of the Weaver. The room is split into two, with one Annihilator Totem on each side.

## Objective
The objective of the encounter is to open the door by depositing stacks at its entrance.

### TL;DR
- Get brands
- Sit on plates
- Kill adds
- Pass brand to ally when it expires
- Deposit stacks at door

## Mechanics
**Annihilator Totems**
: Same thing as in *Pit of Heresy*. If any of the two totems fully charge, the raid wipes. Can be prevented by standing on the plates beneath them. The rooms that they are in are engulfed in fog.

**Fog**
: Presumably either kills all players that it touches or deals extremely high damage.

### Statuses
**Brand of the Weaver**
: Lasts 30 seconds. Found on the pedestals near the entrance of the totem rooms. Creates a safe zone around the player that negates the fog, granting the Aura of the Weaver buff while inside. Once the buff resolves, it is granted to a random player inside the aura, if any others are present, and grants the wielder 10 stacks of Deathsinger's Power.

**Aura of the Weaver**
: Allows players to pass through the fog without penalty.

**Deathsinger's Power**
: Does nothing on its own. Allows players to deposit the stacks onto the door plate to progress towards the door opening. Supposedly makes the afflicted players vulnerable to fog through the Weaver aura.

### Interactables
**Weaver Pedestal**
: Holds the Brand of the Weaver buff entity. Only active if their respective Brand is lost.

**Annihilator Plates**
: Prevents the Annihilator Totem above the plate from charging and slowly reverts their charge.

**Door Plate**
: Opens the door when enough stacks of Deathsinger's Power have been deposited.

## Rewards
One of the following:

## Challenge: 

---

# what is this place called? {#warpriest}

Encounter starts by activating all three plates.

## Objective
The objective of the encounter is to kill the Warpriest.

### TL;DR
- Kill all adds
- Play Simon Says
- Get buff
- Do damage to boss
- Branded player maintains buff by killing adds at 0:02
- Hide from wipe mechanic

## Mechanics

**Monoliths**
: The big rock in front of each plate. During the glyph sequence, each monolith will glow from the front. The order that they glow in denotes the sequence that the plates must be activated in. During the Oculus mechanic, one monolith will be purged from the arena with the text prompt, "The Warpriest draws power from a monolith".

### Statuses
**Brand of the Initiate**
: Lasts 10 seconds. Has 5 stacks. Obtained by being the player to resolve the final plate. Continously grants the Aura of the Initiate buff to all nearby allies. Once the buff resolves from time, the player who had it dies. Killing an enemy resets the timer and removes a stack or removes the buff if all stacks are gone. When the buff expires, damage phase ends with the text prompt, "The Warpriest calls upon the Oculus". Also has the effect of Aura of the Initiate.

**Aura of the Initiate**
: Allows players to damage the Warpriest.

### Interactables
**Plates**
: Used in the glyph sequence. Player who activates the final plate gains the Brand of the Initiate buff.

### Mechanically Relevant Enemies
**Warpriest**
: Large Knight boss. Immune to damage. Casts a LoS wipe attack after each damage phase, destroying a monolith.

**Hallowed Knight**
: Major Knight that spawns when trash mobs are dead. Spawns in sets of three, one per plate. Killing them starts the glyph sequence.

## Rewards
One of the following:

## Challenge: 

---
# labyrinth

labyrinth. if it's like d1, right, 2 lefts, right. hidden chest: r, l, straight, jump over L wall. r, straight x2, right, straight x1, l, straight x2, l. r, straight x2, l, l, r, r, done.

---

# Golgoroth's Cellar {#golgoroth}

Encounter is started by breaking the dark bubble.

## Objective
Kill Golgoroth.

### TL;DR
- Kill adds
- Get and juggle Gaze, point towards team
- Team shoots ball to enable damage phase
- Leave pit when all balls have been used

## Mechanics
**Tablet of Ruin**
: Whenever a player dies, a rune is added to the large black column in the back of the room. If six runes are present, Exodia is summoned and instantly knocks your raid's life points to zero.

### Statuses

**Golgoroth's Gaze**
: Caretaker will inflict a debuff of the same name on someone who shoots him in the back with the text prompt, "Golgoroth shifts his Gaze". While gazed upon, Golgoroth will only cast Axion Darts at the debuffed player instead of using the normal Ogre attack kit. Lasts 20 seconds, only one gaze can be active at a time. Breaking line of sight instantly removes the debuff. Gaining Gaze while it is active will purge it on any other players. If gained during damage phase, a wave of Cursed Thrall spawn in the pit with the boss.

**Pool of Reclaimed Light**
: Once all the adds are dead, six orbs of light (not to be confused with orbs of power) will spawn on the ceiling. Shooting down an orb will enable the boss to be damaged from those inside the temporary pool that it drops. Once all six orbs are gone, damage phase ends (and some stuff happens idk what).

**Unstable Light**
: Lasts 7 seconds after an orb hits the ground. Two players do their best Cursed Thrall impression, dealing damage to all nearby allies when the debuff expires.

### Mechanically Relevant Enemies
**Golgoroth**
: Immune to damage everywhere but his exposed back. Shooting him in the back will grant Golgoroth's Gaze. Weak spot is his glowing core on his stomach.

## Rewards
One of the following:

## Challenge: 
---

# Transept

jumping puzzler omg wowowow also there's a hidden chest in here

---

# Daughters of Oryx {#deathsingers}

## Objective
Kill the Deathsingers.

### TL;DR
- Become Emrakul, the Aeons Torn
- Use Flying to get over enemy blockers and get the Brand Claimer
- Declare attack on non-red Plainswalker
- Force enemy player to sacrifice target permanent
- Get banned in Commander
- This is staying in the final draft

## Mechanics

### Statuses

**Dirge of Unraveling / Hymn of Weaving**
: Lasts 60 seconds. When it times out, inflicts instant death. Inflicted on all players when a phase starts. No more than one Deathsinger can be singing at a time. Unraveling is from Halak and vice-versa.

**Aura of Weaving / Unraveling**
: Allows anyone inside to ignore the effect of the same debuff type and damage the Deathsinger of the same type.

**Torn Between Dimensions**
: Lasts 60? seconds. Inflicted on a random player when the phase starts. Turns their screen monochrome and allows them to stand on translucent platforms. Turns the afflicted player translucent.

**Brand Claimer**
: Used to spawn an Aura of the opposite Deathsinger that was dunked on by the sphere by running into them.

### Interactables

**Brand Claimer**
: Looks like a sphere. Spawns on a translucent platform above the arena. Grants a status effect of the same name.

**Plates**
: There are four plates in the room. These plates spawn translucent platforms. The height of the platforms depends on the order in which they are hit. The exact specifics of how the plates spawn are unknown to me, but TL;DR: Start CCW of where the Taken Sphere spawns and then hit plates going CCW. Platforms are despawned when the Brand Claimer is consumed and prints a matching log to the kill feed.

### Mechanically Relevant Enemies
**Ir Halak, Deathsinger**
: Hive Wizard boss. Immune to being damaged by everything that isn't under the effect of Aura of Unraveling. Creates Unraveling statuses.

**Ir Anûk, Deathsinger**
: Same as above, but replace Unraveling with Weaving.

## Rewards
One of the following:

## Challenge: 

---

# Oryx, The Taken King {#oryx}

Pick up the spark to start the encounter.

## Objective
Kill Oryx, The Taken King.

### TL;DR
- Obtain Torn from Oryx, try not to reuse the same MTG joke again
- Kill all the Light-Eaters ASAP
- Activate all 4 plates CCW, get the Brand Claimer buff
- Brand the Vessel of Oryx, get mechanic eligibility buff
- Continously deal damage to Oryx's chest to maintain damage eligibility
- Plate runners go detonate Corrupted Light
- If Oryx is below 50%, complete the Shade minigame.
- Repeat until final stand (~5% HP), shoot him during it

## Mechanics

### Interactables

**Spark**
: Entity that Oryx creates when he casts his slam on a plate. Grants Torn Between Dimensions.

**Brand Claimer**
: Looks like a sphere. Spawns on a translucent platform above the arena. Grants a status effect of the same name.

**Plates**
: There are four plates in the room. These plates spawn translucent platforms. The height of the platforms depends on the order in which the plates are activated. The exact specifics of how the plates spawn are unknown to me, but TL;DR: Start where Oryx slammed and go CCW. Platforms are despawned when the Brand Claimer is consumed and prints a matching log to the kill feed.

**Corrupted Light**
: Looks like a Taken Blight. When a player stands inside one, it detonates shortly afterwards dealing 6.25% of Oryx's HP if he is stunned. Can be removed by non-Ogre Light-Eaters.

**Dome**
: The thunderdome is active while the Shade of Oryx is alive. If any players or rank-and-file enemies touch it, they teleport inside the dome. All players inside are teleported out when the Shade dies. Players are periodically teleported inside while the dome is active.

**Darkness Dimension**
: Debuff from being inside the dome. Supposedly prevents natural regeneration. When all raid members have this, the raid wipes.

### Statuses

**Brand Claimer**
: Used to slay the Vessel of Oryx and obtaining the Brand of Immortality.

**Torn Between Dimensions**
: Lasts 60? seconds. Inflicted on a random player when the phase starts. Turns their screen monochrome and allows them to stand on translucent platforms. Turns the afflicted player translucent.

**Brand of Immortality**
: Continously grants the Aura of Immortality buff to all nearby allies and grants the effect of Aura of Immortality to self. Lost upon dying or phase transition. Obtained from the Vessel of Oryx.

**Aura of Immortality**
: Immune to damage from everything that isn't Oryx, The Taken King. Presumably allows damaging Oryx's crit spot.

**Channeling Corrupted Light**
: What it says on the tin. Detonates all Corrupted Lights that the player is standing in after roughly 2 seconds of activation.

### Mechanically Relevant Enemies
**Oryx, The Taken King**
: Attacks by routinely slamming the ground infrequently, presumably killing all Guardians hit. First slam each phase spawns a Spark. Immune to damage aside from his crit spot during the effect of Brand of Immortality and his raid-wipe channel when below 5% HP.

**Light-Eater Ogre**
: Drops Corrupted Light at location of death.

**Light-Eater Knight**
: Consumes Corrupted Light when near it.

**Vessel of Oryx**
: Consumes Corrupted Light when near it. Immune to all damage, but can be instantly killed by the Brand Claimer. Drops the Brand of Immortality buff.

**Shade of Oryx**
: Keeps the dome active when he is alive.

## Rewards
One of the following:

## Challenge: 

---

# Master Difficulty {#master}

Master difficulty applies the following changes to the raid:
- The power level of each encounter is boosted to Master power level (Pinnacle Cap + 20)
- Match Game is enabled
- To be filled in further when Master KF is released.

## Reward Adjustments

Unknown as of writing.

---

# End {#end}

## Spoils Chest
Weapons and armor that have obtained from the raid can be purchased here. The first weapon purchase per week is guaranteed to have Deepsight Resonance, on an account-wide lockout. Subsequent purchases during the lockout have no chance, if any, to be Deepsighted.