---
title: "King's Fall"
category: destiny
tags: raids
---
{% assign power = 1580 %}
{% if site.data.destiny.power.min > power %}
{% assign power = site.data.destiny.power.min %}
{% endif %}

Hollow Knight joke here.

# Prereading

- This isn't a guide, this is a mechanic explanation. There's many ways to handle all of these mechanics - do whatever's appropriate for your raid team.
- Light for final encounter is {{power}} on Legend.
- Taken Spec is enabled, but **all** encounter bosses are treated as Hive. There is one spot per encounter where there are more-or-less exclusively Taken enemies - power to you if you want to deal with menuing to optimize damage/clear on trash with your non-boss weapons.

## Ammo Generation
This section is for you, Aeon users.
- E1, E2 and E3 have miniboss Knights or Wizards that can be finished for heavy drops. E4 and E5 have none on Legend.
- On Master difficulty, there are several Champions in every encounter and no more than two types per encounter.

---

# Hall of Souls {#outside}

## Objective
Activate all six statues to spawn the exit portal.

## Mechanics
**Statues**
: Six statues are in the center of the map - activating each of them will spawn the exit portal. Only statues marked by "dark energy" (Taken ball) can be activated. To activate a statue, it must be deposited at twice in quick succession. Successful rapid dunks will open up the next statue. The text log "A statue hums with dark energy" appears when the eligible statue to dunk at has changed.

### Interactables
**Relics**
: Relics are used to deposit at statues and spawn in sets of two. Relic holders gain the normal relic melee and lose all other class functionality, including Movement Abilities. Each set lasts for a certain amount of time when any in the set are obtained, depending on set. If a relic is dropped or runs out of time, it respawns. Using a Class Ability also drops the relic. Players with relics have an icon that can be seen through terrain. The relics also glow more intensely the closer they are to timing out.

: The first time a relic is picked up from its starting position, all Taken enemy spawns and barriers that would be blocking its travel path activate (requires verification, testing on the first set would not respawn any enemies or barriers). The first set of relics are near the statues in the middle of the map and get progressively further away from the center, scaling with how many statues are activated. When they are dunked at a statue, they will spawn again after the current statue resolves.

**Barriers**
: There are five Taken barriers that spawn in doorways - one in the middle and two on each side. While a barrier is up, they prevent travel through them. They are triggered by relics being picked up and are immune to damage from relics. The Taken core on each door is vulnerable to damage.

### Statuses
**Time Remaining**
: Self-explanatory. Initial time allotted appears to be passively rolling from anywhere from 48 seconds to 75 seconds and is only shown to all players when all spawn locations do not have relics on them, but might be dependent on set number. Upon timing out, respawns all relics. Resets to 4 seconds when one is deposited.

## Triumph Challenge: Controlled Dunks
: "Complete the Hall of Souls encounter while never letting the same player deposit relics until everyone else has."

## Rewards
One of the following, at world drop light:
- {{ site.data.destiny.drops.kf.scout_rifle }}
- Class Item

---

# Offering (Bonus Boss Chest) {#offering}

Below the platform that the portal is on, there are three runes displayed out of a pool of 9. Scattered throughout the raid are green flaming plates, each of them holding a specific rune when it's activated. Activating the **three and only the three** displayed will play a jingle and post the text, "The runes accept your offering". grants an additional drop from final boss that has a raid weapon with guaranteed Deepsight Resonance. Shooting a plate with an activated rune will deactivate it and vice-versa.
- The lockout is weekly, once per account.
- To be explicit, it must be done in one complete run.
- You cannot backtrack without OoBing - the doors close behind you in every encounter. If it is anything like Vow of the Disciple, OoBing may cause softlocks.
- **The ninth rune does not properly activate after the fourth encounter starts** (untested as of the 9/12/2022 patch).

### Locations
There are 9 runes in the raid. Ishtar Collective has no data on the names aside from the Typing rune, so have fun communicating this to your raid. I included the nicknames that my group decided on, but feel free to use your own.

