---
title: "Vow of the Disciple"
category: destiny
tags: raids
---
{% if site.data.destiny.power.min > 1550 %}
{% assign power = site.data.destiny.power.min %}
{% else %}
{% assign power = 1550 %}
{% endif %}

Vow of the Disciple is the end result of blending encounters from Last Wish, Leviathan, Vault of Glass, Crown of Sorrow and Risk of Rain 2's final boss.

# Prereading

- This isn't a guide, this is a mechanic explanation. There's many ways to handle these mechanics - do whatever's best for your raid team.
- Must have access to the Throne World region to access the raid.
- Light for final encounter is {{power}}.
- 2 hidden chests (gives shader triumph), 1 bonus chest on boss from raid secret.
- Brief overview on mechanics: obtain or protect mechanic eligibility by either killing named enemies, getting and using buffs with glyph callouts or calling out floating glyphs.
- Solar grenade Raid mod is actually good this time, wacky.

## Ammo Generation
This section is for you, Lucent Finisher and Aeon users.
- No Hive Lightbearers are in the raid. Only Scorn and Taken enemies appear (no Taken bosses, sorry Taken Spec fans).
- Champions are in E1 and E3.
- Ultras are in every encounter, but they are far away from allies (E1, E2, E3 kind of) or functionally unkillable (E2) in every encounter but E4.

Realistically, you won't need to use either outside of Master or Contest mode.

---

# Disciple's Bog (Outside) {#bog}

The bog is a payload minor encounter - it's identical to the one you do in Preservation, except has more enemies and has a secret chest. If you specifically have bad FPS loss here, it will get better after this section ends. Opening section is started by killing all enemies in front of the gate. No darkness zone here either, the only punishment for dying is wasting time.

## Objective
Move the Resonant Splinter forward five times.