|Rune|Nickname|Location|
|:---:|:---------:|------------------------------------|
|!["Table"]({{"assets/images/destiny/runes/table.png" | relative_url}}){:height="50px" width="50px"}|Table|In the Crux, after the first jump to the swaying pillars, look below from where you jumped from.|
|!["Crosswalk"]({{"assets/images/destiny/runes/crosswalk.png" | relative_url}}){:height="50px" width="50px"} | Crosswalk | Above the door, facing the first secret chest.|
|!["Clippy"]({{"assets/images/destiny/runes/clippy.png" | relative_url}}){:height="50px" width="50px"}|Clippy|In the room with the left Annihilator Totem, on the wall with the balcony.|
|!["Volcano"]({{"assets/images/destiny/runes/volcano.png" | relative_url}}){:height="50px" width="50px"}|Volcano|In Warpriest's room, on the wall of the right-side balcony next to the door.|
|!["Typing"]({{"assets/images/destiny/runes/typing.png" | relative_url}}){:height="50px" width="50px"}|(Is) Typing / Door / Treasure / Chamber|Immediately before Golgoroth's room, near the lip of the last pit.|
|!["X"]({{"assets/images/destiny/runes/x.png" | relative_url}}){:height="50px" width="50px"}|X|In the left-side cubby hole in Golgoroth's arena.|
|!["England"]({{"assets/images/destiny/runes/saucyunionjack.png" | relative_url}}){:height="50px" width="50px"}|(COME ON) England|Next to the third secret chest.|
|!["Cone"]({{"assets/images/destiny/runes/cone.png" | relative_url}}){:height="50px" width="50px"}|Cone|In the ceiling immediately before the door after the Transept platforming segment.|
|!["what"]({{"assets/images/destiny/runes/what.png" | relative_url}}){:height="50px" width="50px"}|what|Above the door in the final room, facing the sisters.|

---

# Basketball Court / {{ site.data.destiny.drops.kf.exotic }} Catalyst {#catalyst}

If anyone in the raid has {{ site.data.destiny.drops.kf.exotic }}, the Basketball Court becomes accessible and contains its catalyst. To play some B-ball, all three hidden statues in the raid must be activated. To activate them, their respective dormant plate must be activated. When activated by a user who has the exotic equipped, a nearby statue will start accepting relics while Major Shriekers and 4 relics appear around the area with a time remaining of 1:30 for each set - there also appears to be a pool of spawn locations and 4 of them are chosen. Dunking all the relics in rapid succession will activate the statue. Failure to do so will presumably reset the plate. Activating all the statues will open the door to the court.

The plates are in the following three locations:
- In the Hall of Souls, in the back left building in the distance. The statue is located behind the portal. This plate can only be activated before the first relics are grabbed.
- In Golgoroth's Maze, at the second hidden chest location. Statue is inside a pit before exiting the area, north of the chest.
- In Transept, at the plate  Statue is at the start of the platforming segment, on new invisible platforms.

Inside, there is a final fourth plate. Rapidly dunking inside the court will grant the catalyst to each member in the raid who has {{ site.data.destiny.drops.kf.exotic }} in collections, exact number of dunks required is unknown.

---

# Portico {#platforming}

Cross the expanse by jumping on tombships.

Jump on the first tombship to activate it. Make the following jumps in order:
- Jump on the tombship visible on the direct right, it will start to pass underneath the first ship
- Jump on the tombship visible to the right as it intersects the second ship
- Jump on the tombship visible to the left as it intersects the third ship
- Jump to the platform attached to the upcoming left side pillar

This is an optional player respawn point. Make the next jumps in order:
- Jump on the tombship underneath the platform when it approaches
- Jump on the tombship that spawns on the left as it intersects
- Jump **over** the tombship that blocks the way of the one that is active (you can also just move around it)
- Jump on the tombship that spawns on the right
- Jump on the tombship that spawns on the right
- Jump on the tombship that spawns on the left
- Jump on the tombship that spawns to the north
- Jump to solid ground

There are two sets of buttons here, one before the tombship and one afterwards. Any set being activated will deactivate the barrier that allows players on the ship to cross without being pushed into a death plane.

## Hidden Chest

On the left side of the wall on the final tombship, there is a hidden chest. The door is only open while the barrier is deactivated, but can be bypassed from the inside of the barrier by using Stasis Crystals to climb the wall instead. Chest gives a random KF armor piece or weapon that has been obtained and a KF raid mod that hasn't been obtained.

---

# Basilica: Door ![Unstoppable Champions]({{"assets/images/destiny/champion_icons/Unstoppable_Champion_icon.png" | relative_url}}){:height="20px" width="20px"} {#totems}

Encounter starts by picking up any Brand or attacking the enemies. The room is split into two, with one Annihilator Totem on each side. Taken enemies path to the left room, Hive enemies try to path to the right. Sword Knights will path to nearby allies instead. Unstoppable Ogres and the Hive that are alive at the start will path to the middle plate. Wizards and the Blightguard stay on their platforms.

## Objective
The objective of the encounter is to open the door by depositing roughly 200 stacks at its entrance.

### TL;DR
- Get Brands
- Sit on plates
- Kill Wizards, Ogres and Blightguards on sight
- Only Brand users kill trash (preferably including the starting wave)
- Brand Claimers take the Brands before they blow up
- Deposit stacks at door

## Mechanics
**Annihilator Totems**

: Same thing as in *Pit of Heresy*. If any of the two totems fully charge, the raid wipes. Can be prevented by standing on the plates beneath them. The rooms that they are in are engulfed in Blight auras.

**Blight of Weaving / Unraveling**

: Deals low damage over time, incrementing per successive hit. The seventh tick or so will instantly kill its victim. The Weaving blight is on the left side and the Unraveling one is on the right.