## Hidden Chest
This encounter has a secret chest at the fifth section and is accessible by hitting all 3 pyramid spikes. The crypt containing the chest is located in the building to the direct right of the where the cart stops. There is one pyramid shard per section, excluding the first and last sections.
[imgur gallery](https://imgur.com/a/BTzBH3V)

## Mechanics

### Interactables
**Resonant Splinter**
: Acts as a cart, just like its public event variant. The cart has a small safe zone enveloping it it that prevents Pervasive Darkness accumulation (explained in the statuses section).

: Not directly interactable - it is advanced by bringing all 9 knowledge buffs to the cart. Bringing a buff to the cart purges it.

**"Darkness Shard" / "Crux" / "the rock" / "the (pyramid) fragment" / "the crystal"** (official name unknown)
: Toggleable shootable. Controls whether some associated object is on or off, usually doors being opened or closed.

### Mechanically Relevant Enemies
**Knowledge Keepers**
: 3 ultra Abominations of the same name will spawn at the start of each section, denoted with the kill feed textline, "Drown in the deep...". While any KKs are alive, all players in the zone will gain stacks of Pervasive Darkness. Killing *all* of them causes the kill feed to display the text string, "Rise from the deep..." and will spawn 9 glowing tiny darkness crystals that can be picked up by moving over them, granting the Knowledge series of buffs.

### Statuses
**Knowledge**
: Stackable buff, 3x max. The first word of the buff changes based on the number of stacks you have: Heightened, Brimming and Overflowing. If a player dies with this buff, the buffs respawn where they were picked up.

: The buff is consumed by a sister mechanic to activate them (e.g. in this encounter, it is consumed by the cart).

**Pervading Darkness**
: Effectively the same as Creeping Darkness from Last Wish. You become progressively more blinded and at 10 stacks, you die. Decays if the debuff isn't inflicted again.

---

# Disciple's Bog (Pyramid) {#pyramid}
The pyramid itself is only relevant if one of the following is met: 
- You want the weekly bonus chest from E4
- You want to see the callout names from the glyphs for yourself or others
- You want the lore pages for the raid Ghost


Otherwise, speedrun through this section.

## Bonus Boss Chest
When you first enter the pyramid, a glyph totem/board spawns with 3 glyphs on it. Finding the rooms that correlate to the glyphs on the totem and **only** activating them grants an additional drop from final boss that has a raid weapon with **guaranteed** Deepsight Resonance. Once all 3 have been activated, a text string will appear with "The Disciple recognizes your offering...". 
- The lockout is weekly, once per account.
- You cannot backtrack without OoBing. OoBing in load zones has a chance to render the chest **unobtainable without restarting**, due to despawning load zones forward and killing players in zones ahead, causing a softlock.

### Locations
- Pyramid: After the large fall in the pyramid, turn around. Shard is on the left of the door.
- Give: Right before first encounter, left of the Acquisition encounter entrance. Shootable's on top of the door frame.
- Darkness: In the area where the Acquisition encounter is, the door on the furthest left can be opened by shooting the shard in front of the sphinx.
- Traveler: In the first area after the "Collection" area text appears, at the back of the room. Fragment is hidden on top.
- Worship: Collection encounter, floor 4. Shard is near the entrance of the room, on the left. Door is near the entrance of the room, on the right.
- Light: Floor after Collection that has the first fragment for the platforming segment. Door is on the wall, shard is hidden in the ceiling.
- Stop: Third fragment for the platforming segment. Directly beneath the hidden chest room.
- Guardian: After Exhibition, take the left staircase up one level then turn left and go to the edge. Shard is floating in the air. Door is hidden above the stairs, behind a pillar.
- Kill: On the third floor after Exhibition, there are rooms with Taken Centurions. Shard is floating on the back wall. Door is in on the third floor on the right.

## Glyph Room {#glyphs}
There are 27 interactables that each have a glyph. Walking near it will change the radar location to the name of the corresponding glyph - these need to be memorized for callouts. There is a 28th glyph which is just an empty circle with an ordinary black background, which denotes a lack of a glyph.

![Glyph Cleans](https://cdn.discordapp.com/attachments/937646044714504222/949752321989046402/XxZPh4U.png)

## "Remember" Puzzle
Inside the glyph room, there is a hole in the right-side wall that has a 4x3 set of glyphs, in the following display:

| First column | Second column | Third column | Fourth column |
|-------|--------|---------|---------|
| Guardian | Guardian | Guardian | Guardian |
| Enter | Enter | Commune | Kill |
| Random Glyph | Random Glyph  | Random Glyph | Random Glyph |

- Fourth row will never repeat in that row
: Other players don't work if Guardian shows up in it, but you can always TK someone with Eager Edge for fun.

Follow the instructions for a lore page - there's some failure condition with it as well, I don't know it. Might be a timer, might require other players to help. Failing the puzzle will require a reset with the Remember wall - any additional inputs on the glyphs in the room will cause a failure.

Decoded instructions:

| First column | Second column | Third column | Fourth column |
|-------|--------|---------|---------|
| Player | Player | Player | Player |
| Melee | Melee | Interact | Shoot |
| Glyph 1 | Glyph 2 | Glyph 3 | Glyph 4 |

---

# Acquisition ![Unstoppable Champions]({{"assets/images/Unstoppable_Champion_icon.png" | relative_url}}){:height="20px" width="20px"} {#acquisition} 

Acquisition is an introductory encounter to the raid, teaching the main bulk of the mechanics while racing the clock. The encounter starts when you open the doors using the control mechanism in the north part of the room.

![Acquisition Encounter Map](https://i.imgur.com/9PjcEUk.png)

## Objective
The objective of the encounter is to have the obelisk accept your offering three times, allowing further progression into the raid.

### TL;DR
- Don't let the obelisks blow up
- Kill all 3 Disciple's Compasses
- Kill all 6 Glyphkeepers
- Document which glyph the correct GK dropped
- Shoot the correct glyphs on the correct obelisk

## Mechanics
### Data
**Glyph Totem / Board**
: Split into three parts, one glyph on each. Default empty, gets filled up as objectives progress. In E1, the boards indicates objectives that need to be carried out. 
- Top: designates where a Disciple's Compass spawns
- Mid: designates which crypt the Glyphkeepers are at
- Bottom: designates which Glyphkeeper glyph needs to be relayed to the fireteam

One is in front of each obelisk, for a total of three of them in the raid. 

### Interactables
**Pyramid Fragment** (official name unknown)
: Toggles all doors (shown in the above picture as the Door Control mechanism). Half of the doors start open.

**Obelisks**
![Obelisk](https://cdn.discordapp.com/attachments/937646044714504222/949739827258085456/Destiny_2_Screenshot_2022.03.05_-_13.45.30.12.png)
: The obelisk is the primary wipe mechanic of the first couple of fights. It starts out black and fills up orange. It fills up over time and fills up faster when shot by enemies, acting as a raid clock. When it fills up, the raid wipes. It gets emptied by progressing the Glyph board.
: There are 9 glyph locations on the obelisks that can be interacted by shooting them. When a Glyphkeeper dies, each obelisk gets 1 glyph, presumably shooting the one that matches the bottom glyph board symbol spawns 2 each.
- When all 9 glyph locations fill, a text prompt in the kill feed will appear with the text, "The obelisk awaits your offering..." and resets all obelisk timers. One **and only one** obelisk has all glyphs from all 3 correct GKs and will only be the correct obelisk **once** per encounter.
- Shooting the correct glyph will partially illuminate the obelisk. Keeping the obelisk fully lit (by shooting all 3 glyphs in rapid succession) will cause the obelisk to accept the offering, reset its fill and progress the encounter. Failure to comply within roughly 10 seconds will increment all obelisks by 1/3rd and post the text "The obelisk rejects your offering...".

### Mechanically Relevant Enemies
**Glyphkeepers**
: Glyphkeepers are a reoccurring named enemy - an ultra Chieftain in the raid that reveal glyphs on death.

: Inside each room that is shown by the glyph board, there are two Glyphkeepers, one on each side of the room. Each side of the room has a symbol that corresponds with a display - it will always be light or dark. Presumably, killing the GK that:
- Corresponds to the called side: Spawns an additional glyph on each obelisk.
- Does not correspond: Spawns an ![Unstoppable Champion]({{"assets/images/Unstoppable_Champion_icon.png" | relative_url}}){:height="12px" width="12px"} Abomination outside of its relevant obelisk - these spawn locations are static.

: Regardless of which is killed, they will reveal a glyph pillar located at their spawn location (empty, glyph, empty) and reveal 1 glyph on each obelisk. The pillar from the GK of the called side needs to be relayed to the team for the obelisk offering section. **You must kill both**, and presumably killing both empties their respective obelisk.

**Disciple's Compass**
: The compass is a major Taken Knight that will appear in one of 10 spots (refer to the map).

: On death, reveals the second glyph on its relevant glyph board and the first glyph on an empty glyph board, if applicable. Out of its spawn locations, the top portion of the glyph board designates which side of the map it has spawned on. It also empties its respective obelisk on death.

**Abored Adherent**
: Abored Adherents are major Scorn Lurkers that accompany spawn sets. In E1, it accompanies every normal spawn in a set of 2. They are able to target the obelisk in addition to players. AAs deal large damage to obelisks, roughly 1/18th of its health per hit.

## Challenge: Swift Destruction
The challenge is failed if any ![Unstoppable Champion]({{"assets/images/Unstoppable_Champion_icon.png" | relative_url}}){:height="12px" width="12px"} Abominations remain alive, after roughly 3 seconds, after another one dies. Unknown if this check is per wave or map-wide. Note that, sometimes, the Abomination furthest north can spawn OoB.

## Rewards
One of the following:
- Submission
- Deliverance
- Cataclysmic
- Helmet
- Chestpiece
- Boots

---

# Collection {#collection}

Collection is a boss encounter with split roles. It has 4 floors (excluding the starting floor which is not relevant), each corresponding to a phase set. Killing the Caretaker will allow further progression into the raid. Encounter is started by shooting any door-controlling fragments in the room.

## Objective
Kill the Caretaker.

### TL;DR
- Stun the Caretaker to prevent him reaching the obelisk
- Grab glyph-overlayed buffs
- Shoot all the glyphs off the obelisk
- Shoot at boss

## Mechanics

*Mechanic Phase*
---

### Mechanically Relevant Enemies

**Caretaker**
: During this phase, the Caretaker is invulnerable.
: The Caretaker occasionally glows bright yellow - he can be damaged, in a limited capacity, on his glowing portions.
: If the boss reaches the obelisk before all the glyphs on the obelisk are resolved, the raid wipes - acting as a timer for each floor's mechanic phase.
: He periodically sends out lingering projectiles known as Resonant Suns.
: While unstunned, The Caretaker will also passively use abomination zaps on whoever has aggro. 
: After the obelisk offerings are completed, he will no longer stomp or use Caretaker's Gaze until the next mechanic phase.
: Enemies only spawn on the floor that the Caretaker is currently on, if possible.
: The Caretaker's pathing can be altered or broken by using Sparrows or Stasis Crystals. To be explicit, if CT's pathing is altered outside of damage phase, he will attempt to path to the obelisk by going the other way - this does not alter which plate damage phase starts on. If CT's pathing is altered during damage phase **or** if his path is completely blocked, he will teleport to the fork in the road in front of the obelisk.

*Resonant Suns*

: Also known as seekers. These spiral lingering projectiles can be shot down and also explode on contact with a player. If not shot down, after the obelisk glows orange (e.g. after an offering has been completed and some additional unknown condition, or if damage phase starts), they will home in on a seemingly random player. Taking damage from one of these projectiles will inflict PD and does medium damage.

### Statuses
**Stunned**

: Periodically (?) or when Caretaker gazes, his face will glow yellow for 5 seconds or until taking enough damage, roughly 2000 at 1530 power. If his face is broken, his backpack will then glow for 5 seconds. When the backpack takes enough damage, he releases ~6 Suns and will be stunned for 5 seconds. If any part naturally stops glowing, the stun progress is lost and must be restarted.

**Caretaker's Gaze**

: Caretaker will inflict a debuff of the same name on someone who forces him to stomp - during this duration, he will not stomp again and will be both aggroed and will continuously look at any player with the debuff. Lasts 6 seconds, only one gaze will be active at a time.

**Knowledge**

: Same as normal, but also resets the buff and reinitializes the fragment (with its associated glyph) if an obelisk offering is rejected. When all knowledge has been resolved with the obelisk, damage phase starts with the kill feed text, "The ritual is complete, power awaits you..." and cleanses all stacks of PD.

### Locations
**Glyph / Dark Room**
: The glyph/dark room can be opened by any **Darkness Fragment** and has multiple named ultra Wizards and several Shadow Thrall inside - these can all be mostly ignored. While inside the room, any player inside will be inflicted with stacking **PD**. Inside the dark room, there are 9 glowing knowledge crystals with a glyph on them, scattered around the room, used for the obelisk mechanic.
: Each floor's room is larger than the last and will have more death pits.

### Interactables
**Obelisk**
: An obelisk is present on the second, third and fourth floor. When any player has knowledge stacks and is outside of a glyph room, they become eligible to perform an offering. While any player is eligible to perform an offering, a text log will appear saying, "An obelisk awaits ``<PLAYERNAME>``'s offering...", with the player's name being one who is eligible to offer. All glyphs on the obelisk that correspond with the knowledge puddles that said player ran over must be quickly shot, or the obelisk will partially fill up and purge that player's knowledge buff (thus respawning the fragments in the glyph room). Only one offering can occur at a time.

*Damage Phase*
---
Damage can be dealt to the Caretaker when Resonant Breakthrough is active.

### Health Gating
Caretaker can only lose roughly 33% of their first health bar per damage phase, cumulatively. To be clear: he can only go down to roughly 66% of his first HP bar on floor 1, roughly 33% on floor 2 and 0% on floor 3. Upon triggering the gate, damage phase ends. The glowing portion on the boss health bar denotes how much health is left per gate.

### Statuses
**Resonant Breakthrough**

: The Caretaker is only able to take damage from players who have the Resonant Breakthrough buff, which is continuously granted to players touching glowing plates - lingers for about a second. 

### Interactables
**Plates / Wells**
: Three plates are near the obelisk on each floor, excluding the final floor where all three plates are lined up sequentially. These plates grant Resonant Breakthrough to players touching plates when active. When all 3 have deactivated after being active, the Caretaker will vanish, opening access to the next floor. If the Caretaker is on the fourth and final floor, he wipes the raid instead.
: The first plate to activate will be the closest one to the side that Caretaker approached from and only starts the activation routine when the obelisk glows. Presumably, if Caretaker is deemed to be unable to immediately move closer to the obelisk, the obelisk will glow. Plates permanently deactivate roughly 5 seconds of the Caretaker being near the obelisk, with a two second warning with the log, "The current well begins to fade...", and then immediately activate the next eligible one closest to it.
: Occasionally, he will become permanently stunlocked - damage phase won't end until the damage gate kicks in.

### Final Stand
At the last floor, all gates are ignored and mechanic phase is skipped - he can now be killed. If he doesn't die before all plates expire, he enrages and wipes the raid.

## Challenge: Base Information
No player can obtain Brimming Knowledge - each player is only allowed to hold, at most, one Knowledge stack at a time.

## Rewards
One of the following:
- Submission
- Insidious
- Forebearance
- Cataclysmic
- Helmet
- Gauntlets
- Class Item

---
# Platforming Section
To keep this part brief, keep going up. Path platforms are toggled with the darkness fragment. Progressing through a portion and engaging with enemies on the other side will activate all platforms of the previous segment. In the third platforming segment, there is a hidden chest if you keep going right instead of going through the window.

This is where your flawlesses will die; Warlocks in particular want practice with this part. All fireteam members must be at the exit to open the door to the next encounter. There is a known OoB near the wall at the first set of enemy spawns. However, as of writing there are no appropriate video links to describe how to navigate around the outside.

---

# Exhibition ![Overload Champions]({{"assets/images/Overload_Champion_icon.png" | relative_url}}){:height="20px" width="20px"} {#exhibition}
Exhibition is a mob-heavy encounter where you juggle artifacts (known as relics) to deal with weapon-immune enemies and cleansing debuffs while racing the clock. Encounter starts by taking the Resonant Shard from its terminal / pedestal.

![Exhibition Encounter Map](https://cdn.discordapp.com/attachments/948006022306463804/951287013506707466/IMG_7825.webp)

## Objective
Deposit all three relics on the fifth and final series of terminals.

### TL;DR
- Grab artifacts/relics/whatever, use ability when needed
- Kill Glyphkeepers to reveal glyphs
- Find matching glyphs between pairs
- Shoot 1 or 2 matching glyphs on door to open it
- Place all relics on terminals to open next room

## Mechanics

### Interactables: Relics
**Resonant Shard**
: Used to break white shields.
: Fire input fires a low damage continuous beam.

: When placed on a terminal, the duration of Terminal Resonance is refreshed.

**Aegis**
: Works the same as in Vault of Glass, but has a much larger grenade energy pool and defaults to being filled.

: Fire input is a light attack, ADS input is a heavy attack. Sword block input cleanses all stacks of PD for all players inside the sphere and drains the grenade charge while held. Super shoots a projectile that does high damage.

**Taken Essence**
: Works similarly to the one in Last Wish, but no access to the Super and doesn't die when the grenade input is used.

: Fire input fires a medium damage projectile, grenade input kills all nearby Taken spheres.

### Mechanically Relevant Enemies
**Glyphkeepers**
: A new Glyphkeeper type is introduced in this encounter, the Resonant Glyphkeeper - an Ultra Taken Phalanx.
: Glyphkeepers spawn when all the Taken Hobgoblins on their side have been slain, presumably including the ![Overload Champion]({{"assets/images/Overload_Champion_icon.png" | relative_url}}){:height="12px" width="12px"}s. A text line will appear: "Glyphkeepers approach..."
: Glyphkeepers spawn in sets of 2, 1 Scorn and 1 Taken. Every room that doesn't have a terminal in it will have 2 sets, 1 otherwise.
: Killing either of these Glyphkeepers will drop a glyph totem. The totem from the Taken GK can **only be read by a relic holder** and vice-versa. Killing both of them will spawn a Disciple's Hourglass at the chokepoint of the current non-terminal room. Additionally, if it is the first set of each non-terminal room, their deaths will spawn more Taken Hobgoblins.

: Each pair of glyph totems contains a matching glyph which is used to open the upcoming ingress.

**Disciple's Hourglass**

: Taken Knight with a white shield. Always spawns at a chokepoint at the center of the room after a GK set is slain. Explicit spawn location is based on which GK set dies - it is pre-determined. Killing the Disciple's Hourglass extends Terminal Resonance by around 30 seconds and can't push it past its initial value(?).

### Interactables

**Artifact Terminal**
: Terminals can be used to deposit relics.
: Placing all available relics on terminals in a room will open the door to the next room. Terminals, excluding the one used to start the encounter, are available after every ingress. All terminal sets, aside from the first two sets, will spawn a pack of Screebs *once and only once* when approached.
: Placing a Resonant Shard on a terminal will refresh the duration of Terminal Resonance. Placing a Resonant Shard on the second terminal set will spawn an Aegis on the unused terminal. Placing a Resonant Shard and Aegis on the third terminal set will spawn a Taken Essence on the unused terminal.

: Relics can be taken from the terminal after all active relics are placed. Relics that go OoB will respawn on the terminal that they were last placed on.

**Ingresses / Glyph Doors**
: Ingresses are doors that are required to be opened to progress through the encounter.
: In order to open them, the matching glyph from each glyph pillar pair needs to be quickly shot on the door after the text log saying "The ingress awaits your offering...". Shooting the correct symbols will result in a text log saying that the offering is accepted and vice-versa.

: There is no known direct consequence for failing the offering other than the obvious time loss of waiting for the prompt again.

**Taken Sphere** (unofficial name)
: Identical to the Taken sphere that the Ascendant Primeval (meatball) spawned during Gambit Primeval phases, however it is immune to all damage and can be killed through the grenade function on the Taken Essence. Enemies tethered to it gain immunity to all damage, but not debuffs (e.g. you can push them off an edge with Tractor Cannon or a well placed Vortex Grenade).

### Statuses
**Pervading Darkness**

: Stacks in every room without a terminal in it.

**Terminal Resonance**

: 75 second persistent debuff. When it times out, the raid gets wiped. Inflicted on the entire party when starting the encounter.

**Curbed Resonance**

: 30 second debuff. Unable to pick up any relics. Inflicted on any player when they drop a relic.

## Challenge: Defenses Down
To be written. Not currently available in-game until Tuesday, April 5th, 2022.

## Rewards
One of the following:
- Submission
- Deliverance
- Helmet
- Chestpiece
- Boots
- Class Item

---

# Dominion {#dominion}
Dominion is the final encounter of the raid, combining elements of the second and third encounter with elements from Crown of Sorrow. It flipflops between blind buff deposits and dodging boss AoEs.

![Dominion Encounter Screenshot](https://i.imgur.com/2wJwTfk.jpeg)

## Objective
Kill Rhulk, ~~Edgelord~~ Disciple of the Witness. Rhulk will hard enrage if not killed before his third damage phase ends.

### TL;DR
- Juggle Leeching Force
- Kill Glyphkeepers to reveal glyphs
- Dunk at matching totem with Emanating Force, 6 times
- Kill Glaive to reveal glyph and get buff
- Dunk at matching totem with Emanating Force, 4 times
- Kill crit spots
- Shoot at boss

## Mechanics

*All Deposit Phases*
---

### Mechanically Relevant Enemies
**Rhulk, Disciple of the Witness**
: During all deposit phases, Rhulk is invulnerable unless otherwise stated. He fires lasers that interact with the Leeching Force buff.

### Statuses
**Leeching Force**

: Lasts 45 seconds, granted from either the pyramid pylons in the bubble phase or Rhulk's Glaive in the arena phase. If this buff times out, the player who had it dies. If a player who has this buff is hit by Rhulk's laser attacks, they ignore both the damage and debuffs from it and have their force buff replaced with Emanating Force.

**Emanating Force**

: Lasts 45 seconds, granted from making contact with Suns of Lubrae (the laser) when Leeching Force is active. If this buff times out, the player who had it dies. Does NOT provide protection from laser attacks.

### Interactables
**Glyph Totem**

: Glyph Totems are interactable by any player with the Emanating Force buff. Their glyphs are invisible to any player who has any force buff. On correct deposit, their buff is removed and either the bubble shrinks in bubble phase or a crit spot is exposed on Rhulk in arena phase. On incorrect deposit, the player dies.

*Deposit Phase 1: Bubble Phase*
---

### Mechanically Relevant Enemies
**Rhulk, Disciple of the Witness**

: Rhulk attacks roughly every 20 seconds.

*Summon Pyramid Shard*

: If no players have a force buff, Rhulk will teleport to the back of the room (unless he is there already, such as at phase start) and summon a giant pyramid shard above him while presumably resetting the floating glyph pillars (which are invisible at this point). If the shard is not broken, it will stack PD on all players until broken. The player who gets the final blow on the shard will get Leeching Force. If this attack is used more than twice per phase, the shard will become invulnerable, causing a wipe. A set of Glyphkeepers and supporting enemies will always spawn shortly after this attack resolves.

*Suns of Lubrae*

: Otherwise, Rhulk will always use the same attack: a teleport followed by a massive telegraphed forward-facing lingering beam that does high damage and hits six times, each hit dealing moderate damage and inflicting 1 stack of PD. He will then teleport to the front of the room for several seconds. If any target hit has Leeching Force, the target will ignore the damage and debuffs from the laser; and the buff will be replaced with Emanating Force. **This attack will be interrupted during its startup if the bubble shrinks during it.**

**Glyphkeepers**
: Both a Taken GK and a Scorn GK will spawn together on opposite sides of the map after the single large shard that Rhulk spawns is broken - Taken on left, Scorn on right. When they die, floating glyph pillars will appear on the left and right side of the map - players with a force buff can read the pillar on the left side and vice-versa.

### Interactables
**The Bubble**

: Being inside the bubble will both rapidly play a sound effect and inflict rapidly compounding knockback away from its origin. The bubble will get smaller as more Emanating Force buffs are successfully deposited. After six Emanating Force buffs are deposited, all pending Force buffs will be purged shortly afterwards.

**Glyph Totem**

: There are six totems for phase 1, 3 on the left and 3 on the right. **2** of them will have a matching glyph with the two floating glyph pillars from the GKs. Successfully dunking will shrink the bubble. 6 successful deposits disables bubble knockback until damage phase ends.

: The glyph totem's glyphs will cycle every time the bubble pulses orange, which is about 7 seconds after the last deposit.

**Glyph Plate**

: Any player with Leeching Force that stands on the plate will spawn a pair of large floating pyramid shard. Players without any force buff or that have not killed the other prism in the pair can damage them. Whoever inflicted final blows on the pair of shards gain Leeching Force and whoever was standing on the plate gets it purged.

*Deposit Phase 2: Arena Phase*
---

![mspaint Drawing of the Arena](https://cdn.discordapp.com/attachments/937646044714504222/949917607161630720/unknown.png)

### Timer
After the bubble is enterable, players have an unknown amount of time (I assume 20 seconds) to enter the UFC cage. After the UFC cage is active, players have about 2 minutes to enter damage phase or he will presumably skip damage phase and start executing his phase end attack, kicking players back to the bubble phase. Breaking all 4 of Rhulk's crit spots will progress to damage phase.

### Mechanically Relevant Enemies
**Rhulk, Disciple of the Witness**

: Rhulk's attacks change in this phase.

*Kick*
: Rhulk will walk towards the player closest to him. If he is sufficiently close enough to a player, he will do his best impression of the Gekkos from Metal Gear Rising and kick the player for high damage. Any melee hit from Rhulk will **kill deployable support Supers if they have low Resilience**, presumably breaking barricades as well.

: ![PoV: You are playing during contest mode](https://cdn.discordapp.com/attachments/730083412882358304/950974328755871744/skill_issue.gif)

*Savage Strike*
: Summons 4 sets of 2 Shadow Thrall, one set per quadrant - their spawns are static. Rhulk then summons his glaive, puts it behind his back and dashes forward to the first player that would be in front of him, followed by a high damage frontal cone. He will then drop his glaive, allowing it to be shot as it morphs into a pyramid shard.
: If there are no players where the dash would resolve, he ends his dash where it would have finished otherwise.

: Rhulk is **incorporeal while dashing**, meaning he both takes and deals no damage during the dash. Only the cleave has a hurtbox.

*Suns of Lubrae*
: This attack is usually used as a followup to the dash, but can also be used on its own. Identical to the laser attack in the first phase but is faster, 4x smaller and fires 4way cardinally from where he's facing. Unknown if it can be dodged by being directly inside the boss.

*Orange Channel*

: If his crit spots aren't broken within roughly 2 minutes, Rhulk kneels down and becomes immune to damage while glowing orange. After ~15 seconds, the bubble regains its knockback capability and he transitions back to phase 1.

### Interactables
**Rhulk's Glaive**

: Rhulk drops a copy of his glaive after each dash in this phase - it can be shot and killed. Whomever deals the killing blow on the glaive will be granted Leeching Force. Additionally, a glyph pillar will appear at wherever it died - this pillar can only be seen by those without a force buff. Multiple glaives can be active at once.

**Glyph Totems**

: There are 4 totems for arena phase, 1 on each corner. Their glyphs are static - they never rotate and are always the same as displayed on the arena infographic above. However, they are still invisible to any player who has a force buff, similar to bubble phase. Successfully depositing at a totem will reveal a crit spot on Rhulk, up to 4.

**Crit Spots**

: As totems successfully resolve, Rhulk will stagger and a crit spot on Rhulk will be revealed in the following order: his right shoulder, then his left shoulder, then his left thigh and ending with his right thigh. Breaking all 4 crit spots will purge all active force buffs and enter damage phase **immediately** after the fourth crit spot breaks.

*Damage Phase*
---
Upon entering damage phase, all force buffs are purged. Any pending glaives are still briefly damageable, allowing a player to smuggle Leeching into the damage phase for a free no-punish laser eat.

### Mechanically Relevant Enemies
**Rhulk, Disciple of the Witness**

: Rhulk's behaviour changes again during this phase. After roughly 30 seconds, he will start his orange channel.

*Slash*

: Rhulk will powerwalk towards the player closest to him. If he's close enough to a player, he will slash them with his glaive, dealing high damage.

*Savage Strike*

: Rhulk's tell on the charge changes - he twirls the glaive above him and then immediately dashes forward to the first player that would be in front of him, followed by a high damage frontal cone. This attack is always immediately followed by Suns of Lubrae. He will dash roughly 3 times per damage phase, as a rule of thumb.

### Final Stand
Upon losing his first health bar, he becomes temporarily immune and his glaive transforms and expands, instantly afflicting all players with 2 stacks of PD. During this phase, he constantly afflicts all players with a stack of PD every second until either he dies or all players die. During this phase, he will not cast his bubble channel.

## Challenge: Looping Catalyst
To be written. Not currently available in-game until Tuesday, April 12th, 2022.

## Rewards

One of the following:
- Lubrae's Ruin
- Insidious
- Forebarance
- Helmet
- Gauntlets
- Class Item

: Collective Obligation, unknown drop chance.

: If the glyph secret was completed, an additional chest will spawn granting a random raid weapon with Deepsight on a weekly lockout per account.

---

# End {#end}

## Spoils Chest
One weapon with Deepsight Resonance can be purchased per week, per account.