### Statuses
**Brand of the Unraveler / Weaver**

: Lasts 30 seconds. Found on the pedestals near the entrance of the totem rooms - Unraveler on the left side and Weaver on the right. Creates a safe zone around the player that negates the (opposite type?) damage aura, granting their respective Aura buff while inside. Once the buff times out, the player who has it dies.

: Killing a minor Hive enemy with Brand of the Unraveler grants a stack of Deathsinger's Power and a major Hive gives 3 stacks. With the Weaver brand, you gain a stack from killing a minor Taken enemy instead and 3 stacks from a major Taken.

**Aura of the Unraveler / Weaver**

: Allows players to pass through the aura without penalty.

**Brand Claimer**

: {% capture status_brand_claimer %}Lasts 30 seconds. Allows passing of any brand by interacting on the aura while holding the buff.{% endcapture %} {{ status_brand_claimer }} Resets the timer on a passed Brand of the Unraveler or Brand of the Weaver.

**Deathsinger's Power**

: Offers no benefit on its own. Can be deposited at a rate of two at a time while standing the door plate. Supposedly negates any aura effects while active. Prevents interacting with Brand Claimer while any stacks are active.

**Annihilator Totem**

: Kills the afflicted player shortly after application. Continously inflicted on all players when an Annihilator Totem is charged. Can be cleansed if the Totem who inflicted it deactivates before the debuff resolves.

### Interactables
**Pedestals**

: Holds their side's Brand buff on the right side. Only active if their respective Brand is lost.

**Brand Claimer**

: Grants the user the status of the same name.

**Annihilator Plates**

: Prevents the Annihilator Totem above the plate from charging and slowly reverts their charge. Charges in roughly 5 seconds.

**Door Plate**

: Opens the door when enough stacks of Deathsinger's Power have been deposited, around 200. Presumably, each 65 or so will spawn an ![Unstoppable Champion]({{"assets/images/destiny/champion_icons/Unstoppable_Champion_icon.png" | relative_url}}){:height="12px" width="12px"} Ogre.

### Mechanically Relevant Enemies
**Wizard**

: A minor Wizard will spawn out of each door on the side. Killing any side's Wizard will spawn their side's Blightguard.

**Blightguard**

: Blightguards are miniboss Taken Knights. Killing them drops a Brand Claimer.

### Special Enemies
**Adepts**

: {% capture description_adept_enemy %} Major Acolytes. On death, buffs all nearby Acolytes, augmenting their ranged attack to a Ogre's eye laser beam attack.{% endcapture %}{{description_adept_enemy}} Only present at the door.

## Challenge: The Grass is Always Greener

No player may hold the same Brand type twice in succession.

: A Behemoth point of view for Totems Contest Challenge Mode can be found [here](https://www.youtube.com/watch?v=lNSwHrKRpH4).

## Triumph Challenge: Overzealous

Each plate can not have more than one player on it at a time.

## Rewards
One of the following:
- {{ site.data.destiny.drops.kf.scout_rifle }}
- {{ site.data.destiny.drops.kf.machine_gun }}
- Chest
- Legs
- Class Item

---

# Basilica: Interior {#warpriest}

Encounter starts by activating all three plates at the same time. Add spawns change depending on boss health and monolith count.
- While 3 monoliths are active: Rank and file Hive, Revenant Knights and (ultra) Blistered Wizards. All enemies spawn through the arena doors.
- Above 50% HP and while there are more than two monoliths: Same as above but with Cursed Thralls and Adepts.
- Otherwise: All adds replaced with Taken; including Hobgoblins, Minotaurs and ultras. All enemies spawn through ordinary Taken spawns (aka there are more spawns and at different locations).

## Objective
The objective of the encounter is to kill the Warpriest.

### TL;DR
- Kill all adds
- Touch first plate, get starting plate intel
- Hold successively called plates while calling out next plate
- DPS while killing the Blightguards
- Claimer dance to extend damage phase, twice
- Hide from wipe mechanic

## Mechanics

**Monoliths**

: The big rock in front of each plate. Can glow on its back, either telegraphing which plate is the first for the glyph sequence or which code is next for in the sequence.

: During the Oculus mechanic, any monoliths that were used to hide to dodge Oculus will be purged from the arena. For subsequent glyph sequences, a glowing red pillar will appear in their place if that monolith would have been glowing.

**Glyph Sequences**

: Glyph sequences start once all major Knights have been slain. All sequences start with reading sequence and are followed by a normal sequence.

: During the glyph **reading** sequence, the middle plate will glow green. Any player standing on the middle plate is shown which side is first for the following glyph sequence, shown by its back glowing. The middle monolith's back cannot be seen from the middle plate.

: During the glyph sequences, a player must stand on the correct plate to reveal which next plate needs to be held down. Holding down all three plates will grant Brand of the Initiate to the player who stood on the final plate. If the left and right plates are held down simultaneously before the glyph reading sequence's plate activates and all three plates become activated, it presumably gives it to whoever would have finished it normally. 

: If a sequence is done out of order (or presumably if too much time elapses), a text line is printed in chat that the glyphs are released and lights all plates on fire and turns them glowing red, dealing damage for every couple of ticks that players are touching them. When all players are off the plates, the glyphs become unreleased. If the glyphs are released for too long, the raid gets architected.

### Statuses

**Brand Claimer**

: {{status_brand_claimer}} Decreases the amount of stacks on Brand of the Initiate by 1.

**Brand of the Initiate**

: Lasts 10 seconds. Has 3 stacks. Obtained by being the player to resolve the final plate. Continously grants the Aura of the Initiate buff to all nearby allies. Once the buff resolves from time **if multiple stacks are present**, the player who had it dies. When the buff expires, damage phase ends with the text prompt, "The Warpriest calls upon the Oculus". Also has the effect of Aura of the Initiate.

**Aura of the Initiate**

: Allows players to damage the Warpriest.

**Searing Torrent**

: Flavor status. Shows up when the Oculus is attacking and vanishes afterwards.

### Interactables
**Plates**

: Used in all glyph sequences. Player who activates the final plate gains the Brand of the Initiate buff. Any time Glyphs are released (indicated in kill log) by stepping on any plates that are not part of a sequence, medium reocurring damage will be inflicted to all players on any plate until all players are off of the plates. This is also indicated by the plates glowing red and searing fire. 

### Mechanically Relevant Enemies
**Warpriest**

: Large Knight boss with four extra attacks: Taken Fire from Taken Knights, Retaliation Swarm from Taken Hobgoblins, Darkness Bolts from Taken Captains and Axion Darts from Taken Centurions. Immune to damage from anyone who does not have an Initiate buff. Attacks with a Darkness Bolt after each damage phase.

**Oculus**

: Flavor enemy in the shape of a large Taken ball that hangs out in the back of the arena. Immune to all damage and kills any player that comes into contact with it. Casts Searing Torrent when Brand of the Initiate is lost, dealing [rapid and near-lethal](https://clips.twitch.tv/SpineyInquisitiveWallabyRickroll-c1W-gfASThSwwC_2) damage to any player not hiding behind a monolith. Removes any monoliths that have a player near it after the attack animation ends. **Does not ignore block frames**. Unknown if it ignores overshields or damage resistance.

**Revenant Knight**

: Major Hive Knight that spawns when trash mobs are dead while the Warpriest's arena has Hive enemies present. Same as normal Knights, but has an Arc shockwave after their overhead slash. Spawns in sets of three, one on each sector of the map with a plate. Killing them starts the glyph reading sequence.

**Ravenous Taken Knight**

: Major Taken Knight that spawns when trash mobs are dead and the Warpriest's arena no longer spawns Hive. Spawns in sets of three, one on each plate. Killing them starts the glyph reading sequence.

**Blightguard**

: Blightguards are miniboss Taken Knights that appear when the Brand of the Initiate is obtained. They will spawn within fusion range of plates and spawn twice per damage phase, never in the same spot and never on the same plate that gave a player Brand. Killing them spawns a Brand Claimer on their position.

### Special Enemies
**Adepts**

: {{description_adept_enemy}} Only present after first damage phase and if the Warpriest is spawning Hive.

## Challenge: Devious Thievery

Brand Claimers must be used within 5 seconds of being obtained. Additionally, no one can die from the effect of Brand of the Initiate.

: A Dawnblade and dedicated first Brand Claimer point of view for Warpriest Contest Challenge Mode can be found [here](https://www.youtube.com/watch?v=uQgCsD6VMtM).

## Triumph Challenge: Brand Buster

No player can obtain the Brand again until each player has obtained it. It may be worded poorly, but we effortlessly two-phased him at 10 above cap so that knowledge is unverifiable on my account.

## Rewards
One of the following:
- {{ site.data.destiny.drops.kf.pulse_rifle }}
- {{ site.data.destiny.drops.kf.sniper_rifle }}
- Arms
- Chest

---

# Golgoroth's Maze {#maze}

Same layout as D1's labyrinth but has extra stuff in it now. Map [here](https://i.imgur.com/atlBKa4.png).

The path to the exit is:
- Go right
- Go left
- Go left
- Go right
- Go straight until exit

## Hidden Chest
The hidden chest in the area requires all five hidden plates to be held down simultaneously in the maze, in order.
- First is bottom right
- Second is top left
- Third is bottom left
- Fourth is middle left behind the door - there is a hole above it that can be jumped into
- Fifth is top right

Resolving the plates opens up access to the center of the maze where the second hidden chest can be found.

---

# Golgoroth's Cellar {#golgoroth}

Encounter is started by breaking the poison sac. Add spawns change depending on Golgoroth's health, with Taken adds replacing most Hive ones at lower health values. There is always a single miniboss Wizard spawn at the back of the room before damage phase.

## Objective
Kill Golgoroth.

### TL;DR
- Kill adds
- Get and juggle Gaze, point towards the pool
- Shoot and kill sac ASAP to optimize time spent doing damage
- Upload Cursed Thrall PoV to YouTube after detonating Unstable Light on ~~teammates~~ Golgoroth
- Break Golgoroth LoS when damage phase ends

## Mechanics
**Tablet of Ruin**

: The tablet is a black stone slab in the back of the room. It accumulates when Golgoroth's Gaze is lost and adds stacks depending on how many potential poison sacs weren't spawned per damage phase. It also accumulates by 2 if Golgoroth's Gaze is not obtained within roughly 10 seconds after a poison sac appears. If six runes are present, Exodia is summoned and instantly knocks your raid's life points to zero.

### Statuses
**Golgoroth's Gaze**

: Caretaker will inflict a debuff of the same name on someone who shoots him in the back with the text prompt, "Golgoroth shifts his Gaze to ``<PLAYERNAME>``". While Gaze is active, Golgoroth will fire swarms of Golgoroth's Rage at the debuffed player instead of using the normal Ogre attack kit. Lasts 20 seconds, only one gaze can be active at a time. Breaking line of sight or gaining any form of invisibility instantly removes the debuff. Gaining Gaze while it is active will purge it on any other players. If gained while any other Gazes are active, a wave of adds will spawn near the door in the back of the pit (unsure if on a timer or if this is the spawn condition). Losing Gaze at any time will despawn all poison sacs.

**Pool of Reclaimed Light**

: Continously granted to those standing in a pool of Reclaimed Light that is dropped from a poison sac. The pool lasts roughly 15 seconds. Allows players inside to ignore Golgoroth's damage resistance on his stomach.

**Unstable Light**

: Lasts 7 seconds. Seems to be periodically afflicted on any player who has Pool of Reclaimed Light. One player does their best Grandmaster Cursed Thrall impression, dealing lethal damage to any nearby allies and dealing massive damage to Golgoroth if nearby *and if vulnerable*, presumably ignoring damage resistance. Creates a humming noise that can be heard by all players and gets louder the closer it is to resolving.

**Drained of Light**

: Progressively reduces the player's visibility, similar to all the other screen wipe debuffs. Kills the victim after 7 seconds. Inflicted to all allies when Golgoroth enrages or when the Tablet of Ruin is complete.

**Ogre's Venom**

: Lasts around 1 second. Deals a tiny amount of damage. Obtained when being close enough to a Golgoroth's Rage projectile when it detonates.

### Interactables
**Poison Sac**

: Appears when Golgoroth's Gaze has been obtained / passed, aside from the cosmetic one that starts the encounter. Has 6 spawn spots on the ceiling, in a zig-zag pattern, starting left-most nearest the entrance and ends right-most furthest from the entrance. The When Golgoroth's Gaze is broken, no more poison sacs in sequence will spawn. When the first poison sac is broken 4 times, Golgoroth enrages.

: Rapidly heals over time. Has roughly 13-15k HP at LL1570.

### Mechanically Relevant Enemies
**Golgoroth**

: Immune to taking health damage from any source not under the effect of Pool of Reclaimed Light. Damage to his exposed back counts towards damage dealt but appears to deal no damage to Golgoroth's health bar, regardless of player state. His back becomes exposed after killing all the enemies in the room and will become rearmored if no one has Gaze after obtaining it once ("lost Gaze" / "failed to capture" prompt), not breaking his back within 15 seconds of it appearing (latter prompt as the last one) or Gaze being removed 6 times ("Golgoroth becomes tired").

: Breaking his back will grant Golgoroth's Gaze, changing Golg's kit from the standard Ogre kit to an Axion Dart spammer and lock both his aggro and facing to the player with Gaze. Golgoroth's Axion Darts have a special name (Golgoroth's Rage) and inflict Ogre's Venom as a PBAoE deathrattle in addition to normal Axion Dart effects.

: When a player has Gaze, Golgoroth's stomach will glow white and can be damaged, but with ~95% damage resistance. Standing in a pool of Reclaimed Light will allow outgoing damage to ignore Golgoroth's damage resistance. Enrages after breaking the first poison sac 4 times.

### Special Enemies
**Adepts**

: {{description_adept_enemy}}

## Challenge: Gaze Amaze

Any time Golgoroth's Gaze is removed, the player who had it must under the effect of Pool of Reclaimed Light.

: A Behemoth point of view for Golgoroth Contest Challenge Mode can be found [here](https://www.youtube.com/watch?v=0MUnKoyJVEI).

## Triumph Challenge: Taking Turns

No player can obtain Golgoroth's Gaze again until each player has obtained it. Uncertain if each player must obtain it at least once or if players must do a full party cycle forever.

## Rewards
One of the following:
- {{ site.data.destiny.drops.kf.scout_rifle }}
- {{ site.data.destiny.drops.kf.hand_cannon }}
- {{ site.data.destiny.drops.kf.fusion_rifle }}
- {{ site.data.destiny.drops.kf.machine_gun }}
- Helmet
- Legs

---

# Transept {#dickwall}

Traverse the walls to the next encounter. Don't get knocked off. Standing on a plate will activate platforms to the next plate. When players reach the other side, those platforms become permanently activated.

## Hidden Chest
There is a set of secret platforms that are activated by pulling out a Ghost, starting at the first plate and ending at a jump before the final hidden chest.

---

# Daughters of Oryx {#daughters}

Presumably, there is an enrage here, but I have never seen it because the sisters probably lost an extra 0 for their health bars. Welcome to the new accessible spoils farm.

## Objective
Kill the Deathsingers.

### TL;DR
- Become Emrakul, the Aeons Torn
- Use Flying to get over enemy blockers and get the Brand Claimer
- Declare attack on non-red Plainswalker
- Force enemy player to sacrifice target permanent
- Get banned in Commander
- This is staying in the release version

## Mechanics

### Statuses

**Brand Claimer**

: {{status_brand_claimer}}

**Dirge of Unraveling / Hymn of Weaving**

: Lasts 120 seconds. When it times out, inflicts instant death shortly afterwards. Inflicted on all players when a phase starts.

**Brand of Weaving / Unraveling**

: Grants the Aura effect of the same type to all nearby allies who are standing in the sphere of influence. Also grants the effects of said Aura. Removed upon death, phase transition or killing the Deathsinger who granted it.

**Aura of Weaving / Unraveling**

: Immune to all sources of damage that aren't instant death and presumably debuffs of the same named type (needs testing).

**Torn Between Dimensions**

: {% capture description_status_torn %} Inflicted on a random player when a player stands on a correct plate if no other players are Torn Between Dimensions. Allows them to stand on translucent platforms. Draws aggro on all bosses. Suppresses all abilities besides Movement Abilities. Inflicts both a disarm and forced third person camera. If a player dies while inflicted with Torn, it is immediately reapplied to another player. Has a lower targeting priority on players standing on plates. Turns the afflicted player's screen monochrome and changes their color scheme and texture to look more like the Taken. {% endcapture %} {{description_status_torn}}

### Interactables

**Piece of the Blightguard**

: {% capture description_entity_piece_of_the_blightguard %}Looks like Toland. Spawns on a translucent platform above the arena. Replaced with a Brand Claimer when two have been collected.{% endcapture %} {{ description_entity_piece_of_the_blightguard }}

**Brand Claimer**

: {% capture description_entity_brand_claimer_daughters %}Spawns on a translucent platform above the arena when two pieces of the Blightguard have been obtained. Grants a status effect of the same name.{% endcapture %}{{ description_entity_brand_claimer_daughters }}

**Plates**

: There are four plates in the room. The first green plate will have a Revenant Knight spawn on it. Any plates being activated will inflict a random ally with Torn Between Dimensions if there isn't a Torn player already. Anyone on an activated plate can see the location of the Blightguard fragment / Brand Claimer while they are on it. The second eligible plate is the plate under the floating objective. If both plates are activated in order, platforms will appear that the Torn player can jump on while the plates remain activated. Two(?) platforms will also spawn around the arena depending on plates activated, holding a Taken ranged unit on each of them. If any plate is activated out of order, all plates will light on fire and deal continuous damage to players on plates until no players are standing on plates.

: The sides of each plate do not count as standing on them.

### Mechanically Relevant Enemies

**Ir Halak, Deathsinger**

: Hive Wizard boss. **Can stomp**. Starts each phase with Brand of Weaving. While singing, doesn't fire projectiles and inflicts Dirge of Unraveling on the raid. Only one Deathsinger can be singing at a time (do they always alternate? is the first one static?). **If there are no singing Deathsingers, the phase resets in roughly 10 seconds.** As of the Sept-22-2022 hotfix, no longer treated as an treated as an [elite for purposes of damage calculation](https://www.reddit.com/r/DestinyTheGame/comments/x0r0on/wardcliff_coil_doesnt_do_extra_damage_to_vehicles/).

**Ir Anûk, Deathsinger**

: Same as above, but replace Weaving with Unraveling and vice-versa.

## Challenge: Under Construction

No player can activate a plate more than once per phase.

: A Sentinel point of view for Daughters Contest Challenge Mode can be found [here](https://www.youtube.com/watch?v=K5gxkLiunNo).

## Triumph Challenge: The Floor is Lava

No player with Torn Between Dimensions can touch the ground. Plates, platforms extending out near the boss pillars, the boss pillars and the sides of the map seem to not qualify for what is considered as the ground.

## Rewards
One of the following:
- {{ site.data.destiny.drops.kf.pulse_rifle }}
- {{ site.data.destiny.drops.kf.sniper_rifle }}
- {{ site.data.destiny.drops.kf.machine_gun }}?
- {{ site.data.destiny.drops.kf.hand_cannon }}
- Arms
- Chest

---

# Oryx, The Taken King {#oryx}

Run to not-so-Toland to start the encounter. Basically identical to the last encounter but with some extra steps.

## Objective
Kill Oryx, The Taken King.

### TL;DR
- Kill all the Light-Eaters ASAP
- Do plate dance, do Claimer dance thrice and obtain mechanic eligibility
- Claim the Vessel of Oryx's Brand, obtain life privilege
- Put the Dox in Doxology by detonating neutrino bombs during darkness channel
- Stack on brand holder to survive the ban wave
- Show Oryx how to solo Crota with some [hardcore cheeto hands](https://media.discordapp.net/attachments/981996380698603581/1013505892962029658/sweatcicle.gif) (to be clear, this is not netlimited, this is straight up injection)
- Get flinched by the thrall and whiff the crit, speak a word of it to no one
- Survive the wacky Warioware minigame

## Mechanics

### Interactables

**Piece of the Blightguard**

: {{ description_entity_piece_of_the_blightguard }}

**Brand Claimer**

: {{ description_entity_brand_claimer_daughters }}

**Plates**

: Exact same as the previous encounter, but no Ravenous Knight delineation this time.

: TL;DR: Plate inflicts Torn, plate holders can see the objective. Enemies spawn when plates are held. Plates held in the wrong order hurt plate holders. Plates create platforms, etc.

**Corrupted Light**

: Looks similar to a Taken Blight. When activated, prints a text log and then roughly three seconds afterwards, deals roughly 300 damage to all Guardians not under the effect of an Immortality buff. If detonated while Oryx is channeling Doxology, he becomes vulnerable for five seconds per bomb resolved during the channel. Can be eaten by any Hive Knight, empowering them and removing it from the field. Despawns upon entering final stand.

**Dome / Alternate Doxology**

: The thunderdome / Darkness sphere / "this has no name given to the player" is active while the Shade of Oryx is alive. This always appears in front of Oryx at the end of a phase, should he choose to use it. Players are periodically teleported inside while the dome is active. If the dome is still active after roughly 30 seconds of activation, Oryx casts Doxology and kills all players. If any Taken Thrall touch it, they teleport inside the dome. Touching the outside of the dome is lethal. All players inside are teleported out when the Shade dies.

### Statuses

**Brand Claimer**

: {{status_brand_claimer}}

**Torn Between Dimensions**

: {{description_status_torn}}

**Brand of Immortality**

: Continously grants the Aura of Immortality buff to all nearby allies and grants the effect of Aura of Immortality to self. Lost upon dying or phase transition. Obtained from using the Brand Claimer on the Vessel of Oryx.

**Aura of Immortality**

: Immune to all sources of damage that aren't instant death.

**Channeling Corrupted Light**

: What it says on the tin. Starts detonating all Corrupted Lights that the player is standing in after roughly 2 seconds of activation. Activation for each bomb is printed in the kill feed.

**Darkness Dimension**

: Debuff from being inside the dome. Prevents natural health regeneration. Removed upon leaving the dome.

### Mechanically Relevant Enemies
**Oryx, The Taken King**

: Immune to damage outside of his final stand unless he is stunned. Weak spot is his glowing chest.

: Has the following attacks:
- Spite of the King, a projectile salvo attack. Used when any player has Torn Between Dimensions.
- Fist of Darkness, a slam. Deals approximately 250 damage and massive knockback to any player it hits and always targets a plate. Only used outside of final stand and always used twice per phase: one at the start of the phase and one roughly 110 seconds later, before Doxology. This interval is shortened to roughly 5 seconds after the Brand of Immortality buff has been stolen.
- Doxology, a raid wipe that always has a text tell. Can be countered by detonating a Corrupted Light. Always used once per phase and is always followed by the second Fist of Darkness per phase, excluding during his final stand where he will start channeling it after the right-side Ogre spawns.

: At the end of a phase, he will always do one of two exclusive attacks:
- Summon Darkness Sphere, does what it says on the tin. Summons a Shade of Oryx and a major Taken Knight on each plate after he dies.
- Wrath of the King, targeted AoEs on all players. A major Taken Knight is spawned on each plate. WotK is continuously cast until all 4 Knights are dead or until 9 bombs spawn on each player. 

: Oryx's final stand will spawn 2 successive Light-Eater Ogres nearest him while starting his Doxology channel. This final stand is triggered after four damage phases or when his final stand health gate is hit, whichever comes first. When his final stand starts, damage phase is interrupted.

**Light-Eater Ogre**

: Drops a Corrupted Light puddle at location of death. One spawns in each quadrant near each plate, sequentially after the first Fist of Darkness with an interval of about 3 seconds, starting clockwise after the plate that Oryx slams at. Presumably immune to finishers, as the Corrupted Light would resolve and wipe the raid.

**Light-Eater Knight**

: Consumes Corrupted Light after approaching it. Spawns after a Light-Eater Ogre outside of final stand is slain. Assuming the map is divided by the walls near the two plate sets, a LE Knight and Taken Centurion always spawn from the opposite plate on the same side when an Ogre dies outside of Oryx's final stand. Immune to finishers.

**Vessel of Oryx**

: Consumes Corrupted Light after approaching it. Spawns with the Brand of Immortality buff. Spawns from the Tombship roughly 90 seconds after the first Fist of Darkness, though an alternate condition for the ship spawning may be having two pieces of the Brand Claimer obtained.

**Shade of Oryx**

: Keeps the dome active while he is alive. Has no health bar and is immune to finishers.

## Challenge: Hands Off

No player can kill a Light-Eater Ogre or Light-Eater Knight **from the same spawn location** twice. To be explicit, the two Ogres spawns furthest from spawn will activate a maximum of five times and everything else pops a maximum of four times. 

: A Sentinel point of view for Oryx Contest Challenge Mode can be found [here](https://www.youtube.com/watch?v=oB_qY3R0itI).

## Triumph Challenge: Power Overwhelming

If Oryx is damaged, his first health bar must be emptied in the same damage phase.

## Rewards
One of the following:
- {{ site.data.destiny.drops.kf.fusion_rifle }}
- Helmet
- Gloves

Additionally, if the raid exotic table was hit:
- {{ site.data.destiny.drops.kf.exotic }}, unknown drop chance (presumably ~5% at base)

The rune secret chest grants the following:
- Random King's Fall weapon with Deepsight Resonance

---

# Master Difficulty {#master}

Master difficulty applies the following changes to the raid:
- Master difficulty scalar applied to each enemy
- The power level of each encounter is boosted to {{site.data.destiny.power.max | plus: 20}}
- Match Game is enabled
- Chaff is enabled
- Taken Acolytes gain Void shields
- In the Hall of Souls, the two Taken Vandals near the portal are upgraded to ![Overload Champion]({{"assets/images/destiny/champion_icons/Overload_Champion_icon.png" | relative_url}}){:height="12px" width="12px"} Line Rifle-wielding Hobgoblins and one ![Unstoppable Champion]({{"assets/images/destiny/champion_icons/Unstoppable_Champion_icon.png" | relative_url}}){:height="12px" width="12px"} Ogre is added to each side per spawn wave
- In Basilica, an additional ![Unstoppable Champion]({{"assets/images/destiny/champion_icons/Unstoppable_Champion_icon.png" | relative_url}}){:height="12px" width="12px"} Ogre is added to each side per normal Unstoppable spawn
- In Warpriest, the Revenant Knights are replaced with ![Barrier Champion]({{"assets/images/destiny/champion_icons/Barrier_Champion_icon.png" | relative_url}}){:height="12px" width="12px"} Knights and Taken Hobgoblins are supposedly upgraded their ![Overload Champion]({{"assets/images/destiny/champion_icons/Overload_Champion_icon.png" | relative_url}}){:height="12px" width="12px"} variants ([source until I go to check Warpriest and later manually](https://www.reddit.com/r/raidsecrets/comments/xjgpmu/comment/ip89b0n/?utm_source=share&utm_medium=web2x&context=3))
- In Golgoroth, the two Knights that spawn when damage phase is ready have been upgraded to ![Barrier Champion]({{"assets/images/destiny/champion_icons/Barrier_Champion_icon.png" | relative_url}}){:height="12px" width="12px"} variants
- In Deathsingers, the Revenant Knights have been upgraded to their ![Barrier Champion]({{"assets/images/destiny/champion_icons/Barrier_Champion_icon.png" | relative_url}}){:height="12px" width="12px"} Knight variant
- In Oryx, the Ravenous Taken Knights have been "upgraded" to ![Overload Champion]({{"assets/images/destiny/champion_icons/Overload_Champion_icon.png" | relative_url}}){:height="12px" width="12px"} Stasis-wielding Hobgoblins

## Reward Adjustments

All encounter chest rewards are overwritten with high-stat armor, specializing on a specific stat per a weekly rotation. All challenge chest rewards are overwritten with any Harrowed weapon from the raid, prioritizing those that have not yet been obtained. The elective difficulty challenge chests share a different lockout than the normal mode challenge chests.

---

# End {#end}

See you again in six months, maybe.

## Spoils Chest
Weapons and armor that have been obtained from the raid can be purchased here. The first weapon purchase per week is guaranteed to have Deepsight Resonance, on an account-wide lockout. Subsequent purchases during the lockout have no chance to be Deepsighted, excluding Harrowed weapons.
