# Jarulf’s Guide X

# Table of Contents

## [1. Introduction](#1-introduction)
- [1.1 Abbreviations](#11-abbreviations)

## [2. Characters](#2-characters)
- [2.1 Character stats](#21-character-stats)
  - [2.1.1 Starting stats](#211-starting-stats)
  - [2.1.2 Maximum stats](#212-maximum-stats)
  - [2.1.3 Life and mana](#213-life-and-mana)
  - [2.1.4 Armor Class and To Hit](#214-armor-class-and-to-hit)
- [2.2 Fighting](#22-fighting)
  - [2.2.1 Getting hit](#221-getting-hit)
  - [2.2.2 Damage done](#222-damage-done)
  - [2.2.3 Weapon speed](#223-weapon-speed)
- [2.3 Timing information](#23-timing-information)
- [2.4 Skills](#24-skills)
- [2.5 Starting equipment](#25-starting-equipment)
- [2.6 Experience points](#26-experience-points)
- [2.7 Character level restrictions](#27-character-level-restrictions)
  - [2.7.1 Single player difficulty levels](#271-single-player-difficulty-levels)
- [2.8 Character names](#28-character-names)

## [3. Items](#3-items)
- [3.1 Armor, weapons and jewelry](#31-armor-weapons-and-jewelry)
- [3.2 Other base items](#32-other-base-items)
  - [3.2.1 Runes and oils](#321-runes-and-oils)
  - [3.2.2 Potions and elixirs](#322-potions-and-elixirs)
  - [3.2.3 Books, scrolls and staves with spells](#323-books-scrolls-and-staves-with-spells)
- [3.3 Quest items](#33-quest-items)
- [3.4 Prefixes and suffixes](#34-prefixes-and-suffixes)
- [3.5 Unique items](#35-unique-items)
  - [3.5.1 Properties of unique items](#351-properties-of-unique-items)
  - [3.5.2 Unfindable unique items in multiplayer](#352-unfindable-unique-items-in-multiplayer)
- [3.6 Prices of magical items](#36-prices-of-magical-items)
  - [3.6.1 Formulas](#361-formulas)
  - [3.6.2 Additional notes on the prices](#362-additional-notes-on-the-prices)
  - [3.6.3 Recharge cost](#363-recharge-cost)
- [3.7 Durability of items](#37-durability-of-items)
  - [3.7.1 Losing durability](#371-losing-durability)
  - [3.7.2 Repair cost](#372-repair-cost)
- [3.8 Item creation in dungeon](#38-item-creation-in-dungeon)
  - [3.8.1 What is dropped?](#381-what-is-dropped)
  - [3.8.2 Item type](#382-item-type)
  - [3.8.3 Item properties](#383-item-properties)
- [3.9 Item creation in town](#39-item-creation-in-town)
  - [3.9.1 Adria](#391-adria)
  - [3.9.2 Griswold](#392-griswold)
  - [3.9.3 Pepin](#393-pepin)
  - [3.9.4 Wirt](#394-wirt)
- [3.10 General remarks on possible items](#310-general-remarks-on-possible-items)
- [3.13 Summary of various item properties](#313-summary-of-various-item-properties)
  - [3.13.1 Levels of base items](#3131-levels-of-base-items)
  - [3.13.2 Levels of spells on books and staves](#3132-levels-of-spells-on-books-and-staves)
  - [3.13.3 Levels of prefixes and suffixes](#3133-levels-of-prefixes-and-suffixes)
  - [3.13.4 Levels of unique items](#3134-levels-of-unique-items)
  - [3.13.5 Effects of prefixes and suffixes](#3135-effects-of-prefixes-and-suffixes)
  - [3.13.6 Occurrence of prefixes and suffixes](#3136-occurrence-of-prefixes-and-suffixes)

## [4. Magic](#4-magic)
- [4.1 Spells available to players](#41-spells-available-to-players)
  - [4.1.1 List of spells and spell effects](#411-list-of-spells-and-spell-effects)
  - [4.1.2 Details about spells](#412-details-about-spells)
  - [4.1.3 Spells available in Diablo](#413-spells-available-in-diablo)
  - [4.1.4 New spells in Hellfire](#414-new-spells-in-hellfire)
  - [4.1.5 Mana cost and magic requirements for spells](#415-mana-cost-and-magic-requirements-for-spells)
  - [4.1.6 Spell level of cast spells](#416-spell-level-of-cast-spells)
  - [4.1.7 Targeting of spells](#417-targeting-of-spells)
- [4.2 Spell casting monsters](#42-spell-casting-monsters)
  - [4.2.1 Details about monster spells in Diablo](#421-details-about-monster-spells-in-diablo)
  - [4.2.2 Details about new monster spells in Hellfire](#422-details-about-new-monster-spells-in-hellfire)
- [4.3 Traps](#43-traps)

## [5. Monsters](#5-monsters)
- [5.1 How to calculate monster data](#51-how-to-calculate-monster-data)
- [5.2 Monster data](#52-monster-data)
- [5.3 Monster properties](#53-monster-properties)
- [5.4 Unique monsters](#54-unique-monsters)
- [5.5 Monster AI](#55-monster-ai)
- [5.6 Summary of various monster stats](#56-summary-of-various-monster-stats)

## [6. Battle](#6-battle)
- [6.1 General information](#61-general-information)
- [6.2 Melee attacks](#62-melee-attacks)
- [6.3 Non melee attacks](#63-non-melee-attacks)

## [7. Shrines](#7-shrines)

## [8. Quests](#8-quests)
- [8.1 How quests are chosen](#81-how-quests-are-chosen)
- [8.2 Quests in Diablo](#82-quests-in-diablo)
- [8.3 Quests in Hellfire](#83-quests-in-hellfire)

## [10. Other Useful Information](#10-other-useful-information)
- [10.1 Hot keyed messages while playing](#101-hot-keyed-messages-while-playing)
- [10.2 Save files](#102-save-files)
- [10.3 Transferring save files](#103-transferring-save-files)
- [10.4 Backing up your character](#104-backing-up-your-character)
- [10.5 Daylight-saving time problems in Diablo 1.00](#105-daylight-saving-time-problems-in-diablo-100)
- [10.6 Avoiding the Game End movie](#106-avoiding-the-game-end-movie)
- [10.7 Meaningless information about this guide](#107-meaningless-information-about-this-guide)
- [10.8 The End](#108-the-end)

# 4. Magic

This chapter will explain the details of all spells in the game. It will, of course, include information about those ”spells” monsters use, as well as information about traps, which are often of a magical nature. It will not, however, cover magical effects from shrines. Generally, such magical effects from shrines are dependent on the dlvl they are found on. For an explanation of skills, see chapter 2.4. For a detailed information about how spells attack and also some explanation in general about spells, see chapter 5.6.5.


## 4.1 Spells available to players

All spells in Diablo and Hellfire are equally learnable for all character classes. To learn them to a high slvl one needs a high magic attribute, and not all character classes have the ability to reach the needed 255 magic attribute that is needed for the highest spell levels.


### 4.1.1 List of spells and spell effects

Below is a summary of all spells you will find in Diablo and Hellfire. They are arranged in the same way they appear in your spell book. Page 5, Jester, Magi and Mana only exist in Hellfire.

|**Page One**|**Page Two**|**Page Three**|**Page Four**|<b>Page Five<sup>5</sup></b>|**Not in Book**|
| :- | :- | :- | :- | :- | :- |
|*Skill*|Resurrect1,2|Phasing|Nova2|Lightning Wall|Identify3|
|Firebolt|Fire Wall|Mana Shield|Golem|Immolation|Infravision3|
|Charged Bolt|Telekinesis|Elemental|Teleport|Warp|Jester4,5|
|Holy Bolt|Lightning|Fireball|Apocalypse2|Reflect|Magi4,5|
|Healing|Town Portal|Flame Wave|Bone Spirit|Berserk|Mana4,5|
|Heal Other1|Flash|Chain Lightning|Blood Star|Ring of Fire||
|Inferno|Stone Curse|Guardian|-|Search||
1. Only appear in multi player games.
1. Only appear on scrolls or staves. In Hellfire you can learn Nova and Apocalypse normally though.

1. Only appear on scrolls.

1. Only appear on staves.

1. Found in Hellfire only.


### 4.1.2 Details about spells

Now follows some details about each spell. Not all types of data are applicable for each spell. Below is an explanation of what is told about most spells. If no information type is given for a specific spell, it is either due to it not applying (for example the speed of a stationary effect), or due to it not being known to me. For more details about how spells attack, see chapter 5.6.5 and more specifically chapter 6.1.8.

In previous versions there existed information for spells if they had any distance factor included in their To Hit calculation. From what I have found, no spell has a distance factor; or rather, it is always 0. Only arrows (including fire and lightning arrows and arrows from traps and monsters) have a distance factor. As a consequence, I have removed any reference to a distance in the detailed list of spells.

Type:	Magic, fire or lightning. Some spells are not of one of the three main types and

are listed as n/a.

Damage:	Stated damage in spell book (see below for more details), can be split up into

min. and max. damage where appropriate.

Quick Damage:	A quicker way to calculate damage but not as accurate. Can be split up into min.

and max. damage where appropriate.

Real Damage:	The real damage as used by the game. This is not necessarily the same as the

stated damage, especially for non missile spells, as they instead can often attack several times. If no real damage is stated, it is identical to the damage stated. Also, if the real damage distribution is linear within the range given, it is not shown either. All this is done to reduce the amount of data presented, as it is already extensive.

Duration:	This is how long each spell lasts. The time given is always in seconds unless

otherwise stated. Moving spells will generally be terminated if they hit any dungeon feature, such as a wall.

Speed:	This is the speed at which the spell effect travels. It is a relative number used for

comparison between different spells and normal arrows, and is not to be confused with walk speed for players and monsters. The higher the value, the faster it is. For information about the speed of arrows, see chapter 2.2.3.

Blockable:	This will tell if a spell is blockable or not. In Diablo, you will only block if you

have 0% resistance. In Hellfire, you will block anything blockable regardless of your resistance.


**Damage**

Some spells use a recursive formula to calculate damage. The notation for these spells was introduced by Sourceror and I have used it here too. Here follows an explanation on how it works. To make it easier to write damage formulas for spells using multiple random numbers, I have also added a notation for that.

|[ ]|round down||
| :- | :- | :- |
|Rnd[x]|is a random number in the range 0 to x-1||
|Rec(slvl, slvl0)|recursive function, defined as follows:||
||Rec(0, slvl0):|[slvl0]|
||and for slvl>0; Rec(slvl, slvl0):|[Rec(slvl-1, slvl0) × 9/8]|
|Itt(nbr, value)|iterative function, defined as follows:||
||Itt(0, value):|value|
||and for nbr>0; Itt(nbr, value):|Itt(nbr-1, value) + value|

The easiest way to understand how the recursive function works is to make an example. A Fireball’s maximum damage for a level 30 character is:

1. Rec(slvl, 40 + 2×clvl); clvl=30

|2\.|First calculate damage for spell level 0:|40 + 2×clvl = 100|
| -: | :- | :- |
|3\.|Damage for spell level 1 can then be calculated as:|[100 × 9/8] = 112|
|4\.|Damage for spell level 2 can then be calculated as:|[112 × 9/8] = 126|

5. and so on…

Note that it is very important to round down. For those spells using this recursive formula I have also given a quick formula. For a Fireball’s maximum damage it is:

(40 + 2×clvl) × (9/8)^slvl

Note that this formula does not round down and you will therefore get a damage a bit too high, but it will still be more or less accurate. For a level 20 fireball from a level 50 character the correct maximum damage is 1442, while this quick method gives 1476. In the table below, I have listed values for use with the quick formula.

**Summary for quick damage**

|(9/8)^1|1\.125|(9/8)^6|2\.027|(9/8)^11|3\.653|(9/8)^16|6\.583|
| -: | -: | :- | -: | -: | -: | -: | -: |
|(9/8)^2|1\.266|(9/8)^7|2\.281|(9/8)^12|4\.110|(9/8)^17|7\.406|
|(9/8)^3|1\.424|(9/8)^8|2\.566|(9/8)^13|4\.624|(9/8)^18|8\.332|
|(9/8)^4|1\.602|(9/8)^9|2\.887|(9/8)^14|5\.202|(9/8)^19|9\.373|
|(9/8)^5|1\.802|(9/8)^10|3\.247|(9/8)^15|5\.852|(9/8)^20|10\.545|

Lets make an example for the iterative function as well. Take the damage of the flash spell (case 1). It uses a recursive formulas where the slvl0 (see above) is actually first calculated using an iterative formula. Lets calculate slvl0 for a level 30 character:

slvl0 = Itt(clvl, Rnd[20] + 1); clvl=30

This means we should, 30 times, calculate Rnd[20] + 1 and add all those 30 values together. For each value, a new random number should be created, for if the same random number would be used, it would have been written as clvl×(Rnd[20] + 1) instead. This sum of 30 values, ranging from 1 to 20 in the example, is the slvl0 which is then used in the recursive formula. It is worth noticing that if there is any random number used in the iterative formula, the result would typically be a distribution of the values as in a bell curve.


**Splash damage**

Some spells do additional splash damage. Splash damage is always considered a separate attack and thus does its own to hit check and can hit or miss independently from the initial attack. Of course, there need to be some hit before the splash damage is applied. Such a hit can be either a normal target or such a thing as a wall. As an example a fireball will cause splash damage to all adjacent locations when it hits a wall.


### 4.1.3 Spells available in Diablo

The spells below are listed in alphabetical order and are available in both Diablo and Hellfire. For skills, see chapter 2.4. In those cases a spell can be used by a monster, see chapter 0.

|**Apocalypse**|**Blood Star**|
| :- | :- |
|Type: n/a|Type: magic|
|Min. Damage: clvl|Damage: 3×slvl + [Mag/2] - [Mag/8]|
|Max. Damage: 6×clvl|Speed: 16|
|Real damage: Itt(clvl, Rnd[6] + 1)|Blockable: Yes|
|Blockable: Yes||
|Note:|Note:|
|\*  Works against all monsters, even triple immune ones.|\*  Costs 5 life to cast or 5 extra mana if you use Mana|
|\*  In Hellfire, this spell only works on monsters you|Shield. This cost is applied even if the spell is cast|
|have a line of sight to.|from a staff.|
|||
|**Bone Spirit**|**Chain Lightning**|
|Type: magic|Type: lightning|
|Damage against monster: 1/3 of targets HP|Min. Damage: 4|
|Damage against player: 1/6 of targets life|Max. Damage: 4 + 2×clvl|
|Speed: 16|Real Damage: Rnd[clvl] + Rnd[2] + 2|
|Blockable: Yes|Bolts: 1 + numbers of monsters in range|
|\*  Note that the damage value given above is still subject|Range: 2 + slvl (max 18)|
|to reduction due to resistance.|Speed: 32|
||Duration: ([slvl/2] + 6)/20 seconds|
||Blockable: No|
|Note:|Note:|
|\*  Costs 6 life to cast or 6 extra mana if you use Mana|\*  You get one bolt in the direction where you aim with|
|Shield. This cost is applied even if the spell is cast|your mouse and one additional bolt for each monster|
|from a staff.|in range.|
||\*  This spell is well known for causing gaps at high levels|
||and/or when there are many monsters within range.|
||\*  The lightning is actually a stationary effect, but the|
||initiation will be delayed the further away it appears,|
||thus giving an appearance of moving. This delay|
||”travels” with a speed of 32.|
||\*  The bolt will try to hit once each 0.05 seconds for a|
||total of [slvl/2] + 6 times.|

|<a name="page72"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|**Created by Pedro Faria**||
| :- | :- | :- |
||||
|**Charged Bolt**|**Elemental**||
|Type: lightning|Type: fire||
|Min. Damage: 1|Min. Damage: Rec(slvl, 4 + 2×clvl)||
|Max. Damage: 1 + [Mag/4]|Max. Damage: Rec(slvl, 40 + 2×clvl)||
|Number of bolts: 4 + [slvl/2]|Quick Min. Damage: (4 + 2×clvl) × (9/8)^slvl||
|Speed: 8|Quick Max. Damage: (40 + 2×clvl) × (9/8)^slvl||
|Blockable: Yes|Real Damage: Rec(slvl, 2×(Rnd[10]+Rnd[10]+clvl) +||
||4)/2||
||Speed: 16||
||Blockable: Yes||
||Note:||
||\*  This is basically a fireball that has some homing||
||abilities.||
||\*  It does half the damage of a fireball, but can hit two||
||targets.||
||\*  Splash damage is 1/64th of the damage and is applied||
||for 0.7 seconds and will try to hit every 0.05 second||
||(for a total of 14 times) and is not blockable.||
||||
|**Fireball**|**Firebolt**||
|Type: fire|Type: fire||
|Min. Damage: Rec(slvl, 4 + 2×clvl)|Min. Damage: 1 + slvl + [Mag/8]||
|Max. Damage: Rec(slvl, 40 + 2×clvl)|Max. Damage: 10 + slvl + [Mag/8]||
|Quick Min. Damage: (4 + 2×clvl) × (9/8)^slvl|Real Damage: Rnd[10] + slvl + [Mag/8] + 1||
|Quick Max. Damage: (40 + 2×clvl) × (9/8)^slvl|Speed: 16 + 2×slvl||
|Real Damage: Rec(slvl, 2×(Rnd[10]+Rnd[10]+clvl) + 4)|Blockable: Yes||
|Speed: 16 + 2×slvl (max 50)|||
|Blockable: Yes|||
|Note:|||
|\*  A fireball cause splash damage in adjacent hexes as|||
|well as in the target hex. Splash damage is equal to the|||
|damage of the fireball itself.|||
|\*  If the fireball has traveled over some obstacle on its|||
|way to its target, the splash damage normally does not|||
|occur.|||
|\*  You can block either the fireball or the splash, but not|||
|both.|||
||||
|**Fire Wall**|**Flame Wave**||
|Type: fire|Type: fire||
|Min. Damage: 4 + 2×clvl|Min. Damage: 6 + 6×clvl||
|Max. Damage: 40 + 2×clvl|Max. Damage: 60 + 6×clvl||
|Real Damage: (Rnd[10] + Rnd[10] + clvl + 2)/8|Real Damage: Rnd[10] + clvl + 1||
|Duration: 8 + 8×slvl seconds (12 + 8×slvl in Hellfire)|Speed: 16||
|Number of flames: 11|Number of flames: 5 + [slvl/2]||
|Blockable: No|Blockable: Yes||
|Note:|\*  Flame Waves are treated as traps against players,||
|\*  The central fire wall flame actually consists of two|including the caster.||
|flames on top of each other, with the result of a|||
|damage for that ”flame” being double.|||
|\*  The Fire Wall will disappear immediately if you gain|||
|any level in the spell.|||
|\*  Fire Walls are treated as traps against players,|||
|including the caster.|||
|\*  The flame will try to hit once every 0.05 seconds for a|||
|total of 160 + 160×slvl times (240 + 160×slvl times in|||
|Hellfire).|||

|<a name="page73"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|**Created by Pedro Faria**|||
| :- | :- | :- | :- |
|||||
|**Flash**|**Golem**|||
|Type: magic (but uses same animation as lightning)|Type: n/a (but uses same animation as fire)|||
|Min. Damage: [3×Rec(slvl, clvl)/2]|Stated damage: 11-17 (quite meaningless number)|||
|Max. Damage: 2×[3×Rec(slvl, clvl)/2]|The golem has the following stats:|||
|Quick Min. Damage: 3×clvl/2 × (9/8)^slvl|HP: 2×maxmana/3 + 10×slvl|||
|Quick Max. Damage: 3×clvl × (9/8)^slvl|AC: 25|||
|Real Damage 1: [3×Rec(slvl, Itt(clvl, Rnd[20] + 1))/2]/64|To Hit: 40 + 2×clvl + 5×slvl|||
|Real Damage 2: [3×Rec(slvl, Itt(clvl, Rnd[2] + 1))/2]/64|Min. Damage: 8 + 2×slvl|||
|Duration: 0.95 seconds|Max. Damage: 16 + 2×slvl|||
|Blockable: No|mlvl: 12 (modified for difficulty)|||
||HP regeneration: 1.9, 4.1 and 6.6 each second on|||
||normal, nightmare and hell difficulty (same as for|||
||normal monster)|||
||Resistances: None|||
||Immunities: Apocalypse, Stone Curse and Telekinesis|||
|Note:|Note:|||
|\*  The Flash spell is actually composed of two different|\*  Each player can have only one golem alive at a time.|||
|effects, the two different Real Damages given are for|If you cast the spell again, the first golem will be|||
|the two different effects. The first hit in front of you|destroyed.|||
|and to the sides, the other behind you.|\*  If more than one player casts golem, they will seek|||
|\*  You seem to be able to do two flashes in a row, then|each other out and fight until one of them is|||
|you have to wait for them to finish. Don’t know how|destroyed.|||
|this affects damage though.|\*  You will get normal experience for any monster that|||
|\*  While casting Flash, you are temporarily invulnerable|your golem kills.|||
|and can’t access the normal GUI.|\*  If no monster is close enough to the golem, he will|||
|\*  The flash will try to hit once every 0.05 seconds for a|walk in the same direction the owning player is facing.|||
|total of 19 times.||||
|||||
|**Guardian**|**Healing**|||
|Type: fire|Type: n/a|||
|Min. Damage: Rec(slvl, 1 + [clvl/2])|Mana Cost: 8 + 2×clvl - 3×slvl|||
|Max. Damage: Rec(slvl, 10 + [clvl/2])|Min. Healing: bonus×(1 + clvl + slvl)|||
|Quick Min. Damage: (1 + clvl/2) × (9/8)^slvl|Max. Healing: bonus×(10 + 4×clvl + 6×slvl)|||
|Quick Max. Damage: (10 + clvl/2) × (9/8)^slvl|Real Healing: bonus×(Rnd[10] + Itt(clvl, Rnd[4]+1) +|||
|Duration: 4×slvl/5 + 2×clvl/5 seconds (maximum 24|Itt(slvl, Rnd[6]+1) + 1)|||
|seconds, minimum 0.8 seconds)|Bonus:|||
|Fire frequency: every 0.8 second|Warrior, Monk and Barbarian:|2\.0||
|Blockable: Yes|Rogue and Bard:|1\.5||
||Sorcerer:|1\.0||
|Note:|Note:|||
|\*  The fire bolts shot by a Guardian are determined by|\*  The actual distribution of the healing is bell curve|||
|the slvl of your Firebolt spell, so the shown damage is|shaped.|||
|actually bogus.||||
|\*  You will get normal experience for any monster that||||
|your guardians kill.||||

|<a name="page74"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|**Created by Pedro Faria**|||
| :- | :- | :- | :- |
|||||
|**Heal Other**||**Holy Bolt**||
|Type: n/a||Type: n/a||
|Mana Cost: 8 + 2×clvl - 3×slvl||Min. Damage: 9 + clvl||
|Min. Healing: bonus×(1 + clvl + slvl)|Max. Damage: 18 + clvl|||
|Max. Healing: bonus×(10 + 4×clvl + 6×slvl)|Speed: 16 + 2×slvl|||
|Real Healing: bonus×(Rnd[10] + Itt(clvl, Rnd[4]+1) +||||
|Itt(slvl, Rnd[6]+1) + 1)||||
|Bonus:||||
|Monk:|3\.0|||
|Warrior and Barbarian:|2\.0|||
|Rogue and Bard:|1\.5|||
|Sorcerer:|1\.0|||
|Note:||Note:||
|\*  The actual distribution of the healing is bell curve|\*  This spell only works on undead monsters and|||
|shaped.||Diablo. See chapter 5.2 for information about which||
|||monsters are undead. It does not work against||
|||players.||
|||\*  In Hellfire, Diablo and Bone Demons are resistant to||
|||Holy Bolt.||
|||||
|**Identify**||**Inferno**||
|Type: n/a||Type: fire||
|||Min. Damage: 3||
|||Max. Damage: 6 + 3×clvl/2||
|||Real Damage: (3×(Rnd[clvl]+Rnd[2]) + 6)/16||
|||Range: 3||
|||Duration: 1, 1.25 and 1.50 seconds||
|||Blockable: No||
|Note:||Note:||
|\*  Identifies magical and unique items.|\*  This spell always affect the same area and has the|||
|||same duration, regardless of spell level.||
|||\*  The three values for duration are for the three target||
|||locations starting with the one closest to the caster.||
|||\*  The flame will try to hit once each 0.05 second for a||
|||total of 20, 25 and 30 times.||
|||||
|**Infravision**||**Lightning**||
|Type: n/a||Type: lightning||
|Duration: Rec(slvl, 79.2) seconds||Min. Damage: 4||
|Murky pools:||Max. Damage: 4 + 2×clvl||
|Church:|slvl = 2|Real Damage: Rnd[clvl]+ Rnd[2] + 2||
|Catacombs:|slvl = 4|Speed: 32||
|Caves:|slvl = 6|Duration: ([slvl/2]+6)/20 seconds||
|Hell:|slvl = 8|Blockable: No||
|Note:||\*  The lightning is actually a stationary effect, but the||
|\*  Lets you see a ”heat” image of monsters and players|initiation will be delayed the further away it appears,|||
|outside of your normal view and through walls.|thus giving an appearance of moving. This delay|||
|\*  As far as I know, you will never find Murky Pools in|”travels” with a speed of 32.|||
|the Hive or in the Crypt.||\*  The bolt will try to hit once every 0.05 seconds for a||
|||total of [slvl/2]+6 times.||

|<a name="page75"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|**Created by Pedro Faria**||
| :- | :- | :- |
||||
|**Mana Shield**|**Nova**||
|Type: n/a|Type: lightning||
|Damage reduction in Diablo: 33%|Min. Damage: 5×Rec(slvl, 2 + [clvl/2])||
|Damage reduction in Hellfire: see below|Max. Damage: 5×Rec(slvl, 15 + [clvl/2])||
|Duration: until mana reaches 0 or you leave the current|Quick Min. Damage: 5×(2 + clvl/2) × (9/8)^slvl||
|dlvl|Quick Max. Damage: 5×(15 + clvl/2) × (9/8)^slvl||
||Real Damage: Rec(slvl, (Itt(5, Rnd[6]) + clvl + 5)/2)||
||Number of bolts: 92||
||Speed: 16||
||Blockable: No||
|Note for Hellfire only:|||
|\*  A Mana shield decreases the damage taken, but due to|||
|a bug the reduction actually decreases as slvl goes up.|||
|The damage is reduced by the following amount:|||
|100/(3× slvl)%|||
|\*  If slvl is higher than 7, set slvl to 7.|||
|Note for both Diablo and Hellfire:|||
|\*  For slvl 0 there is never any reduction of the damage.|||
|\*  Due to a bug you will neither be stunned nor pushed|||
|back by *the bear* or Diablo if you receive damage|||
|(before modification by the Mana Shield) greater than|||
|your current life.|||
||||
|**Phasing**|**Resurrect**||
|Type: n/a|Type: n/a||
|Note:|Note:||
|\*  Due to being a non targeting spell, it is slightly faster|\*  Brings another player back to life. The player will||
|than Teleport and it may thus be easier to escape with|have 10 life (or his max life if it is less than 10) and 0||
|this spell than with Teleport.|mana.||
||||
|**Stone Curse**|**Telekinesis**||
|Type: n/a|Type: n/a||
|Duration: 4.8 + 0.8×slvl seconds (max 12 seconds)|||
|Note:|Note:||
|\*  Stone Curse works on all monsters except Diablo and|\*  Can be used to open doors, chests, bookcases, shrines||
|Na-Krul.|etc. from a distance.||
|\*  Stone Curse does not work on other players.|\*  Can also be used to pick up items from a distance.||
|\*  Any monster already stoned, charging, phasing in or|\*  Can be used to ”knock” monsters back. This ”attack”,||
|phasing out is temporary immune to Stone Curse.|although it does not inflict any damage, is sufficient||
||for receiving full experience points when the monster||
||later dies. The following Unique or Special monsters||
||are immune to Telekinesis: Snotspill, Gharbad the||
||Weak, Zhar the Mad, Warlord of Blood, Lachdanan,||
||Arch-Bishop Lazarus, Blackjade and Red Vex.||
||\*  A monster will immediately lose any Stone Curse||
||status if it is targeted with Telekinesis.||
||||
|**Teleport**|**Town Portal**||
|Type: n/a|Type: n/a||
|Note:|Note:||
|\*  You can teleport to anywhere within the screen. I|\*  Makes a portal to town and disappears when the||
|have noticed that if you quickly move your cursor|caster uses it to go down to the dungeon.||
|before teleporting you often end up teleporting to|||
|where your cursor was just before you moved it.|||
|**4.1.4 New spells in Hellfire**|||

The spells in the table below are new spells in Hellfire. Apocalypse and Nova, although new as learnable spells in Hellfire, exist in Diablo and no changes have been done to them. See chapter 4.1.3 for information about Apocalypse and Nova.

|<a name="page76"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|**Created by Pedro Faria**|||
| :- | :- | :- | :- |
|||||
|**Berserk**||**Immolation**||
|Type: magic||Type: fire||
|||Min. Damage: 5×Rec(slvl, 2 + clvl/2)||
|||Max. Damage: 5×Rec(slvl, 15 + clvl/2)||
|||Quick Min. Damage: 5×(2 + clvl/2) × (9/8)^slvl||
|||Quick Max. Damage: 5×(15 + clvl/2) × (9/8)^slvl||
|||Real Damage: Rec(slvl, (Itt(5, Rnd[6]) + clvl + 5)/2)||
|||Number of bolts: 92||
|||Speed: 16 + slvl||
|Note:||Note:||
|\*  All unique and special monsters are immune to|\*  Does the same damage as Nova.|||
|Berserk.||\*  Immolation will use bolts that are basically fireballs||
|\*  Any monster charging, phasing in or phasing out is|(including splash damage), they just has a different|||
|temporary immune to Berserk.|damage and speed compared to normal fireballs.|||
|\*  When cast on a monster, it will consider other||||
|monsters as possible targets too.||||
|\*  It will increase the damage done by the monster by||||
|between 20 and 30%, plus the level of the spell||||
|(possible problem with overflow if value gets higher||||
|than 255).||||
|\*  You will not receive any experience for monsters||||
|killed by a berserk monster.||||
|\*  Monsters resistant to Magic, will have a 50% chance||||
|of escaping the spell. Monsters immune to Magic are||||
|of course immune to this spell.||||
|||||
|**Jester**||**Lightning Wall**||
|Type: random||Type: lightning||
|The following spells are cast by a staff of jester:|Min. Damage: 4 + 2×clvl|||
|Firebolt|20%|Max. Damage: 40 + 2×clvl||
|Apocalypse|10%|Real Damage: (Rnd[10] + Rnd[10] + clvl + 2)/4||
|Chain lightning|10%|Duration: 12.75 + 12.75×slvl seconds||
|Fireball|10%|Number of bolts: 11||
|Fire Wall|10%|Blockable: No||
|Guardian|10%|||
|Teleport|10%|||
|Town Portal|10%|||
|Stone Curse|10%|||
|Note:||Note:||
|\*  This spell can only occur on staves and casts a|\*  The central lightning wall bolt actually consists of two|||
|random spell.||bolts on top of each other, with the result of a||
|||damage for that ”bolt” being double.||
|||\*  Does twice the damage of a Fire Wall and lasts||
|||longer.||
|||\*  The flame will try to hit once every 0.05 seconds for a||
|||total of 255 + 255×slvl times.||

|<a name="page77"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|**Created by Pedro Faria**|||
| :- | :- | :- | :- |
|||||
|**Magi**|**Mana**|||
|Type: n/a|Type: n/a|||
||Min. Mana: bonus×(1 + clvl + slvl)|||
||Max. Mana: bonus×(10 + 4×clvl + 6×slvl)|||
||Real Mana restore: bonus×(Itt(clvl, Rnd[4]+1) + Itt(slvl,|||
||Rnd[6] + 1) + Rnd[10] + 1)|||
||Bonus:|||
||Sorcerer:|2\.0||
||Rogue and Bard:|1\.5||
||Warrior, Monk and Barbarian:|1\.0||
|Note:|Note:|||
|\*  Completely restores mana.|\*  The actual distribution of healing is bell curve shaped.|||
||\*  This spell works like Healing but affects your mana|||
||instead of your life.|||
|||||
|**Reflect**|**Ring of Fire**|||
|Type: n/a|Type: fire|||
|Duration: slvl×clvl hits|Min. Damage: 4 + clvl×2|||
||Max. Damage: 40 + clvl×2|||
||Duration: 12 + 8×slvl seconds|||
||Real Damage: (Rnd[10] + Rnd[10] + clvl + 2)/8|||
||Duration: 8 + 8×slvl seconds (12 + 8×slvl in Hellfire)|||
||Number of flames: 22|||
||Blockable: No|||
|Note:|Note:|||
|\*  Reduces melee damage by 20-29% and reflects it back|\*  Does the same damage as a Fire Wall and lasts the|||
|to the attacking monster. Spell level determines|same amount of time.|||
|number of hits it lasts.|\*  The Ring of Fire will disappear immediately if you|||
|\*  Even if you block an attack, 20-29% of the damage is|gain any level in the spell.|||
|reflected back to the attacking monster.|\*  Fire Walls are treated as traps against players,|||
|\*  An attack counts as a hit even if you block it as it will|including the caster.|||
|reflect some damage.|\*  The flame will try to hit once every 0.05 seconds for a|||
|\*  The Reflect will be terminated if you die or leave the|total of 160 + 160×slvl times.|||
|current dlvl.||||
|||||
|**Search**|**Warp**|||
|Type: n/a|Type: n/a|||
|Duration: 12.25 + 10×slvl + clvl seconds||||
|Note:|Note:|||
|\*  Makes items on the ground shine.|\*  Teleports you to the nearest stair.|||
|\*  Makes items show up on the map.||||

### 4.1.5 Mana cost and magic requirements for spells

Casting spells costs mana and each spell has an initial mana cost at slvl 1. For each slvl the mana cost then decreases by a certain amount specific for each spell until it reaches its minimum mana cost. The table below shows the mana cost for each spell as well as the slvl you reach the minimum mana cost (unless stated otherwise, use the 100% value in the table unless stated otherwise for a character class). Note that Rogues, Monks and Bards only pay 75% of the mana cost (use the 75% value in the table). In Hellfire (after patch 1.01) the Sorcerer only pays 50% of the mana cost (use the 50% value in the table for Hellfire and the 100% value for Diablo). However, no character class ever pays less than the minimum mana cost. Casting spells from scrolls and staves do not cost any mana, but you have to have the required magic to do so.

For staves, the required magic to cast a spell from it is the same as it is to learn the same spell to the first slvl. For scrolls, the mana required to cast a spell is normally a bit less. The table below also shows those required magic levels. For information about prices and slvl of books, scrolls, and staves with spells, see chapter 3.2.3.

|<a name="page78"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**||||||**Created by Pedro Faria**||||||
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|||||||||||||
|**Name of Spell**|||**Mana cost**||||||**Magic requirement**|||
||<b>Initial<sup>1</sup></b>|**Decrease**|**Minimum**|**slvl you reaches**|<b>Staff<sup>2</sup> and</b>|**Scroll**||||||
|||**per slvl**||**minimum**|**slvl 1**|||||||
|||||**(100%/75%/50%)**||||||||
|Apocalypse3|150|6|90|11|/|6|/|1|149|117||
|Blood Star|25|2|14|7|/|5|/|1|70|-||
|Bone Spirit|24|1|12|13|/|9|/|1|34|-||
|Chain Lightning|30|1|18|13|/|7|/|1|54|35||
|Charged Bolt|6|0|6|1|/|1|/|1|25|-||
|Elemental|35|2|20|9|/|6|/|1|68|-||
|Fireball|16|1|10|7|/|4|/|1|48|31||
|Firebolt|6|0\.5|3|7|/|5|/|1|15|-||
|Fire Wall|28|2|16|7|/|5|/|1|27|17||
|Flame Wave|35|3|20|6|/|4|/|1|54|29||
|Flash|30|2|16|8|/|6|/|1|33|21||
|Golem|100|6|60|8|/|5|/|1|81|51||
|Guardian|50|2|30|11|/|6|/|1|61|47||
|Healing|||special4||||||17|0||
|Heal Other|||special4||||||17|-||
|Holy Bolt|7|1|3|5|/|4|/|2|20|-||
|Identify|-|-|-|- /|- /|-|-|0||||
|Inferno|11|1|6|6|/|4|/|1|20|19||
|Infravision|-|-|-|- /|- /|-|-|23||||
1. This is also the amount of mana you receive when you read a book of the spell.
1. There is no requirement to cast a spell from a unique staff.

1. You can only learn this spell in Hellfire.

1. Heal and Heal Other cost 8 + 2×clvl - 3×slvl mana to cast.

|**Name of Spell**|||**Mana cost**||||||**Magic requirement**||
| :- | :- | :- | -: | :- | :- | :- | :- | :- | -: | :- |
||<b>Initial<sup>1</sup></b>|**Decrease**|**Minimum**|**slvl you reaches**|<b>Staff<sup>2</sup> and</b>|**Scroll**|||||
|||**per slvl**||**minimum**|**slvl 1**||||||
|||||**(100%/75%/50%)**|||||||
|Lightning|10|1|6|5|/|3|/|1|20|0|
|Mana Shield|33|0|33|1|/|1|/|1|25|0|
|Nova3|60|3|35|10|/|6|/|1|87|57|
|Phasing|12|2|4|5|/|5|/|3|39|25|
|Resurrect|-|-|-|- /|-|/|-|30|0||
|Stone Curse|60|3|40|8|/|4|/|1|51|33|
|Telekinesis|15|2|8|5|/|4|/|1|33|-|
|Teleport|35|3|15|8|/|6|/|3|105|81|
|Town Portal|35|3|18|7|/|5|/|1|20|0|
|Berserk|35|3|15|8|/|6|/|3|35|-|
|Immolation|60|3|35|10|/|5|/|1|87|-|
|Jester|-|-|-|- /|-|/|-|30|-||
|Lightning Wall|28|2|16|7|/|5|/|1|27|-|
|Magi|-|-|-|- /|-|/|-|45|-||
|Mana|-|-|-|- /|-|/|-|17|-||
|Reflect|35|3|15|8|/|6|/|3|25|-|
|Ring of Fire|28|2|16|7|/|5|/|1|27|-|
|Search|15|1|1|15|/|15|/ 14|25|0||
|Warp|35|3|18|7|/|5|/|1|25|0|

1. This is also the amount of mana you receive when you read a book of the spell.
1. There is no requirement to cast a spell from a unique staff.

1. You can only learn this spell in Hellfire.

The table above has the magic requirement to learn a spell to level 1. For each additional spell level the magic requirement is 20% higher to learn. To make it easier for you, the table below lists the magic requirement for each spell and spell level. Note that if the magic requirement is 213 or higher, it is always adjusted to 255.

|<a name="page79"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|||||||**Created by Pedro Faria**||||||||||
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
||||||||||||||||||
|**Name of Spell**|**1**|**2**|**3**|**4**|**5**|**6**|**7**|**8**|**9**|**10**|**11**|**12**|**13**|**14**|**15**||
|Blood Star|70|84|100|120|144|172|206|255|255|255|255|255|255|255|255||
|Bone Spirit|34|40|48|57|68|81|97|116|139|166|199|255|255|255|255||
|Chain Lightning|54|64|76|91|109|130|156|187|255|255|255|255|255|255|255||
|Charged Bolt|25|30|36|43|51|61|73|87|104|124|148|177|212|255|255||
|Elemental|68|81|97|116|139|166|199|255|255|255|255|255|255|255|255||
|Fireball|48|57|68|81|97|116|139|166|199|255|255|255|255|255|255||
|Firebolt|15|18|21|25|30|36|43|51|61|73|87|104|124|148|177||
|Fire Wall|27|32|38|45|54|64|76|91|109|130|156|187|255|255|255||
|Flame Wave|54|64|76|91|109|130|156|187|255|255|255|255|255|255|255||
|Flash|33|39|46|55|66|79|94|112|134|160|192|255|255|255|255||
|Golem|81|97|116|139|166|199|255|255|255|255|255|255|255|255|255||
|Guardian|61|73|87|104|124|148|177|212|255|255|255|255|255|255|255||
|Healing|17|20|24|28|33|39|46|55|66|79|94|112|134|160|192||
|Heal Other|17|20|24|28|33|39|46|55|66|79|94|112|134|160|192||
|Holy Bolt|20|24|28|33|39|46|55|66|79|94|112|134|160|192|255||
|Inferno|20|24|28|33|39|46|55|66|79|94|112|134|160|192|255||
|Lightning|20|24|28|33|39|46|55|66|79|94|112|134|160|192|255||
|Mana Shield|25|30|36|43|51|61|73|87|104|124|148|177|212|255|255||
|Phasing|39|46|55|66|79|94|112|134|160|192|255|255|255|255|255||
|Stone Curse|51|61|73|87|104|124|148|177|212|255|255|255|255|255|255||
|Telekinesis|33|39|46|55|66|79|94|112|134|160|192|255|255|255|255||
|Teleport|105|126|151|181|255|255|255|255|255|255|255|255|255|255|255||
|Town Portal|20|24|28|33|39|46|55|66|79|94|112|134|160|192|255||
|Apocalypse|149|178|255|255|255|255|255|255|255|255|255|255|255|255|255||
|Berserk|35|42|50|60|72|86|103|123|147|176|211|255|255|255|255||
|Immolation|87|104|124|148|177|212|255|255|255|255|255|255|255|255|255||
|Lightning Wall|27|32|38|45|54|64|76|91|109|130|156|187|255|255|255||
|Nova|87|104|124|148|177|212|255|255|255|255|255|255|255|255|255||
|Reflect|30|36|43|51|61|73|87|104|124|148|177|212|255|255|255||
|Ring of Fire|27|32|38|45|54|64|76|91|109|130|156|187|255|255|255||
|Search|25|30|36|43|51|61|73|87|104|124|148|177|212|255|255||
|Warp|25|30|36|43|51|61|73|87|104|124|148|177|212|255|255||

### 4.1.6 Spell level of cast spells

When you cast a spell, it will always be cast at the slvl you know the spell plus any additional levels you get from items. As your slvl can go down (by hitting an Enchanted shrine, for example), it is possible to get a known spell to slvl 0. When this happens, you can no longer use the spell, unless some items you are wearing raise the slvl above 0. The slvl can never be negative. Maximum base slvl is 15. With the correct items equipped, the modified slvl can be brought to a maximum of 20.

When casting a spell from a scroll or staff, it will have the same slvl as the slvl you know the spell (including any modifications from items). If you don’t know the spell it will be cast at slvl 1 (plus any modifications from items). There is a bug, however. If you cast a spell from a scroll and currently have another spell hot keyed, it will use the slvl of the hot keyed spell instead of the spell you are casting. This is true even if you don’t know the spell.


### 4.1.7 Targeting of spells

The casting of spells in Diablo and Hellfire is normally easy to do. Just click on the mouse. Some spells need to be targeted, some change the cursor, and others just cast no matter where you are targeting it. The table below is a summary of how different spells behave.

It is worth noticing that there can be a small delay between the time you click on the mouse and the actual cast of the spell. If you change the cursor position during the time in between, or change the spell, you will normally cast the new spell and the target will be the new position of the cursor. Another side effect of this is that the actual mana reduction is done when the spell is cast which may at times lead to mana reaching negative values (the check for enough mana to cast the spell is done when you click the mouse, while the actual reduction is done when it is cast; due to this effect , one can, if one clicks fast enough, end up with negative mana, or be able to cast a spell twice from a scroll, or squeeze out an extra spell from a staff).


**Area**

The spell does not target in any way and normally affects a larger area. It does not matter where on the screen you position the cursor when you cast this spell. Nova is such a spell.


**Cursor**

The spell will, when cast, change the cursor. You will then have to click on the desired target to be affected by the spell. It does not matter where on the screen you position the cursor when you cast the spell initially. A good example of a spell that affects the cursor is Telekinesis.


**Direction**

The spell is only controllable in that you can affect in what direction from your character the spell will go. Flame Wave is such a spell.


**Target**

The effect of the spell will target the location (or monster) on the screen where the cursor is positioned at the time you cast the spell. Lightning is such a spell.


**Auto**

This spell targets a monster but you do not have to actually point the cursor on the monster, since it will automatically target a specific monster (normally the one closest to the cursor). Some spells are both targeted and automatically seek up a target. This is true for spells like Elemental and Bone Spirit, they are cast at the position you cursor is at but will then automatically seek out a target as well.


**Self**

The spell affects your character directly. Infravision is such a spell.

|**Spell**|**Behavior**|**Spell**|**Behavior**|**Spell**|**Behavior**|
| :- | :- | :- | :- | :- | :- |
|Apocalypse|Area|Healing|Self|Teleport|Target|
|Blood Star|Target|Heal Other|Cursor|Town Portal|Target|
|Bone Spirit|Target/Auto|Holy Bolt|Target|Berserk2|Target/Auto|
|Chain Lightning|Target/Auto1|Identify|Cursor|Immolation|Area|
|Charged Bolt|Direction|Inferno|Direction|Jester3|n/a|
|Elemental|Target/Auto|Infravision|Self|Lightning Wall|Target4|
|Fireball|Target|Lightning|Target|Magi|Self|
|Firebolt|Target|Mana Shield|Self|Mana|Self|
|Fire Wall|Target4|Nova|Area|Reflect|Self|
|Flame Wave|Direction|Phasing|Self/Auto|Ring of Fire|Area|
|Flash|Area|Resurrect|Cursor|Search|Self|
|Golem|Target/Auto|Stone Curse2|Target/Auto|Warp|Self/Auto|
|Guardian|Target/Auto|Telekinesis|Cursor|||
1. Chain Lightning will produce one lightning bolt that is targeted just as normal lightning. The other bolts are automatically targeted.

1. If there is no monster targeted, Stone Curse and Berserk will affect the monster closest to the cursor.

1. This spell casts another random spell. See each individual spell for the behavior.

1. The direction of the wall is always perpendicular to the caster.



## 4.2 Spell casting monsters

Some monsters have the ability to do magical attacks. Monsters in Diablo can only use spells that are available to the player (although they work a bit differently in regard to damage, for example), except for Spitting Terrors. In Hellfire, there are many new monsters that also have the ability to do magical attacks. Often those are new ones that are not available to the player in any way. The tables below summarize all monsters with magical attacks as well as what type of magic it is (not always obvious).

|<a name="page81"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|**Created by Pedro Faria**||||
| :- | :- | :- | :- | :- |
||||||
||**Type**|**Monster**|**Spell/Attack**||
||**Magic**|Succubi|Blood Star||
|||Blightfire (Unique Goat Man)|Blood Star||
|||All Mages|Flash||
|||Spitting Terrors|Spit1||
|||Psychorb|Magic Attack1||
|||Necromorb|Magic Attack1||
|||Spider Lord|Spit1||
|||Bone Demon|Magic Attack1||
|||Lich|Magic Attack1||
|||Arch Lich|Magic Attack1||
||1  These monsters cast spells that are not available to characters.||||
||||||
||**Type**|**Monster**|**Spell/Attack**||
||**Fire**|Counselor|Firebolt||
|||Advocate|Fireball||
|||Balrog|Inferno||
|||Torchant|Fireball||
|||Fire Bat|Firebolt||
|||Hell Bat|Fireball||
||||||
||**Type**|**Monster**|**Spell/Attack**||
||**Lightning**|Familiars|Single stationary Charged Bolt||
|||Magistrate|Charged Bolt||
|||Lightning Demons|Lightning||
|||Cabalist|Lightning||
||||||
||**Type**|**Monster**|**Spell/Attack**||
||**Other**|Diablo|Apocalypse||
|||Skeleton Archer|Arrow1||
|||Goat Archer|Arrow1||
1. Arrows is of course not a spell, but is in many ways technically handled as a spell (with some special cases) by the game. For ease of use together with other parts of this Guide, it is thus useful to list arrow attacks here.


### 4.2.1 Details about monster spells in Diablo

Below are listed all those spells that monsters are able to use. In most cases they are identical to the ones used by players. although some differences can exist. If the damage is stated as *min - max*, the damage is identical to the one listed for melee damage in chapter 5. Note that the charge attacks some monsters can do are, in fact, treated by the game as a type of ”spell,” where the monster itself is the ”spell” projectile. Upon hitting it will do normal melee damage. See chapter 6.1.7 for more information.

|**Apocalypse**|**Arrow**|
| :- | :- |
|Type: n/a|Type: n/a|
|Damage: 40|Damage: min - max|
|Blockable: Yes|Speed: 32|
||Blockable: Yes|
|Note:|Note:|
|\*  Only Diablo can cast apocalypse.|\*  See chapter 5.2.1 for information about min and max|
||damage for monsters.|
||\*  Arrow is of course not a spell, but is in many ways|
||technically handled as a spell (with some special cases)|
||by the game. For ease of use together with other parts|
||of this Guide, it is thus useful to list arrow attacks|
||here.|

|<a name="page82"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|**Created by Pedro Faria**||
| :- | :- | :- |
||||
|**Blood Star**|**Charged Bolt**||
|Type: magic|Type: lightning||
|Damage: min - max|Damage Magistrate: 15||
|Speed: 16|Damage Familiars: 1 - 10||
|Blockable: Yes|Number of bolts:||
||Speed: 8||
||Blockable: Yes||
|Note:|||
|\*  See chapter 5.2.1 for information about min and max|||
|damage for monsters.|||
||||
|**Fireball**|**Firebolt**||
|Type: fire|Type: fire||
|Damage: min - max|Damage: min - max||
|Speed: 16|Speed: 16||
|Blockable: Yes|Blockable: Yes||
|Note:|Note:||
|\*  See chapters 5.2.1 and 5.2.3 for information about|\*  See chapters 5.2.1 and 5.2.3 for information about||
|min and max damage for monsters.|min and max damage for monsters.||
||||
|**Flash**|**Inferno**||
|Type: magic|Type: fire||
|Damage 1: mlvl/32|Damage: min/64 - max/64||
|Damage 2: 4/64|Range: 3||
|Duration: 0.95 seconds|Duration: 1, 1.25 and 1.50 seconds||
|Blockable: No|Blockable: No||
|\*  The Flash spell is actually composed of two different|Note:||
|effects, the two different Damages given are for the|\*  See chapter 5.2.1 for information about min and max||
|two different effects. The first hit in front of the|damage for monsters.||
|monster and to the sides, the other behind the|\*  The three values for duration are for the three target||
|monster.|locations, starting with the one closest to the caster.||
|\*  The flash will try to hit once every 0.05 seconds for a|\*  The flame will try to hit once every 0.05 seconds for a||
|total of 19 times.|total of 20, 25 and 30 times.||
||||
|**Lightning**|**Magma Ball**||
|Type: lightning|Type: fire||
|Damage: min/32 - max/32|Damage: min - max||
|Speed: 32|Speed: 16||
|Duration: 0.5 seconds|Blockable: Yes||
|Blockable: No|||
|\*  The lightning is actually a stationary effect, but the|Note:||
|initiation will be delayed the further away it appears,|\*  See chapters 5.2.1 and 5.2.3 for information about||
|thus giving an appearance of moving. This delay|min and max damage for monsters.||
|”travels” with a speed of 32.|||
|\*  The bolt will try to hit once every 0.05 seconds for a|||
|total of 10 times.|||

|<a name="page83"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|**Created by Pedro Faria**||
| :- | :- | :- |
||||
|**Spit Attack**|**Spit Puddle**||
|Type: magic|Type: magic||
|Damage: min - max|Damage (spit attack): 1/32||
|Speed: 16|Damage (dead Acid Beasts): (Intf + 1)/64||
|Duration: 20 + Intf×5|Duration: 2×(Intf + 1) + Rnd[15]/20 seconds||
|Blockable: Yes|Blockable: No||
|Note:|Note:||
|\*  See chapters 5.2.1 and 5.2.3 for information about|\*  See chapter 5.3.3 for information about intelligence||
|min and max damage for monsters.|factors (Intf) for monsters.||
|\*  See chapter 5.3.3 for information about intelligence|\*  The puddle will try to hit once each 0.05 second for a||
|factors (Intf) for monsters.|total of (Intf + 1)×2 + Rnd[15] times.||
|\*  The duration is actually what determines the distance|||
|a monster can spit.|||

### 4.2.2 Details about new monster spells in Hellfire

Most new monsters in Hellfire that can use spells have new special spells not available to players, although some use ”old” spells. Below are listed all new spells monsters in Hellfire can use. If the damage given is stated as *min - max*, the damage is identical to the one listed for melee damage in chapter 5.

|**Arch Lich attack**|**Bone Demon attack**|
| :- | :- |
|Type: magic|Type: magic|
|Damage: min - max|Damage: min - max|
|Speed: 16|Speed: 16|
|Blockable: Yes|Blockable: Yes|
|Note:|Note:|
|\*  See chapters 5.2.1 and 5.2.3 for information about|\*  See chapters 5.2.1 and 5.2.3 for information about|
|min and max damage for monsters.|min and max damage for monsters.|
|||
|**Lich attack**|**Necromorb attack**|
|Type: magic|Type: magic|
|Damage: min - max|Damage: min - max|
|Speed: 16|Speed: 16|
|Blockable: Yes|Blockable: Yes|
|Note:|Note:|
|\*  See chapters 5.2.1 and 5.2.3 for information about|\*  See chapters 5.2.1 and 5.2.3 for information about|
|min and max damage for monsters.|min and max damage for monsters.|
|||
|**Psychorb attack**||
|Type: magic||
|Damage: min - max||
|Speed: 16||
|Blockable: Yes||
|Note:||
|\*  See chapters 5.2.1 and 5.2.3 for information about||
|min and max damage for monsters.||

## 4.3 Traps

Most traps are of magical nature, and thus it is appropriate to explain how they work here. Traps can be set off when you open chests, sarcophagi, barrels, or doors. There are 7 different types of traps (including skeletons) in the original Diablo. Three new ones were added in Hellfire. The probability of a trap is shown in the table below. Traps originating from shrines are not covered by this guide.

|<a name="page84"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|||**Created by Pedro Faria**|||||||
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|||||||||||
|||||<b>Probability of traps<sup>5</sup></b>||||||
|**Origin**|**Church**|**Catacombs**|**Caves and Hive**|**Hell and Crypt**||||||
|Chest in Diablo|trap:|0 %|arrow:|5 %|arrow:|3\.3 %|arrow:|3\.3 %||
||||fire arrow:|5 %|fire arrow:|3\.3 %|fire arrow:|3\.3 %||
||||||nova:|3\.3 %|nova:|3\.3 %||
|Chest in Hellfire|trap:|0 %|arrow:|5 %|arrow:|1\.7 %|arrow:|1\.7 %||
||||fire arrow:|5 %|fire arrow:|1\.7 %|fire arrow:|1\.7 %||
||||||nova:|1\.7 %|nova:|1\.7 %||
||||||ring of fire:|1\.7 %|ring of fire:|1\.7 %||
||||||mana drain:|1\.7 %|mana drain:|1\.7 %||
||||||disenchant:|1\.7 %|disenchant:|1\.7 %||
|Sarcophagus|skeleton:|20 %|n/a|n/a||n/a||||
|Barrel, Pods and Urns|explosion:|20%2|explosion:|20%2|explosion:|20%2|explosion:|20%2||
|outside rooms|skeleton:|16%3|skeleton:|16%3|skeleton:|0 %|skeleton:|0 %||
|Barrels, Pods and Urns|explosion:|50 %|explosion:|83 %|explosion:|75 %|explosion:|88 %||
|inside rooms6|skeleton:|0 %|skeleton:|0 %|skeleton:|0 %|skeleton:|0 %||
|**Origin**|**dlvl 1-2**|**dlvl 3-5**|**dlvl 6-8**|<b>dlvl 9-16<sup>4</sup></b>||||||
|Doors5|arrow:|100 %|arrow:|50 %|arrow:|33\.3 %|n/a|||
||||firebolt:|50 %|firebolt:|33\.3 %||||
||||||lightning:|33\.3 %||||
1. Sarcophagi only exist in the Crypt, never in Hell.
1. In each cluster of barrels, pods and urns, the first barrel placed has a 25% chance having an explosion trap. All subsequent barrels have a 20% chance. As the number of barrels in a cluster is very hard to calculate accurately, I have used the value of 20% for all barrels. This will also affect the value for skeletons slightly, as it is 20% for a *non* exploding barrel.

1. Skeleton traps are, of course, only available if there are skeletons on the same level.

1. Hell and Crypt can’t have traps form doors.

1. The probabilities for doors apply to doors that *do* have traps. It seems that the probability to have traps is linked to the actual dungeon layout for doors in that it needs a wall opposite to it.

1. Rooms also includes the fenced locations in caves. A room does not necessarily need to have a door, in cats and especially in hell, many rooms just have an opening.

For damage and other information about the traps, see below. For damage, when two values or formulas are given, the top one is minimum damage and the bottom one is maximum damage. With fire arrows, the maximum damage might at times be less than the minimum damage (possible on dlvl 1-8). In that case, the actual damage done is always identical to the minimum damage. The table also list some dungeon features that while not being traps, still deal damage to players.

|<a name="page85"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**||**Created by Pedro Faria**|||||
| :- | :- | :- | :- | :- | :- | :- |
||||||||
|**Trap**|**Damage**|||**Speed/Duration**|**Other**||
|Arrow|Min: dlvl|||32|Will fire an arrow, originating from the||
||Max: 2×dlvl||||nearest wall.1||
|Burning cross|Church:|6/64||n/a|The flame will hit once every 0.05 seconds||
||Catacombs:|8/64|||for as long as you are standing in it.||
||Caves:|10/64|||||
||Hell:|12/64|||||
|Fire Arrow|Min: dlvl + Rnd[10] + 1||32|Will fire an arrow, originating from the|||
||Max: 2×dlvl + Rnd[10] + 1||nearest wall.1||||
|Firebolt|dlvl + Rnd[2×dlvl]|||26|Will cast the spell Firebolt, originating||
||||||from the nearest wall.1||
|Lightning|(dlvl + Rnd[dlvl])/32||32 / 0.4 seconds2|Will cast the spell Lightning, originating|||
||||||from the nearest wall.1||
|Nova|Itt(3, Rnd[3]) + dlvl/2||32|Will cast the spell Nova, originating from|||
||||||the chest.||
|Exploding barrel|Min: 8|||n/a|An exploding barrel does fire damage and||
||Max: 16||||is treated like a Firebolt hitting.||
|Skeleton|n/a|||n/a|Will create a random skeleton of those||
||||||present on the same dlvl.||
|Ring of Fire|(Rnd[10] + Rnd[10] + dlvl|Unknown|Will cast the spell Ring of Fire, originating||||
||+ 2)/8||||from the chest.||
|Mana Drain|n/a|||n/a|Will drain you of all current mana. This||
||||||trap has the ability to affect other players||
||||||on the same dlvl.||
|Disenchant potions|Full Healing:||Healing|For each potion in your belt, there is a|||
||Full Mana:||Mana|50% chance that it will be replaced with|||
||Full Rejuvenation:||Rejuvenation - 33%|another potion according to the left. If|||
||||Full Healing - 33%|several possibilities exist, the chance is|||
||||Full Mana - 33%|equal for all possibilities and shown after|||
||Healing:||destroyed|the potion. This trap has the ability to|||
||Mana:||destroyed|affect other players on the same dlvl.|||
||Rejuvenation:||Healing - 50%||||
||||Mana - 50%||||
1. In caves, hell, the Hive, and the Crypt it will originate form the chest, pod or urn.
1. The bolt will try to hit once every 0.05 seconds.


**To Hit**

To Hit for traps is calculated according to the formulas below.

|To Hit for an arrow trap:|100 - AC/2|
| :- | :- |
|To Hit for a magic trap:|40|

As with attacks from monsters, there is also an automatic chance of hitting for traps, and it is listed below. Of course, the auto To Hit for magic traps is 40%, even on dungeon levels 14 to 16.

|arrow trap:|10%|
| :- | -: |
|magic trap:|40%|
|on dungeon level 14:|20%|
|on dungeon level 15:|25%|
|on dungeon level 16:|30%|

- magic traps includes Fire Wall, Flame Wave and Ring of Fire attacks from other players.


# 5. Monsters

This chapter deals with all the monsters you will face in the dungeons. As there are both many monsters and much data about each of them, it has been divided into several different types of tables for easier use. First are the tables with complete data about most things that affect combat for each monster on all difficulty levels (except for timing data). Then you will find tables with all data that is normally common for within each monster type (this includes things such as monster size, timing data, occurrence and attack type). Finally, monster AI has its own section. In the end I have made a few summary tables with selected data and some additional information. They have been constructed for ease of use during play. In them you can quickly check for example what monsters can be on a level, what resistances they have, and if you will get any experience. Included in this chapter are also special tables for the unique monsters. Note that although they are ”unique”, data about Diablo, Skeleton King, and The Butcher from Diablo, and Hork Demon, The Defiler, and Na-Krul from Hellfire are presented among the normal monsters (in their own table). The reasons for this are several but are mainly due to the fact that they are truly unique and not based on any other monster type.



## 5.1 How to calculate monster data

Data for nightmare and hell difficulties is calculated from the data for normal difficulty, and here follows information on how that is done as well as some description of the actual data. All data in the tables for nightmare and hell have been calculated using these formulas. Unique monsters generally follow the same formulas but more detailed information about data for unique monsters is found in chapter 5.4.


**Monster type**

Each monster can be one of three types: Undead, Animal or Demon. The type they are affects how much damage you do to them. It is summarized in the table below provided by Da O’Toth. The modifiers apply to the whole damage, that is, both to character and weapon damage. If a Bard is holding one sword and one club, the club takes precedence and it counts as having a club, *not* a sword. The modifications below are done even if the weapon equipped is red, and thus unusable, due to the requirements not being met.

|**Weapon type**|**Undead**|**Animal**|**Demon**|
| :- | :-: | :-: | :-: |
|Swords|× 0.5|× 1.5|× 1.0|
|Clubs|× 1.5|× 0.5|× 1.0|
|Axes/Bows/Staves/Hands/Feet|× 1.0|× 1.0|× 1.0|

In addition to the above, monster type also affects if a monster will take damage from the spell Holy Bolt. Only undead monsters take damage from it. The only exception is Diablo who is a demon but yet takes damage from Holy Bolt. There are a few magical effects on items that are also dependent on monster type (+200% damage versus demons, extra AC versus undead, and extra AC versus demons, the last two only available in Hellfire). There are no other effects of the monster type.


**Dungeon Level**

This tells on what dungeon level the monster can occur on. This does not differ between difficulty levels. For more information about probabilities of monsters occurring on a specific dungeon level, see chapter 5.3.2.


|**Monster level**||
| :- | :- |
|Nightmare:|normal + 15|
|Hell:|normal + 30|

A monster’s level affects many things, including To Hit and experience points given. It also affects how fast it regenerates hit points, what treasures it can drop, and many other things. For some unique monsters, one should add +30/+60 instead of the normal +15/+30. For information about this, see chapter 5.4.


**Hit points**

First note that all data for hit points is based on the value for normal multi player (even in Hellfire). To calculate the hit points for normal single player, divide the hit points for normal multi player by 2 and round down (1 minimum though). For higher difficulty levels then use:

Nightmare:	3×normal + 1 (+50 in Hellfire single player and +100 in Hellfire multi player)

Hell:	4×normal + 3 (+100 in Hellfire single player and +200 in Hellfire multi player)

Note that there is a bug in Diablo previous to v1.07 and in the unpatched Hellfire (v1.00). This bug was ”corrected” differently in Hellfire and Diablo. In the tables the hit points for single player are correct for both Diablo and Hellfire (remember that in Diablo, only normal difficulty exists for single player). For multi player, the shown hit points are for Diablo; for Hellfire, you need to add 99 and 197 hit points in nightmare and hell difficulties respectively.

All monsters regenerate hit points. The rate is about 10×mlvl/64 hit points per second. Some monsters might regenerate it faster in some circumstance. Gargoyles, Scavengers and Grave Diggers will all, after having taken a certain amount of damage, move away and start *healing*. Gargoyles do so when in their stone form, while the other two need a carcass of a monster to eat or dig upon. The table below summarize monster regeneration of hit points.

|**Monster type**|**When to start healing**|**When to stop healing**|<b>Rate<sup>1</sup></b>|
| :- | :-: | :-: | :- |
|Scavenger|HP < maxHP/2|HP > 3×maxHp/4|1\.82 hit points per second.|
|Gargoyle|HP < maxHP/2|HP = maxHP|random between 20×maxHP/64 and|
||||20×maxHP/128 hit points per second2.|
|Grave Digger|HP < maxHP/2|HP > 3×maxHp/4|1\.25 hit points per second.|

1. Note that they still get the normal regeneration rate on top of the faster one.
1. The time to completely regenerate HP is thus fixed to between 3.2 and 6.4 seconds.

Regeneration of hit points, as well as any other activity on a dungeon level, only works when the level is ”active”, that is, when at least one character is present on the level. When a level is later reactivated by any character entering it, monsters will have the exact same number of hit points as when the last character left the level.


|**Armor Class**||
| :- | :- |
|Nightmare:|normal + 50|
|Hell:|normal + 80|

Note that there is a bug in Hellfire that causes any monster having an AC above 127 to instead have a very low, or even negative, AC.


**Attacks**

All data for To Hit in the tables are for the physical attacks only. Magic attacks do not use any base To Hit. The damage value is usually used both for melee and magic attacks. For magic attacks, see chapter 4.2. Some monsters have more than one melee attack. Sometime they are connected in the way that each attack animation (that is each attack) has two chances of hitting at different times of the animation. They can hit with both their hands. An example of this is the Lightning Demons. In the other cases it is two different attacks (with two different animations) and the monster can only do one of them at a time. An example of this is the Overlords which can attack with either hand or the Spitting Terrors which can either attack in melee or cast a spell (spit). The table will only hold information about the main melee attack while information about the second melee attack or the spell attack is given in the notes. Often the second melee attack is sort of crippled in that the base To Hit and damage are both 0 on normal difficulty (and upgraded normally for difficulty) which make it more or less ineffective as it hardly ever hit and when it do it, it do none or neglectable damage.


|**To Hit**||
| :- | :- |
|Nightmare:|normal + 85|
|Hell:|normal + 120|

Note that the To Hit values shown in the tables are the *base* To Hit chance a monster has. The formula for a monster hitting a player is:

|To Hit with melee attack:|30 + base + 2×(mlvl - clvl)||
| :- | :- | :- |
|To Hit with arrow attack:|30|+ base + 2×(mlvl - clvl) - 2×distance|
|To Hit with magic attack:|40|+ 2×(mlvl - clvl)|

- The term *base* refers to the To Hit values found in the tables. For charges, it is always 500.

- All magic attacks will always check for To Hit, even for spells like Lightning and Inferno.

- Distance is actually a time count. It goes up by 20 each second. Arrows always have a distance factor, even if they have extra fire or lightning damage. For more information see chapters 4.1.2.

- To get the final chance of hitting, you subtract the AC of the enemy (normally a player) except if it is a magic attack, of course.
- For more detailed information about battle between players and monsters, see chapter 6.

Each monster also has an automatic To Hit value, just like players (monsters don’t have any chance to automatically miss unless fighting other monsters; in that case, they use the same chance to automatically hit or miss as players do). This indicates the chance of a hit regardless of the player’s AC. So even with an AC of 500, monsters will sometimes hit you. The attack can still be blocked, however. The auto To Hit values are listed below.

|melee:|15%|
| :- | -: |
|arrow:|10%|
|magic:|10%|
|on dungeon level 14:|20%|
|on dungeon level 15:|25%|
|on dungeon level 16:|30%|

- The auto To Hit values for special dungeon levels apply to all types of attack (melee, arrow and magic).

- In multi player the game uses a rather bad way to keep the computers in synchronization with each other, this may at times lead to strange results as far as monsters attacking are concerned. It may for example seem that the monster get ”stuck” and misses the player for way to long time. For more information, see chapter 5.5.8.

**Damage**

Nightmare:	2×normal + 4

Hell:	4×normal + 6


**Resistance and immunity**

Nightmare:	same as in normal

Hell:	different resistances and immunities, but normally they gain extra

resistances and/or immunities and some of the resistances are turned

into immunities. Exceptions exist, though. Unique monsters have the

same resistances and immunities as in normal difficulty.

- When a monster is resistant to a spell type the damage is always reduced by 75%.

- All monsters, except undead ones and Diablo, are immune to Holy Bolt.

- In Hellfire, Diablo and Bone Demons are resistant to Holy Bolt.

- Diablo and Na-Krul are immune to Stone Curse.

- No monster is immune or resistant to Apocalypse.

**Experience points**

The experience points gained for killing a monster is explained in chapter 2.6. The base experience points used for those calculations are adjusted according to:

Nightmare:	2×normal + 2000

Hell:	4×normal + 4000


## 5.2 Monster data

Each monster type is presented in its own table below. In Diablo, each monster type has four subtypes of monsters that differ in color and stats. The monsters in Hellfire do not follow this pattern, and have instead been grouped into two sections: monsters found in the Hive and monsters found in the Crypt. Finally, there is a table for the special monsters: Diablo, Skeleton King and The Butcher in Diablo, and Hork Demon, The Defiler and Na-Krul in Hellfire.

Data for unique monsters is presented in chapter 5.4.

In each table, each monster has data in three lines corresponding to the three difficulty levels. The top line is for normal, the middle one for nightmare and the bottom line for hell. As the resistances and immunities are the same for nightmare as for normal they are only given once for normal. Dungeon levels are the same regardless of difficulty level and are thus only given once for each monster.

Resistances and immunities are given in the following way. In the top of the column it says MFL. That corresponds to Magic, Fire, and Lightning, in that order. Below are then listed if the monsters are resistant, R, or immune, I. If there is no letter or there is a ”-”, it means the monster is neither resistant nor immune.


### 5.2.1 Monsters in Diablo

**Zombies - Undead**

||**Name**|**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**|||||
| :- | :- | -: | -: | :- | :- | -: | -: | -: | :- | -: | :- | :- | :- | :- |
|||||**(Hellfire)**|**(Diablo)**||||||||||
||||1|2-|3|4-|7|5|10|2-  5|I--|54|||
||Zombie|1- 2|16|56-|59|13-|22|55|95|8- 14||2 108|||
||||31|108-|112|19-|31|85|130|14- 26|I--|4 216|||
||||2|3-|5|7-|11|10|10|3- 10|I--|58|||
||Ghoul|2- 3|17|59-|65|22-|32|60|95|10- 24||2 116|||
||||32|112-|120|31-|47|90|130|18- 46|I--|4 232|||
||||4|7-|12|15-|25|15|25|5- 15|I--|136|||
||Rotting Carcass|2- 4|19|71-|86|46-|76|65|110|14-|34||2 272||
||||34|128-|148|63-|103|95|145|26- 66|IR-|4 544|||
||||6|12-|20|25-|40|20|30|6- 22|I--|240|||
||Black Death1|3- 5|21|86-|110|76-|121|70|115|16- 48||2 480|||
||||36|148-|180|103-|163|100|150|30- 94|I-R|4 960|||
||1  Black Deaths have the ability to lower your life *permanently* by 1 when they hit you.||||||||||||||
||||||||||||||||
||<b>Fallen Ones with spear<sup>1</sup> - Animals</b>||||||||||||||
||**Name**|**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**|||||
|||||**(Hellfire)**|**(Diablo)**||||||||||
||||1|1-|2|1-|4|0|15|1-  3||46|||
||Fallen One|1- 3|16|53-|56|4-|11|50|100|6- 10||2 092|||
||||31|104-|108|7-|19|80|135|10- 18||4 184|||
||||3|2-|4|4-|8|5|20|2-  5||80|||
||Carver|2- 3|18|56-|62|13-|25|55|105|8- 14||2 160|||
||||33|108-|116|19-|35|85|140|14- 26||4 320|||
||||5|6-|12|12-|24|10|25|3-|7||155||
||Devil Kin|2- 4|20|68-|86|37-|71|60|110|10- 18||2 310|||
||||35|124-|148|51-|99|90|145|18- 34|-R-|4 620|||
||||7|10-|18|20-|36|15|30|4-|8||255||
||Dark One|3- 5|22|80-|104|61-|109|65|115|12- 20||2 510|||
||||37|140-|172|83-|147|95|150|22- 38|--R|5 020|||
1	When you kill any monster, Fallen Ones will walk away from you for a short while, see chapter 5.5.9 under Fallen One.

||<a name="page90"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|||||**Created by Pedro Faria**||||||||||
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|||||||||||||||||
|<b>Fallen Ones with sword<sup>1</sup> - Animals</b>||||||||||||||||
|**Name**||**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**||||||
||||||**(Hellfire)**|**(Diablo)**||||||||||
|||||1|1-|2|2-|5|10|15|1-  4||52|||
|Fallen One||1- 3|16|53-|56|7-|16|60|100|6- 12||2 104||||
|||||31|104-|106|11-|23|90|135|10- 22||4 208|||
|||||3|2-|4|5-|9|15|20|2-  7||90|||
|Carver||2- 3|18|56-|62|16-|28|65|105|8-|8||2 180|||
|||||33|108-|116|23-|39|95|140|14- 34||4 360|||
|||||5|8-|12|16-|24|20|25|4- 10||180|||
|Devil Kin||2- 4|20|74-|86|49-|73|70|110|12- 24||2 360||||
|||||35|132-|148|67-|99|100|145|22- 46|-R-|4 720|||
|||||7|12-|18|24-|36|25|30|4- 12||280|||
|Dark One||3- 5|22|86-|106|73-|109|75|115|12- 28||2 560||||
|||||37|148-|172|99-|147|105|150|22- 54|--R|5 120|||
||1  When you|kill any monster, Fallen Ones will walk away from you for a short while, see 5.5.9 under Fallen One.||||||||||||||
|||||||||||||||||
|**Skeletons - Undead**||||||||||||||||
|**Name**||**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**||||||
||||||**(Hellfire)**|**(Diablo)**||||||||||
|||||1|1-|2|2-|4|0|20|1-  4|I--|64|||
|Skeleton||1- 2|16|53-|56|7-|13|50|105|6-|12||2 128|||
|||||31|104-|108|9-|19|80|140|10- 22|I--|4 256|||
|||||2|2-|3|4-|7|0|25|3-  5|I--|68|||
|Corpse Axe||2- 3|17|56-|59|13-|22|50|110|10- 14||2 136||||
|||||32|108-|112|19-|31|80|145|18- 26|I--|4 272|||
|||||4|4-|6|8-|12|5|30|3-|7|IR-|154||
|Burning Dead||2- 4|19|62-|68|25-|37|55|115|10- 18||2 308||||
|||||34|116-|124|35-|51|85|150|18- 34|II-|4 616|||
|||||6|6-|10|12-|20|15|35|4-|9|I-R|264||
|Horror||3- 5|21|68-|80|37-|61|65|120|12- 22||2 528||||
|||||36|124-|140|51-|83|95|155|22- 42|I-R|5 056|||
|||||||||||||||||
|<b>Skeleton Archers<sup>1</sup> - Undead</b>||||||||||||||||
|**Name**||**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**||||||
||||||**(Hellfire)**|**(Diablo)**||||||||||
|||||3|1-|2|2-|4|0|15|1-|2|I--|110||
|Skeleton Archer||2- 3|18|53-|56|7-|13|50|100|6-|8||2 220|||
|||||33|104-|108|11-|19|80|135|10- 14|I--|4 440|||
|||||5|4-|8|8-|16|0|25|1-|4|I--|210||
|Corpse Bow||2- 4|20|62-|66|25-|33|50|110|6- 12||2 420||||
|||||35|116-|132|35-|67|80|145|10- 22|I--|4 840|||
|||||7|5-|12|10-|24|5|30|1-|6|IR-|364||
|Burning Dead||3- 5|22|65-|86|31-|73|55|115|6- 16||3 728||||
|Archer|||37|120-|148|43-|99|85|150|10- 30|II-|5 456||||
|||||9|7-|22|15-|45|15|35|2-|9|I-R|594||
|Horror Archer||4- 6|24|71-|116|46-|136|65|120|8- 22||3 188||||
|||||39|128-|190|63-|183|95|155|14- 42|I-R|6 376|||

1. They can fire arrows at a golem regardless of the distance (assuming they have a line of sight to it) but will not be activated unless the golem is adjacent to them.

||<a name="page91"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|||||**Created by Pedro Faria**|||||||||
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
||||||||||||||||
|**Skeleton Captains - Undead**|||||||||||||||
|**Name**|**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**||||||
|||||**(Hellfire)**|**(Diablo)**||||||||||
||||2|1-|3|3-|6|10|20|2-  7|I--|90|||
|Skeleton Captain|1- 3|17|53-|59|10-|19|60|105|8-|18||2 180|||
||||32|104-|112|15-|27|90|140|14- 34|I--|4 360|||
||||4|6-|10|12-|20|5|30|3-|9|I--|200||
|Corpse Captain|2- 4|19|68-|80|37-|61|55|115|10- 22||2 400||||
||||34|124-|140|51-|83|85|150|18- 42|I--|4 800|||
||||6|8-|15|16-|30|15|35|4- 10|IR-|393|||
|Burning Dead|3- 5|21|74-|95|49-|91|65|120|12- 24||2 786||||
|Captain||36|132-|160|67-|123|95|155|22- 46|II-|5 472||||
||||8|17-|25|35-|50|30|40|5- 14|I-R|604|||
|Horror Captain|4- 6|23|101-|125|106-|151|80|125|14- 32||3 208||||
||||38|168-|200|143-|203|110|160|26- 62|I-R|6 416|||
||||||||||||||||
|<b>Scavengers<sup>1</sup> - Animals</b>|||||||||||||||
|**Name**|**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**||||||
|||||**(Hellfire)**|**(Diablo)**||||||||||
||||2|1-|3|3-|6|10|20|1-  5||80|||
|Scavenger|1- 3|17|53-|59|10-|19|60|105|6- 14||2 160||||
||||32|104-|112|15-|27|90|140|10- 26|-R-|4 320|||
||||4|6-|12|12-|24|20|30|1-|8||188||
|Plague Eater|2- 4|19|68-|86|37-|73|70|115|6- 20||2 376||||
||||34|124-|148|51-|99|100|150|10- 38|--R|4 752|||
||||6|12-|18|24-|36|25|35|3- 12||375|||
|Shadow Beast|3- 5|21|86-|104|73-|109|75|120|10- 28||2 750||||
||||36|148-|172|99-|147|105|155|18- 54|-R-|5 500|||
||||8|14-|20|28-|40|30|35|5- 15|R--|552|||
|Bone Gasher|4- 6|23|92-|110|85-|121|80|120|14- 34||3 104||||
||||38|156-|180|115-|163|110|155|26- 66|--R|6 208|||
||1  Scavengers|have the ability to regenerate hit points faster while feasting on dead monsters.|||||||||||||
||||||||||||||||
|<b>Winged Fiends<sup>1</sup> - Animals (Familiars are demons)</b>|||||||||||||||
|**Name**|**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**||||||
|||||**(Hellfire)**|**(Diablo)**||||||||||
||||3|1-|3|3-|6|0|35|1-|6||102||
|Fiend|2- 3|18|53-|59|10-|19|50|120|6- 16||2 204||||
||||33|104-|112|15-|27|80|155|10- 30||4 408|||
||||7|6-|14|12-|28|15|45|1-|8||340||
|Blink2|3- 5|22|68-|92|37-|85|65|130|6- 20||2 680||||
||||37|124-|156|51-|115|95|165|10- 38||5 360|||
||||9|14-|18|28-|36|35|70|4- 12|R--|509|||
|Gloom3|4- 6|24|92-|104|85-|109|85|155|12- 28||3 018||||
||||39|156-|172|115-|147|115|190|22- 54|R--|6 036|||
||||13|10-|17|20-|35|35|50|4- 16|R-I|448|||
|Familiar4|6- 8|28|80-|101|61-|106|85|135|12-|36||2 896|||
||||43|140-|168|83-|143|115|170|22- 70|R-I|5 792|||

1. Winged Fiends never drop any items or gold. A unique Winged Fiend does, however.
1. Blinks have the ability to Teleport to a square next to you when they are hit and go into hit recovery. The teleportation can thus be said to be their hit recovery.

1. Glooms have the ability to charge, like the Horned Demons, but will never attack with it. It is just a way for them to move around.

1. Familiars have the ability to cast a stationary charged bolt when attacking you.

||<a name="page92"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|||||**Created by Pedro Faria**|||||||||
| :- | -: | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
||||||||||||||||
|<b>The Hiddens<sup>1</sup> - Demons</b>|||||||||||||||
|**Name**|**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**||||||
|||||**(Hellfire)**|**(Diablo)**||||||||||
||||5|4-|12|8-|24|25|35|3-|6||278||
|Hidden|2- 5|20|62-|86|25-|73|75|120|10- 16||2 556||||
||||35|116-|148|35-|99|105|155|18- 30||5 112|||
||||9|15-|22|30-|45|30|40|8- 16||630|||
|Stalker|5- 7|24|95-|116|91-|136|80|125|20-|36||3 260|||
||||39|160-|188|123-|183|110|160|28- 70||6 520|||
||||11|17-|25|35-|50|30|45|12- 20|R--|935|||
|Unseen|6- 8|26|101-|100|106-|151|80|130|28- 44||3 870||||
||||41|168-|200|143-|203|110|165|54- 86|I--|7 740|||
||||13|20-|30|40-|60|30|60|16- 24|RR-|1 500|||
|Illusion Weaver2|8-10|28|110-|140|121-|181|80|145|36- 52||5 000||||
||||43|180-|220|163-|243|110|180|70-102|IR-|10 000|||

1. The Hiddens have the ability to disappear. They are always active and can always see you, even with max reduced light radius, regardless of whether or not you have a line of sight to them and regardless of the distance. They will fade in at a distance of 4-Intf and fade away at a distance of 6-Intf. See chapter 5.3.3 for information about the intelligence factor (Intf).
1. While moving away from you (after getting hit), the Illusion Weavers are impossible to hit.

<b>Goat Men<sup>2</sup> - Demons</b>

||**Name**|**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**||||
| :- | :- | :- | -: | -: | -: | -: | -: | -: | :- | -: | :- | :- | :- |
|||||**(Hellfire)**|**(Diablo)**|||||||||
|||<sub>2</sub>1|8|15-|22|30-|45|40|50|4- 10||460||
||Flesh Clan|4- 6|23|95-|116|91-|136|90|135|12- 24||2 920||
||||38|160-|188|123-|183|120|170|22- 46||5 840||
||||10|20-|27|40-|55|40|60|6- 12|R--|685||
||Stone Clan|5- 7|25|110-|131|121-|166|90|145|16- 28||3 370||
||||40|180-|208|163-|223|120|180|30- 54|I--|6 740||
||||12|25-|32|50-|65|45|70|8- 16|-R-|906||
||Fire Clan|6- 8|27|125-|146|151-|196|95|155|20- 36||3 812||
||||42|200-|228|203-|263|125|190|38- 70|-I-|7 624||
||||14|27-|35|55-|70|50|80|10- 20|R--|1 190||
||Night Clan|7- 9|29|131-|155|166-|211|100|165|24- 44||4 380||
||||44|208-|240|223-|283|130|200|46- 86|I--|8 760||
1. They only appear on level 2 as part of the Poisoned Water quest.
1. Goat Men have a second spinning attack. They will only perform this attack once their HP gets low (see chapter 5.5.9). Flesh, Stone and Fire Clan have a base To Hit of 0, 85 and 120 for the three difficulty levels while the damage is 0-0, 4-4 and 6-6. Night Clan have a base To Hit of 15, 100 and 135 while the damage is 30-30, 64-64 and 126-126.

<b>Goat Men Archers<sup>1</sup> - Demons</b>

||**Name**|**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**|||||
| :- | :- | :- | -: | -: | -: | -: | -: | -: | :- | -: | :- | :- | :- | :- |
|||||**(Hellfire)**|**(Diablo)**||||||||||
|||22|8|10-|17|20-|35|35|35|1-|7||448||
||Flesh Clan Archer|4- 6|23|80-|101|61-|106|85|120|6- 18||2 896|||
||||38|140-|168|83-|143|115|155|10- 34||5 792|||
||||10|15-|20|30-|40|35|40|2-|9|R--|645||
||Stone Clan Archer|5- 7|25|95-|110|91-|121|85|125|8- 22||3 290|||
||||40|160-|180|123-|163|115|160|14- 42|I--|6 580|||
||||12|20-|25|40-|50|35|45|3- 11|-R-|822|||
||Fire Clan Archer|6- 8|27|110-|125|121-|151|85|130|10- 26||3 644|||
||||42|180-|200|163-|203|115|165|18- 50|-I-|7 288|||
||||14|25-|32|50-|65|40|50|4- 13|R--|1 092|||
||Night Clan Archer|7- 9|29|125-|146|151-|196|90|135|12- 30||4 184|||
|||103|44|200-|228|203-|263|120|170|22- 58|I--|8 368|||
1. They can fire arrows at a golem regardless of the distance (assuming they have a line of sight to it) but will not be activated unless the golem is adjacent to them.

1. They only appear on level 2 as part of the Poisoned Water quest.

1. They only appear on level 10 as part of the Anvil of Fury quest.

||<a name="page93"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|||||**Created by Pedro Faria**||||||||
| :- | -: | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|||||||||||||||
|<b>Overlords<sup>1</sup> - Demons</b>||||||||||||||
|**Name**|**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**|||||
|||||**(Hellfire)**|**(Diablo)**|||||||||
|||42|10|30-|40|60-|80|55|55|6- 12||635||
|Overlord|5- 7|25|140-|170|181-|241|105|140|16- 28||3 270|||
||||40|220-|260|243-|323|135|175|30- 54|-R-|6 540||
||||14|50-|62|100-|125|60|60|8- 16||1 165||
|Mud Man|7- 9|29|200-|236|301-|376|110|145|20- 36||4 330|||
||||44|300-|348|403-|503|140|180|38- 70|--I|8 660||
||||16|67-|80|135-|160|65|70|8- 16|I--|1 380||
|Toad Demon|8-10|31|251-|270|406-|441|115|155|20- 36||4 760|||
||||46|368-|420|543-|643|145|190|38- 70|I-R|9 520||
||||20|80-|100|160-|200|70|85|10- 20|RI-|2 058||
|Flayed One|10-12|35|290-|350|481-|601|120|170|24- 44||6 116|||
||||50|420-|500|643-|803|150|205|48- 86|II-|12 232||

1. Overlords have a second melee attack. Overlord, Mud Man and Flayed One have a base To Hit of 0, 85 and 120 for the three difficulty levels while the damage is 0-0, 4-4 and 6-6. Toad Demon have a base To Hit of 40, 125 and 160 while the damage is 8-20, 20-44 and 38-86.
1. They only appear on level 4 as part of the Tavern Sign quest.

<b>Gargoyles<sup>1,2</sup> - Demons</b>

||**Name**|**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**||||
| :- | :- | :- | -: | -: | -: | -: | -: | -: | :- | -: | :- | :- | :- |
|||||**(Hellfire)**|**(Diablo)**|||||||||
||||9|22-|30|45-|60|45|50|10- 16|IR-|662||
||Winged-Demon|5- 7|24|116-|140|136-|181|95|135|24- 36||3 324||
||||39|188-|220|183-|243|125|170|48- 70|II-|6 648||
||||13|30-|45|60-|90|45|65|10- 16|I-R|1 205||
||Gargoyle|7- 9|28|140-|185|181-|271|95|150|24- 36||4 410||
||||43|220-|280|243-|363|125|185|48- 70|I-I|8 820||
||||19|37-|62|75-|125|50|80|14- 22|II-|1 873||
||Blood Claw|9-11|34|161-|236|226-|376|100|165|32- 48||5 746||
||||49|248-|348|303-|503|130|200|62- 94|IIR|11 492||
||||23|45-|75|90-|150|60|95|16- 28|I-I|2 278||
||Death Wing|10-12|38|185-|275|271-|451|110|180|36- 60||8 556||
||||53|280-|400|363-|603|140|215|70- 90|IRI|13 112||
1. Gargoyles have the ability to regenerate hit points faster while in stone form.
1. If you leave a level all Gargoyles are active when you come back.

<b>Magma Demons<sup>1,2</sup> - Demons</b>

||**Name**|**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**||||
| :- | :- | :- | -: | -: | -: | -: | -: | -: | :- | -: | :- | :- | :- |
|||||**(Hellfire)**|**(Diablo)**|||||||||
||||13|25-|35|50-|70|45|45|2- 10|IR-|1 076||
||Magma Demon|8- 9|28|125-|155|151-|211|95|130|8- 24||4 152||
||||43|200-|240|203-|283|125|165|14- 48|II-|8 304||
||||14|28-|37|55-|75|45|50|2- 12|II-|1 309||
||Blood Stone|8-10|29|134-|161|166-|226|95|135|8- 28||4 618||
||||44|212-|248|223-|303|125|170|14- 54|II-|9 236||
||||16|30-|40|60-|80|50|60|2- 20|II-|1 680||
||Hell Stone|9-11|31|140-|170|181-|241|100|145|8- 44||5 360||
||||46|220-|260|243-|323|130|180|14- 86|II-|10 720||
||||18|35-|42|70-|85|60|75|4- 24|II-|2 124||
||Lava Lord|9-11|33|155-|176|211-|256|110|160|12- 52||6 248||
||||48|240-|268|283-|343|140|195|22-102|II-|12 496||
1. Magma demons may hit with their second hand as well. Such an attack has the To Hit increased by 10% and the damage decreased by 2.

1. Magma Demons have the ability to cast magma balls, which do fire damage.

||<a name="page94"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|||||**Created by Pedro Faria**||||||||
| :- | -: | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|||||||||||||||
|<b>Horned Demons<sup>1</sup> - Animals</b>||||||||||||||
|**Name**|**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**|||||
|||||**(Hellfire)**|**(Diablo)**|||||||||
|||52|13|20-|40|40-|80|40|60|2- 16||1 172||
|Horned Demon|7- 9|28|110-|170|121-|241|90|145|8- 36||5 344|||
||||43|180-|260|163-|323|120|180|14- 70|-R-|8 688||
||||15|25-|45|50-|90|45|70|6- 18||1 404||
|Mud Runner|8-10|30|125-|185|151-|271|95|155|16- 40||4 808|||
||||45|200-|280|203-|363|125|190|30- 78|-R-|9 616||
||||17|30-|50|60-|100|50|80|8- 20|I-R|1 720||
|Frost Charger|9-11|32|140-|200|181-|301|100|165|20- 44||5 440|||
||||47|220-|300|243-|403|130|200|38- 86|I-R|10 880||
||||19|35-|55|70-|110|55|90|10- 22|I-R|1 809||
|Obsidian Lord|10-12|34|155-|215|211-|331|105|175|24- 48||5 618|||
||||49|240-|320|283-|443|135|210|46- 94|III|11 236||

1. Horned Demons have the ability to charge. Their charges have a base To Hit of 500%, so you’d better move out of the way. The damage of such a charge is - Horned Demon: 5-32 / 12-68 / 26-134, Mud Runner: 12-36 / 28-76 / 54-150, Frost Charger: 20-40 / 44-84 / 86-166 and Obsidian Lord: 20-50 / 44-104 / 86-206.
1. They only appear on level 5 as part of the Valor quest.

<b>Spitting Terrors<sup>1</sup> - Animals</b>

||**Name**|**dlvl**||**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**||||
| :- | :- | -: | :- | :- | :- | :- | -: | -: | -: | :- | -: | :- | :- | :- |
||||||**(Hellfire)**|**(Diablo)**|||||||||
|||||11|20-|33|40-|66|30|40|4- 12||846||
||Acid Beast|6- 8||26|110-|149|121-|199|80|125|12- 28||3 692||
|||||41|180-|232|163-|267|110|160|22- 54|I--|7 384||
|||||15|30-|42|60-|85|30|45|4- 16||1 248||
||Poison Spitter|8-10||30|140-|176|181-|256|90|130|12- 36||4 496||
|||||45|220-|268|243-|343|110|165|22- 70|I--|8 992||
|||||21|40-|55|80-|110|35|55|8- 18|R--|2 060||
||Pit Beast|10-12||36|170-|215|241-|331|85|140|20- 40||6 120||
|||||51|260-|220|323-|443|115|175|38- 78|I-R|12 240||
|||||25|50-|75|100-|150|35|65|10- 20|RI-|2 940||
||Lava Maw|12-14||40|200-|275|301-|451|85|150|24- 44||7 880||
|||||55|300-|400|403-|603|115|185|46- 86|II-|15 760||
||1  Spitting Terrors have the ability to spit, which does magic damage.||||||||||||||
||||||||||||||||
||<b>Lightning Demons<sup>1,2</sup> - Demons</b>||||||||||||||
||**Name**|**dlvl**||**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**||||
||||||**(Hellfire)**|**(Diablo)**|||||||||
|||||18|27-|55|55-|110|30|80|8- 18|I-R|2 160||
||Red Storm|9-11||33|131-|215|166-|331|80|165|20- 40||6 320||
|||||48|208-|320|223-|443|110|200|36- 78|I-I|12 640||
|||||20|30-|60|60-|120|30|80|8- 18|R-I|2 391||
||Storm Rider|10-12||35|140-|230|181-|361|80|165|20- 40||6 782||
|||||50|220-|340|243-|483|110|200|36- 78|I-I|13 564||
|||||22|37-|67|75-|135|35|85|12- 24|R-I|2 775||
||Storm Lord|11-13||37|161-|251|226-|406|85|170|28- 52||7 550||
|||||52|248-|368|303-|543|115|205|54-102|I-I|16100||
|||||24|45-|75|90-|150|40|90|12- 28|R-I|3 177||
||Maelstorm|12-14||39|185-|275|271-|451|90|175|28- 62||8 354||
|||||54|280-|400|363-|603|120|210|54-118|I-I|16 708||
1. Lightning demons may hit with their second hand as well. Such an attack has the To Hit decreased by 20% and the damage increased by 4.

1. Lightning demons have the ability to cast Lightning.

||<a name="page95"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|||||**Created by Pedro Faria**|||||||||
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
||||||||||||||||
|<b>Balrogs<sup>1</sup> - Demons</b>|||||||||||||||
|**Name**||**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**|||||
||||||**(Hellfire)**|**(Diablo)**|||||||||
|||||20|60-|70|120-|140|60|100|12- 20|RI-|2 300||
|Slayer||10-12|35|230-|260|361-|421|110|185|28- 44||6 600|||
|||||50|340-|380|483-|563|140|220|54- 86|RI-|13 200||
|||||22|70-|80|140-|160|65|110|14- 22|RI-|2 714||
|Guardian||11-13|37|260-|290|421-|481|115|195|32- 48||7428|||
|||||52|380-|420|563-|643|145|230|62- 94|RI-|14 856||
|||||24|80-|90|160-|180|70|120|18- 24|RI-|3 252||
|Vortex Lord||12-14|39|290-|320|481-|541|120|205|40- 52||8 504|||
|||||54|420-|460|643-|723|150|240|78-102|RIR|17 008||
|||||26|90-|100|180-|200|75|130|22- 30|RI-|3 643||
|Balrog||13-15|41|320-|350|541-|601|125|215|48- 64||9 286|||
|||||56|460-|500|723-|803|155|250|94-126|RIR|18 572||
||1  Balrogs have the ability to cast Inferno.||||||||||||||
||||||||||||||||
|<b>Vipers<sup>1</sup> - Demons</b>|||||||||||||||
|**Name**||**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**|||||
||||||**(Hellfire)**|**(Diablo)**|||||||||
|||||21|50-|75|100-|150|60|90|8- 20|I--|2 725||
|Cave Viper||11-13|36|200-|275|301-|451|110|175|20- 44||7 450|||
|||||51|300-|400|403-|603|140|210|38- 86|I--|14 900||
|||||23|60-|85|120-|170|65|105|12- 24|IR-|3 139||
|Fire Drake||12-14|38|230-|305|361-|311|115|190|28- 52||8 278|||
|||||53|340-|440|483-|683|145|225|54-102|II-|16 556||
|||||25|70-|80|140-|180|70|120|15- 26|I-R|3 484||
|Gold Viper||13-14|40|260-|320|421-|541|120|205|34- 56||8 968|||
|||||55|380-|460|563-|723|150|240|66-110|I-R|17 936||
|||||27|80-|100|160-|200|75|130|18- 30|-RR|3 791||
|Azure Drake||15-15|42|290-|350|481-|601|125|215|40- 64||9 582|||
|||||57|420-|500|643-|803|155|250|78-126|IRI|19 164||

1. Vipers have the ability to do a short range charge attack with a To Hit of 500. This short ranged charge will have a base damage of 0-0 / 4-4 / 6-6, and will be in addition to their normal attack.

<b>Succubi<sup>1</sup> - Demons<sup>2</sup></b>

||**Name**|**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**||||
| :- | :- | -: | -: | -: | -: | -: | :-: | -: | :- | -: | :- | :- | :- |
|||||**(Hellfire)**|**(Diablo)**|||||||||
||||24|60-|75|120-|150|60|100|1- 20|R--|3 696||
||Succubus|12-14|39|230-|275|361-|451|110|185|6- 44||9 392||
||||54|340-|400|483-|603|140|220|10- 86|IR-|18 784||
||||26|67-|87|135-|175|65|110|1- 24|--R|4 084||
||Snow Witch|13-15|41|251-|311|406-|526|115|195|6- 52||10 168||
||||56|368-|448|543-|703|145|230|10-102|I-R|20 336||
||||28|75-|100|150-|200|75|115|1- 30|R-I|4 480||
||Hell Spawn|14-15|43|275-|350|451-|601|125|200|6- 64||10 960||
||||58|400-|500|603-|803|155|235|10-126|IIR|21 920||
||||30|70-|112|140-|225|85|120|1- 35|RIR|4 644||
||Soul Burner|15-15|45|260-|386|421-|676|135|205|6- 74||11 288||
||||60|380-|548|563-|903|165|240|10-146|III|22 576||
1. Succubi have the ability to cast Blood Stars. They can also see and fire Blood Stars at a golem regardless of the distance (assuming they have a line of sight to it) but will not be activated unless the golem is adjacent to them.

1. In Hellfire, Hell Spawns are animals, not demons.

||<a name="page96"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|||||**Created by Pedro Faria**||||||||
| :- | -: | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|||||||||||||||
|**Knights - Demons**||||||||||||||
|**Name**|**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**|||||
|||||**(Hellfire)**|**(Diablo)**|||||||||
||||24|75-|75|150-|150|75|110|15- 20|R-R|3 360||
|Black Knight|12-14|39|275-|275|451-|451|125|195|34- 44||8 720|||
|||161|54|400-|400|603-|603|155|230|66- 86|R-I|17 440||
||||26|82-|82|165-|165|75|130|18- 25|RR-|3 650||
|Doom Guard|13-15|41|296-|296|496-|496|125|215|40- 54||9 300|||
||||56|428-|428|663-|663|155|250|78-106|RI-|18 600||
|||132|28|90-|90|180-|180|80|120|20- 30|RIR|4 252||
|Steel Lord|14-15|43|320-|320|541-|541|130|205|44- 64||10 504|||
||||58|460-|460|723-|723|160|240|86-126|IIR|21 008||
||||30|100-|100|200-|200|85|130|25- 35|IRI|5 130||
|Blood Knight|13-14|45|350-|350|601-|601|135|215|54- 74||12 260|||
|||16|60|500-|500|803-|803|165|250|106-146|IRI|24 520||

1. One Black Knight is always present in Diablo’s room. Otherwise they don’t appear on level 16.
1. They only appear on level 13 as part of the Warlord of Blood quest.

<b>Mages<sup>1</sup> - Demons</b>

||**Name**|**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**||||
| :- | :- | :- | -: | -: | -: | -: | -: | -: | :- | -: | :- | :- | :- |
|||||**(Hellfire)**|**(Diablo)**|||||||||
||||25|35-|35|70-|70|0|90|8- 20|RRR|3 876||
||Counselor2|13-14|40|155-|155|211-|211|50|175|20- 44||9 752||
||||55|190-|190|283-|283|80|210|38- 86|RRR|19 504||
||||27|42-|42|85-|85|0|100|10- 24|RIR|4 478||
||Magistrate3|14-15|42|176-|176|256-|256|50|195|24- 52||10 956||
||||57|268-|268|343-|343|80|220|46-102|IIR|21 912||
||||29|60-|60|120-|120|0|110|14- 30|RRI|4 929||
||Cabalist4|15-15|44|230-|230|361-|361|50|205|32- 64||11 858||
||||59|340-|340|483-|483|80|230|62-126|IRI|23 716||
|||156|30|72-|72|145-|145|0|120|15- 25|IRI|4 968||
||Advocate5|16-16|45|266-|266|436-|436|50|215|34- 54||11 936||
||||60|388-|388|583-|583|80|240|66-106|III|23 872||
1. All mages have the ability to cast Flash.
1. Counselors have the ability to cast Firebolt.

1. Magistrates have the ability to cast Charged Bolt.

1. Cabalists have the ability to cast Lightning.

1. Advocates have the ability to cast Fireball.

1. They only appear on level 15 as part of the Arch-Bishop Lazarus quest.


### 5.2.2 Special monsters in Diablo

In the table below are listed the special monsters in Diablo. They are truly unique and are not based on any monster type. They are all treated by the game as unique monsters, except for Diablo, who is treated as a normal monster (but with some special abilities). Thus you can see some of Diablo’s stats when you have killed him a number of times just as for any other normal monster. Diablo will also for this reason drop items like a normal monster.

Like unique monsters, the special monsters have two different mlvl as well. One is used for combat and experience point award (battle) and one is used for item generation of items dropped by the unique monster (item). Both are given below.

||<a name="page97"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**||||**Created by Pedro Faria**||||||||
| :- | -: | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
||||||||||||||
|**Special Monsters in Diablo - Demons (Skeleton King is Undead)**|||||||||||||
|**Name**|**dlvl**|**mlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**|||
||||**battle**|**items**|**(Hellfire)**|**(Diablo)**|||||||
||||6|1|110|220|50|50|6- 12|-RR|710||
|The Butcher|2|36|1|380|661|100|130|16- 28||3 420|||
||||66|1|540|883|130|170|30- 54|-RR|6 840||
||||14|9|120|240|70|60|6- 16|IRR|570||
|Skeleton King1|3|44|9|410|721|120|140|16- 36||3 140|||
||||74|9|580|963|150|180|30- 70|IRR|6 280||
||||30|30|833|1 666|70|220|30- 60|IRR|31 666||
|Diablo2|16|45|30|2 549|4 999|120|3004|64-124||65 332|||
|(Diablo)||60|30|3 432|6 667|150|3404|126-246|IRR|130 664|||
||||45|45|1 666|3 333|90|220|30- 60|IRR|31 666||
|Diablo2,3|16|60|45|5 048|10 199|140|3004|64-124||65 332|||
|(Hellfire)||75|45|6 764|13 532|170|3404|126-246|IRR|130 664|||

1. In single player, the Skeleton King has the ability to raise dead skeletons. In multi player, the Skeleton King has the ability to steal life. He steal 100% life, that is, all the damage he inflicts is added to his current HP. His current HP may go above his maximum HP this way. He is also referred to as Leoric.
1. Diablo is immune to Stone Curse and has the ability to cast Apocalypse, regardless of distance, and do Knock Back attacks. Although being a demon, he take damage from Holy Bolt. He is also referred to as The Dark Lord.

1. In Hellfire, Diablo is resistant to Holy Bolt.

1. Due to a bug, base To Hit for Diablo will be 44% on nightmare and 84 on hell.


### 5.2.3 Monsters in Hellfire

Contrary to the original Diablo monsters, most Hellfire monsters do not have subtypes within a specific type. Some of the monsters do exist in two different variants though. For formatting reasons, the Hellfire monsters are grouped into monsters found in the Hive and monsters found in the Crypt. They are further grouped into monsters that have subtypes and monsters that have no subtypes.

**The Hive - monsters with subtypes, U - Undead, A - Animals, D - Demons**

||**Name**|**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**||||
| :- | :- | -: | -: | -: | -: | -: | -: | -: | :- | -: | :- | :- | :- |
||||22|15-|20|30-|40|50|85|1- 20||500||
||Stinger (A)|1- 2|37|95-|110|190-|220|100|170|6- 44||3 000||
||||52|160-|180|320-|360|130|205|10- 86|--R|6 000||
||||24|20-|25|40-|50|60|85|1- 30|--R|1 000||
||Venomtail (A)|3- 4|39|110-|125|220-|250|110|170|6- 64||4 000||
||||54|180-|200|360-|400|140|205|10-126|-RI|8 000||
||||22|10-|15|20-|30|40|80|10- 10||450||
||Psychorb1 (A)|1- 2|37|80-|95|160-|190|90|165|24- 24||2 900||
||||52|140-|160|280-|320|120|200|46- 46|-R-|5 800||
||||24|15-|20|30-|40|50|80|20- 20|-R-|1 100||
||Necromorb1 (A)|3- 4|39|95-|110|190-|220|100|165|44- 44||4 200||
||||54|160-|180|320-|360|130|200|86- 86|-IR|8 400||
||||22|30-|40|60-|80|50|50|5- 15||500||
||Arachnon (A)|1- 2|37|140-|170|280-|340|100|135|14- 34||3 000||
||||52|220-|260|440-|520|130|170|26- 66|--R|6 000||
||||24|40-|50|80-|100|60|60|8- 20|--R|1 250||
||Spider Lord2 (A)|3- 4|39|170-|200|340-|400|110|145|20- 44||4 500||
||||54|260-|300|520-|600|140|180|38- 86|-RI|9 000||
1. Psychorbs and Necromorbs have the ability to cast magical bolts, which do magic damage.
1. Spider Lords have the ability to spit, which does magic damage.

||<a name="page98"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|||||**Created by Pedro Faria**||||||||
| :- | -: | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|||||||||||||||
|**The Hive - monsters without subtypes, U - Undead, A - Animals, D - Demons**||||||||||||||
|**Name**|**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**|||||
||||23|35-|45|70-|90|65|75|4- 12|-RR|900||
|The Shredded (U)|1- 2|38|155-|185|310-|370|115|160|10- 28||3 800|||
||||53|240-|280|480-|560|145|195|22- 54|-RR|7 600||
||||22|25-|35|50-|70|50|70|10- 18||600||
|Felltwin (D)|1- 2|37|125-|155|250-|310|100|155|24- 40||3 200|||
||||52|200-|240|400-|480|130|190|46- 78|IR-|6 400||
||||23|40-|50|80-|100|60|70|16- 24||750||
|Hellboar1 (D)|1- 2|38|170-|200|340-|400|110|155|36- 52||3 500|||
||||53|260-|300|520-|600|140|190|70-102|-RR|7 000||
||||22|15-|15|30-|30|25|60|10- 25|I--|250||
|Hork Spawn2 (D)|2- 3|37|95-|95|190-|190|75|145|24- 54||2 500|||
||||52|160-|160|320-|320|105|180|46-106|I--|5 000||
||||20|15-|15|30-|30|50|90|12- 20||600||
|Lashworm (A)|3- 4|35|95-|95|190-|190|100|175|28- 44||3 200|||
||||50|160-|160|320-|320|130|210|54- 86|-R-|6 400||
||||22|30-|40|60-|80|70|75|20- 30|-I-|600||
|Torchant3 (A)|3- 4|37|140-|170|280-|340|120|160|44- 64||3 200|||
||||52|220-|260|440-|520|150|195|86-126|RIR|6 400||

1. Hellboars have the ability to Knock Back.
1. Hork Spawns never drop any items or gold.

1. Torchants have the ability to cast Fireball.

**The Crypt - monsters with subtypes, U - Undead, A - Animals, D - Demons**

||**Name**|**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**||||
| :- | :- | -: | -: | -: | -: | -: | -: | -: | :- | -: | :- | :- | :- |
||||24|30-|40|60-|80|70|100|15- 20|-I-|2 400||
||Firebat1 (A)|1- 2|39|140-|170|280-|340|120|185|34- 44||6 800||
||||54|220-|260|440-|520|150|220|66- 86|RIR|13 600||
||||29|50-|70|100-|140|80|110|30- 30|RIR|3 600||
||Hellbat2 (D)|3- 4|44|200-|260|400-|520|130|195|64- 64||9 200||
||||59|300-|380|600-|760|160|230|126-126|RII|18 400||
||||27|35-|35|70-|70|80|75|15- 20|-RR|3 000||
||Skullwing (U)|1- 2|42|155-|155|310-|310|130|160|34- 44||8 000||
||||57|240-|240|480-|480|160|195|66- 86|-RR|14 000||
||||30|120-|140|240-|280|50|100|40- 50|-II|5 000||
||Bone Demon3 (U)|3- 4|45|410-|470|820-|940|100|185|84-104||12 000||
||||60|530-|660|1 160-1 320|130|220|166-206|-II|24 000|||
||||25|40-|50|80-|100|60|100|15- 20|--R|3 000||
||Lich4 (U)|1- 2|40|170-|200|340-|400|110|185|34- 44||8 000||
||||55|260-|300|520-|600|140|220|66- 86|RRI|16 000||
||||30|90-|100|180-|200|75|120|30- 30|RRI|4 000||
||Arch Lich4 (U)|3- 4|45|320-|350|640-|700|125|205|64- 64||10 000||
||||60|460-|500|920- 1000|155|240|126-126|III|20 000|||
1. Firebats have the ability to cast Firebolt.
1. Hellbats have the ability to cast Fireball.

1. Bone Demons have the ability to cast magical bolts, which do magic damage. Bone Demons are also resistant to Holy Bolt.

1. Liches and Arch Liches have the ability to cast magical bolts, which do magic damage.

||<a name="page99"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|||||**Created by Pedro Faria**||||||||
| :- | -: | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|||||||||||||||
|**The Crypt - monsters without subtypes, U - Undead, A - Animals, D - Demons**||||||||||||||
|**Name**|**dlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**|||||
||||26|60-|120|120-|240|20|80|2- 12|--I|2 000||
|Gravedigger1 (U)|1- 1|41|230-|410|460-|820|70|165|8- 28||6 000|||
||||56|340-|580|680- 1160|100|200|12- 54|RRI|12 000|||
||||24|40-|60|80-|120|30|120|12- 25||1 800||
|Tomb Rat (A)|1- 2|39|170-|230|340-|460|80|205|28- 54||5 600|||
||||54|260-|340|520-|680|110|240|56-106|-RR|11 200||
||||27|60-|80|120-|160|70|100|18- 24|-RR|2 400||
|Devil Kin Brute|1- 2|42|230-|290|460-|580|120|185|40- 52||6 800|||
|(A)||57|340-|460|680-|840|150|220|78-102|RRR|13 600|||
||||28|80-|100|160-|200|70|90|20- 30|-RR|2 800||
|Satyr Lord (A)|1- 2|43|290-|350|580-|700|120|175|44- 64||7 600|||
||||58|420-|500|840-1 000|150|210|86-126|RII|15 200|||
||||28|100-|120|200-|240|85|100|20- 40|IRR|3 200||
|Crypt Demon (D)|2- 3|43|350-|410|700-|820|135|185|44- 84||8 400|||
||||58|500-|580|1 000-1 160|165|220|86-166|IIR|16 800|||
||||30|100-|120|200-|240|80|90|40- 50|--R|4 000||
|Biclops3 (D)|3- 4|45|350-|410|700-|820|130|175|84-104||10 000|||
||||60|500-|580|1 000-1 160|160|210|166-206|-RR|20 000|||
||||28|150-|200|300-|400|70|150|12- 18|RRR|4 000||
|Flesh Thing (D)|3- 4|43|500-|650|1 000-1 300|120|235|28- 40||10 000||||
||||58|700-|900|1 400-1 800|150|2703|54- 76|RRR|20 000|||
||||30|130-|150|260-|300|90|120|30- 35|IIR|6 000||
|Reaper (D)|3- 4|45|440-|500|880-1000|140|205|64- 74||14 000||||
||||60|620-|700|1 240-1 400|170|240|126-146|III|28 000|||

1. Gravediggers have the ability to regenerate hit points faster while digging on dead monsters.
1. Biclops have the ability to Knock Back.

1. Due to a bug, the base To Hit for Flesh Thing will be 14% on hell difficulty.


### 5.2.4 Special monsters in Hellfire

In the table below are listed the special monsters in Hellfire. They are truly unique and are not based on any monster type. They are all treated by the game as unique monsters. Like unique monsters, the special monsters have two different mlvl as well. One is used for combat and experience point award (battle) and one is used for item generation of items dropped by the unique monster (item). Both are given below. For information about the modified data for Diablo in Hellfire, see chapter 5.2.2.

**Special Monsters in Hellfire - Demons**

||**Name**|**dlvl**|**mlvl**|**mlvl**|**HP-single**|**HP-multi**|**AC**|**To Hit%**|**Damage**|**MFL**|**Base Exp**|||
| :- | :- | :- | -: | -: | -: | -: | -: | -: | -: | :- | -: | :- | :- |
||||**battle**|**items**||||||||||
||||38|27|60-|70|120-|140|80|60|20- 35|--R|2 000|
||Hork Demon1|H 3|53|27|230-|260|460-|520|130|145|44- 74||6 000|
||||68|27|340-|380|680-|760|160|180|86-146|R-I|10 000|
||||40|30||120||240|80|110|20- 30|RRI|5 000|
||The Defiler|H 4|55|30||410||820|130|195|44- 64||12 000|
||||70|30||580||1 160|160|230|86-126|RII|24 000|
||||45|40||666||1 332|125|150|40- 50|III|6 000|
||Na-Krul2|C 4|75|40||2 048||4 096|175|235|84-104||14 000|
||(by lever)||105|40||2 764||5 528|205|2703|166-206|III|28 000|
||||45|40||333||666|75|150|40- 50||6 000|
||Na-Krul2|C 4|75|40||1 049||2 098|125|235|84-104||14 000|
||(by book)||105|40||1 432||2 864|155|2703|166-206||28 000|

1. Hork Demon has the ability to spawn Hork Spawns
1. Na-Krul is immune to Stone Curse.

1. Due to a bug, the base To Hit for Na-Krul will be 14% on hell difficulty.


## 5.3 Monster properties

Apart from the data given in earlier chapters, monsters have other properties that are often shared within a monster type. This chapter will list such properties, which might be of interest in various ways. Currently the information includes monster size and how it affects selection of monsters for a specific dungeon level, attack types (for information in more detail about the behavior of the monsters according to attack type, see chapter 5.5), intelligence factor, abilities to open doors and follow target around corners, and timing information.


### 5.3.1 Monster size

Each monster type has a size associated with it. That size is used when selecting monsters for a specific level of the dungeon. Maximum total size of all monsters types on a level is 4000. Most monsters in the church, for example, have small sizes, and that is the reason why you will see many different monsters on each level. Monsters in hell and the Crypt normally have large sizes and thus you will only see two or three different monster types at once. In the tables below you can find the size of all monster types in the game. Note that golems also have a size, which is important for monster selection (see below).

**Monsters in Diablo**

||**Monster type**|**Size**|**Monster type**|**Size**|**Monster type**|**Size**||
| :- | :- | -: | :- | -: | :- | -: | :- |
||Zombies|799|Goat Men|1 030|Vipers|1 270||
||Fallen One, spear|543|Goat Men Archers|1 040|Succubi|980||
||Fallen One, sword|623|Overlords|1 130|Knights|2 120||
||Skeletons|553|Gargoyles|1 650|Mages|2 000||
||Skeleton Archers|567|Magma Demons|1 680||||
||Skeleton Captains|575|Horned Demons|1 630|Golem|386||
||Scavengers|410|Spitting Terrors|716|The Butcher|980||
||Winged Fiends|364|Lightning Demons|1 740|Skeleton King|1 010||
||The Hiddens|992|Balrogs|2 200|Diablo|2 000||
|||||||||
||**New monsters in Hellfire**|||||||
||**Monster type**|**Size**|**Monster type**|**Size**|**Monster type**|**Size**||
||The Shredded|484|Lashworm|800|Arch Lich|800||
||Felltwin|800|Torchant|800|Satyr Lord|800||
||Hellboar|800|Gravedigger|800|Crypt Demon|800||
||Hork Spawn|520|Tomb Rat|550|Biclops|800||
||Stinger|305|Devil Kin Brute|800|Flesh Thing|800||
||Venomtail|305|Firebat|550|Reaper|800||
||Psychorb|800|Hellbat|550||||
||Necromorb|800|Skullwing|1 740|Hork Demon|800||
||Arachnon|800|Bone Demon|1 740|The Defiler|800||
||Spider Lord|800|Lich|800|Na-Krul|1 200||

### 5.3.2 Monster occurrences in the dungeons

The process of selecting monsters for a dungeon level is as follows:

1. Subtract the golem’s size from the total size as it can always exist on every level.

1. If there are any special quest monsters on a dungeon level (like Snotspill, The Butcher, Lachdanan, Hork Demon and so on) subtract the size of that monster type. That monster type will also appear, if possible, on that dungeon level of course.

1. In Hellfire, if the dungeon level is level 2 or 3 of the Hive, subtract the size of the Hork Spawn. That monster type will also appear on those dungeon levels of course.

1. In Hellfire, if the dungeon level is level 4 of the Crypt, subtract the size of the Arch Lich. That monster type will also appear on that dungeon level of course.

1. In multi player, if it is the same dungeon level as the Skeleton King appears on (dlvl 3), pick a random skeleton type that can appear on that dungeon level. Subtract its size. It can now appear on that dungeon level and will be the skeleton type that appears around the Skeleton King.

1. If possible, pick a random monster type of the ones that has not yet been picked that can appear on the dungeon level in question, and whose size is equal or less than the size left. Subtract that monsters size; it can now appear on the level.

7. If there are still monsters that have a size less than the size left, go to step 6. Otherwise, end monster type selection.

7. If any monster type that was picked has a unique monster set to appear on the dlvl in question, that unique monster will always appear.

All special mini levels found in single player are created by special code and thus are not created according to the above. The same is true for dlvl 16. Which is also created by special code and does not follow the above steps. In the same way, the monsters in Arch-Bishop Lazarus’ room on dlvl 15 in multi player are not counted toward the size limit. They are considered when the game picks possible unique monsters for the dungeon level, though. That is the reason you will always see Bloodlust on dlvl 15 in multi player.

With the algorithm above and the monster size also from the tables above, it is quite easy to calculate the probability of a specific monster appearing on a dlvl. The table below has been calculated using the above information. For information about on what dlvl monsters can occur, see chapter 5.2.1 and 5.2.3.

|**dlvl 1 - Church**|**%**|**dlvl 3 - Church**|**%**|**dlvl 4 - Church**|**%**|
| :- | -: | :- | :- | :- | :- |
|Zombie|100|Ghoul|13|Rotting Carcass|24|
|Fallen One (spear)|100|Rotting Carcass|13|Black Death|24|
|Skeleton|100|Black Death|13|Devil Kin (spear)|26|
|Fallen One (sword)|100|Carver (spear)|15|Dark One (spear)|26|
|Scavenger|100|Devil Kin (spear)|15|Devil Kin (sword)|26|
|Skeleton Captain|100|Dark One (spear)|15|Dark One (sword)|26|
|**dlvl 2 - Church**|**%**|Carver (sword)|14|Burning Dead|26|
|Zombie|18|Devil Kin (sword)|14|Horror|26|
|Ghoul|18|Dark One (sword)|14|Corpse Bow|26|
|Rotting Carcass|18|Corpse Axe|24|Burning Dead Archer|26|
|Fallen One (spear)|20|Burning Dead|24|Horror Archer|26|
|Carver (spear)|20|Horror|24|Corpse Captain|26|
|Devil Kin (spear)|20|Skeleton Archer|24|Burning Dead Captain|26|
|Fallen One (sword)|20|Corpse Bow|24|Horror Captain|26|
|Carver (sword)|20|Burning Dead Archer|24|Plague Eater|31|
|Devil Kin (sword)|20|Skeleton Captain|24|Shadow Beast|31|
|Skeleton|20|Corpse Captain|24|Bone Gasher|31|
|Corpse Axe|20|Burning Dead Captain|25|Blink|34|
|Burning Dead|20|Scavenger|20|Gloom|34|
|Skeleton Archer|20|Plague Eater|20|Hidden|22|
|Corpse Bow|20|Shadow Beast|20|Flesh Clan|22|
|Skeleton Captain|20|Fiend|23|Flesh Clan Archer|22|
|Corpse Captain|20|Blink|23|||
|Scavenger|28|Hidden|11|||
|Plague Eater|28|||||
|Fiend|35|||||
|Hidden|16|||||

|<a name="page102"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**||**Created by Pedro Faria**||||||
| :- | :- | :- | :- | :- | :- | :- | :- |
|||||||||
||**dlvl 5 - Catacombs**|**%**|**dlvl 6 - Catacombs**|**%**|**dlvl 7 - Catacombs**|**%**||
||Black Death|23|Horror Archer|31|Familiar|75||
||Dark One (spear)|26|Horror Captain|31|Stalker|20||
||Dark One (sword)|26|Bone Gasher|44|Unseen|20||
||Horror|26|Gloom|47|Stone Clan|20||
||Burning Dead Archer|26|Familiar|47|Fire Clan|20||
||Horror Archer|26|Stalker|23|Night Clan|20||
||Burning Dead Captain|25|Unseen|23|Stone Clan Archer|20||
||Horror Captain|25|Flesh Clan|22|Fire Clan Archer|20||
||Shadow Beast|32|Stone Clan|22|Night Clan Archer|20||
||Bone Gasher|32|Fire Clan|22|Overlord|19||
||Blink|36|Flesh Clan Archer|22|Mud Man|19||
||Gloom|36|Stone Clan Archer|22|Winged-Demon|15||
||Hidden|21|Fire Clan Archer|22|Gargoyle|15||
||Stalker|21|Overlord|22|Horned Demon|15||
||Flesh Clan|20|Winged-Demon|17|Acid Beast|34||
||Stone Clan|20|Acid Beast|28||||
||Flesh Clan Archer|20|**dlvl 8 - Catacombs**|**%**|**dlvl 8 - Catacombs**|**%**||
||Stone Clan Archer|20|Familiar|49|Toad Demon|18||
||Overlord|20|Unseen|19|Gargoyle|15||
||Winged-Demon|16|Illusion Weaver|19|Magma Demon|14||
||||Fire Clan|18|Blood Stone|14||
||||Night Clan|18|Horned Demon|14||
||||Fire Clan Archer|18|Mud Runner|14||
||||Night Clan Archer|18|Acid Beast|33||
||||Mud Man|18|Poison Spitter|33||
|||||||||
||**dlvl 9 - Caves**|**%**|**dlvl 10 - Caves**|**%**|**dlvl 11 - Caves**|**%**||
||Illusion Weaver|16|Illusion Weaver|19|Flayed One|31||
||Night Clan|16|Toad Demon|19|Blood Claw|14||
||Night Clan Archer|16|Flayed One|19|Death Wing|14||
||Mud Man|16|Blood Claw|13|Hell Stone|14||
||Toad Demon|16|Death Wing|13|Lava Lord|14||
||Gargoyle|13|Blood Stone|13|Frost Charger|14||
||Blood Claw|13|Hell Stone|13|Obsidian Lord|14||
||Magma Demon|13|Lava Lord|13|Pit Beast|31||
||Blood Stone|13|Mud Runner|13|Red Storm|14||
||Hell Stone|13|Frost Charger|13|Storm Rider|14||
||Lava Lord|13|Obsidian Lord|13|Storm Lord|14||
||Horned Demon|13|Poison Spitter|31|Slayer|9||
||Mud Runner|13|Pit Beast|31|Guardian|9||
||Frost Charger|13|Red Storm|13|Cave Viper|19||
||Poison Spitter|56|Storm Rider|13||||
||Red Storm|13|Slayer|8||||
||||**dlvl 12 - Caves**|**%**|**dlvl 12 - Caves**|**%**||
||||Flayed One|22|Slayer|9||
||||Death Wing|13|Guardian|9||
||||Obsidian Lord|13|Vortex Lord|9||
||||Pit Beast|29|Cave Viper|18||
||||Lava Maw|29|Fire Drake|18||
||||Storm Rider|13|Succubus|23||
||||Storm Lord|13|Black Knight|9||
||||Maelstorm|13||||

|<a name="page103"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**||**Created by Pedro Faria**||||||
| :- | :- | :- | :- | :- | :- | :- | :- |
|||||||||
||**dlvl 13 - Hell**|**%**|**dlvl 14 - Hell**|**%**|<b>dlvl 15 - Hell<sup>1</sup></b>|**%**||
||Lava Maw|27|Lava Maw|26|Balrog|17||
||Storm Lord|11|Maelstorm|10|Azure Drake|33||
||Maelstorm|11|Vortex Lord|9|Snow Witch|33||
||Guardian|9|Balrog|9|Hell Spawn|33||
||Vortex Lord|9|Fire Drake|21|Soul Burner|33||
||Balrog|9|Gold Viper|21|Doom Guard|17||
||Cave Viper|21|Succubus|22|Steel Lord|17||
||Fire Drake|21|Snow Witch|22|Magistrate|17||
||Gold Viper|21|Hell Spawn|22|Cabalist|17||
||Succubus|23|Black Knight|10|**dlvl 16 - Hell**|**%**||
||Snow Witch|23|Doom Guard|10|Black Knight|100||
||Black Knight|10|Steel Lord|10|Blood Knight|100||
||Doom Guard|10|Blood Knight|10|Advocate|100||
||Steel Lord|10|Counselor|10||||
||Blood Knight|10|Magistrate|10||||
||Counselor|9||||||
|||||||||
||1  Not including Arch-Bishop Lazarus’ room in multi player.|||||||
|||||||||
||**Dlvl H1 - Hive**|**%**|**dlvl H2 - Hive**|**%**|**dlvl H3 - Hive**|**%**||
||The Shredded|80|The Shredded|70|Hork Spawn|100||
||Felltwin|80|Felltwin|65|Venomtail|100||
||Hellboar|80|Hellboar|65|Necromorb|50||
||Stinger|100|Hork Spawn|100|Spider Lord|50||
||Psychorb|80|Stinger|70|Lashworm|50||
||Arachnon|80|Psychorb|65|Torchant|50||
||||Arachnon|65||||
||**dlvl H4 - Hive**|**%**|**dlvl C1 - Crypt**|**%**|**dlvl C2 - Crypt**|**%**||
||Venomtail|100|Gravedigger|58|Tomb Rat|67||
||Necromorb|75|Tomb Rat|67|Devil Kin Brute|58||
||Spider Lord|75|Devil Kin Brute|58|Firebat|67||
||Lashworm|75|Firebat|67|Skullwing|43||
||Torchant|75|Skullwing|43|Lich|58||
||||Lich|58|Satyr Lord|58||
||||Satyr Lord|58|Crypt Demon|58||
||**dlvl C3 - Crypt**|**%**|**dlvl C4 - Crypt**|**%**||||
||Hellbat|53|Hellbat|55||||
||Bone Demon|43|Bone Demon|40||||
||Arch Lich|53|Arch Lich1|100||||
||Crypt Demon|52|Biclops|55||||
||Biclops|52|Flesh Thing|55||||
||Flesh Thing|52|Reaper|55||||
||Reaper|52||||||
1	There will always be Arch Liches on level 4 of the Crypt.


### 5.3.3 Attack types

Most monster types have their own unique way of attacking and moving. However, some of the monster types share some common attack types. The table below lists the various attack types that exist. I have used the name of the first monster type that uses that attack type. For example, skeletons and knights use the same attack type, but I have called it *skeleton* because they appear first. All monsters of a monster type share the same attack type, so I have only listed attack types for monster types. Since Hellfire does not have monster types, I have listed the attack type for each monster.

When a unique monster is present, it and its mob may have a different attack type than the normal one for that monster type. See chapter 5.4 for information about such attack type changes.

||<a name="page104"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**||**Created by Pedro Faria**||||||
| :- | :- | :- | :- | :- | :- | :- | :- | :- |
||||||||||
|**Monsters in Diablo**|||||||||
|**Monster type**||**Attack type**|**Monster type**|**Attack type**|**Monster type**|**Attack type**|||
|Zombies||Zombie|Goat Men|Goat Man|Vipers|Viper|||
|Fallen One, spear||Fallen One|Goat Men Archers|Goat Archer|Succubi|Goat Archer|||
|Fallen One, sword||Fallen One|Overlords|Overlord|Knights|Skeleton|||
|Skeletons||Skeleton|Gargoyles|Gargoyle|Mages|Mage|||
|Skeleton Archers||Skeleton Archer|Magma Demons|Magma Demon|||||
|Skeleton Captains||Skeleton|Horned Demons|Horned Demon|Golem|Golem|||
|Scavengers||Scavenger|Spitting Terrors|Spit|The Butcher|Butcher|||
|Winged Fiends||Winged Fiend|Lightning Demons|Magma Demon|Skeleton King|Skeleton King|||
|The Hiddens||Hidden|Balrogs|Balrog|Diablo|Magma Demon|||
||||||||||
|**New monsters in Hellfire**|||||||||
|**Monster type**||**Attack type**|**Monster type**|**Attack type**|**Monster type**|**Attack type**|||
|The Shredded||Skeleton|Lashworm|Skeleton|Arch Lich|Goat Archer|||
|Felltwin||Skeleton|Torchant|Goat Archer|Satyr Lord|Skeleton|||
|Hellboar||Skeleton|Gravedigger|Scavenger|Crypt Demon|Skeleton|||
|Hork Spawn||Skeleton|Tomb Rat|Skeleton|Biclops|Skeleton|||
|Stinger||Skeleton|Devil Kin Brute|Skeleton|Flesh Thing|Skeleton|||
|Venomtail||Skeleton|Firebat|Goat Archer|Reaper|Skeleton|||
|Psychorb||Goat Archer|Hellbat|Goat Archer|||||
|Necromorb||Goat Archer|Skullwing|Skeleton|Hork Demon|Skeleton|||
|Arachnon||Skeleton|Bone Demon|Magma Demon|The Defiler|Skeleton|||
|Spider Lord||Spit|Lich|Goat Archer|Na-Krul|Skeleton|||

The attack type does not only affect the actual attack but also how the monsters move around. Many monsters that share a specific attack type still cast different spells as the attack type does not in itself include spell (or arrow) cast. For information about what spell specific monsters cast, see 4.2. Others may be similar at some parts; for example, at a distance greater than Inferno range (3 squares) a Balrog will behave like a Skeleton in its movements, and it is not until it gets closer that it will start to circle the player. There are many similar features between the different attack types. Most of them are also heavily triggered by the distance to the target; that is, the behavior of the monster changes as it gets to a specific distance(s) to the target. Monsters can also gain a different attack type if they are part of a mob of a unique monster with a different attack type. The way monsters behave is not affected by difficulty level. For a more detailed explanation of how the attack types work, see chapter 5.5.

It is worth noticing that within a certain monster type the various monsters normally have an increasing ”intelligence”. A good way to see this difference is the look the various Goat Archers. Run up to them and you will see that a normal Flesh Clan Archer will not run a way immediately while a Night Clan Archer will normally run away before you even get close. Similar differences can be seen for most monster types. The table below will list the intelligence factor (Intf) within each monster type. It is basically a number between 0 and 3 (inclusive). The higher the number, the higher the intelligence of the monster. For monster types with 4 subtypes in Diablo, I have listed the four values after each other. For monsters that have no subtypes, there is only one number. Otherwise, there is no value given. For information about what intelligence factor unique monsters have, see chapter 5.4.

Presented in the table below is also the ability to open doors and to follow characters around walls. If a character disappears from the line of visibility of a player, they will normally move to the last position where they saw the character. Some monsters have the improved ability to also find the way around obstacles and follow you even further. This makes it possible for them to even follow you around a wall should you just teleport to the other side of it. If they do not have that ability, they will normally end up where you teleported from. These abilities are also presented below in the same way as the intelligence factor. A *D* means the monster can open doors and an *F* that means they will follow you.

||<a name="page105"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|||||**Created by Pedro Faria**|||||||||||||||
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
||||||||||||||||||||||
|**Monsters in Diablo**|||||||||||||||||||||
|**Monster type**|||**Intf**|||**Behavior**||**Monster type**||**Intf**|||**Behavior**||||||||
|Zombies||0|1|2|3|||||Horned Demons|0|1|2|3|DF|DF|DF|DF|||
|Fallen One, spear||0|2|2|3|||||Spitting Terrors|0|1|2|3|||||||
|Fallen One, sword||0|1|2|3|||||Lightning Demons|0|1|2|3|DF|DF|DF|DF|||
|Skeletons||0|1|2|3|||||Balrogs|0|1|2|3|DF|DF|DF|DF|||
|Skeleton Archers||0|1|2|3|||||Vipers|0|1|2|3|-F  -F  -F  -F||||||
|Skeleton Captains||0|1|2|3|--|--|--|F-|Succubi|0|1|2|3|D-  D-  DF  DF||||||
|Scavengers||0|1|2|3|||||Knights|0|0|1|1|-F  -F  -F  -F||||||
|Winged Fiends||0|1|2|3|--|--|-F|-F|Mages|0|1|2|3|D-|D-|D-|D-|||
|The Hiddens||0|1|2|3|--  -F  -F|-F||||||||||||||
|Goat Men||0|1|2|3|DF|DF|DF|DF|Golem|0||||D-||||||
|Goat Men Archers||0|1|2|3|D-  D-  DF|DF|The Butcher|3||||||||||||
|Overlords||0|1|2|3|--  -F  -F|-F|Skeleton King|3||||DF||||||||
|Gargoyles||0|1|2|3|D-  D-  D-|D-|Diablo|3||||DF||||||||
|Magma Demons||0|1|2|3|DF|DF|DF|DF||||||||||||
||||||||||||||||||||||
|**New monsters in Hellfire**|||||||||||||||||||||
|**Monster type**||**Intelligence**||**Behavior**||**Monster type**|**Intelligence**||**Behavior**||||||||||||
||||**factor**||||||||**factor**||||||||||
|The Shredded||3||||||||Firebat|3||||||||||
|Felltwin||3||||DF||||Hellbat|3||||||||||
|Hellboar||2||||-F||||Skullwing|0||||||||||
|Hork Spawn||3||||||||Bone Demon|0||||||||||
|Stinger||3||||||||Lich|3||||||||||
|Venomtail||3||||||||Arch Lich|3||||||||||
|Psychorb||3||||||||Satyr Lord|3||||||||||
|Necromorb||3||||||||Crypt Demon|3||||||||||
|Arachnon||3||||-F||||Biclops|3||||D-||||||
|Spider Lord||3||||-F||||Flesh Thing|3||||||||||
|Lashworm||3||||||||Reaper|3||||||||||
|Torchant||3|||||||||||||||||||
|Gravedigger||3||||D-||||Hork Demon|3||||||||||
|Tomb Rat||3||||||||The Defiler|3||||-F||||||
|Devil Kin Brute||3||||||||Na-Krul|3||||DF||||||

### 5.3.4 Timing information

This chapter deals with the time it takes for different monsters to do different things. The data given is explained below. In almost every case the data is the same for each monster type and thus is not given for each subtype (as it is the same). Note that for all the actions below, the time is only valid for the case when the monsters are actually walking, swinging and so on. Most monsters will, for example, make pauses occasionally when they walk, so that the average walking speed over a longer time is slower. The same applies for when monsters attack players. Sometimes they make pauses. Even monsters within a monster type may act differently as, for example, the duration of a pause is generally affected by the intelligence factor. The data below does *not* take such things into consideration. However, the actual time to do an action does not vary between different difficulty levels and subtypes of monsters. All times are given in seconds.


**Walk time**

This is the time it takes for the monster to walk one square. For a player, it takes 0.40 seconds. Due to the fact that many monsters make pauses in the walking, you can often outrun monsters with a walk speed of 0.40 seconds.


**Hit recovery time**

This is the time it takes for a monster to go through a hit recovery (stun). To stun lock a monster, you need to hit it again before it has finished its hit recovery and either hit you (hit time) or moved away (for information about entering a new location, see chapter 6.1.9). For the monster to actually go into a hit recovery, you have to hit it and do damage equal or exceeding mlvl+3 (monsters of The Hiddens go into hit recovery regardless of the damage as long as they have no resistance to the attack type). Thanks to concre+e for initial information about monsters and hit recoveries.


**Attack time**

This is the time it takes a monster to do a complete attack against you, in much the same way as the swing speed of the characters in chapter 2.2.3 works. Some monsters can actually hit you twice in one attack. Many monsters have more than one attack, in such cases, two times are given. The first attack will be the main attack, that is, the one that have data within the tables in chapter 5.2 while the second is the one explained in the foot notes. Usually the main attack will be the melee attack while the second attack is a spell attack.


**Hit time**

Within the swing this is the time it takes to reach the frame where the actual hit on a player occurs. This is of course always identical or shorter than the complete attack time. When there exist two attacks and thus two attack times, there will also be two hit times given. For Magma Demons and Lightning Demons there are actually three times given, where the first two relate to the melee attack which, as described above, can hit you twice in the same attack and the last number correspond to the spell attack.

**Diablo**

||**Monster type**|**Walk time**|**Hit recovery time**|**Attack time**|**Hit time**||
| :- | :- | :- | :-: | :- | :- | :- |
||Zombies|1\.20|0\.30|0\.60|0\.40||
||Fallen Ones with spear|0\.55|0\.55|0\.65 / 0.651|0\.35 / 0.251||
||Fallen Ones with sword|0\.60|0\.55|0\.65 / 0.751|0\.40 / 0.251||
||Skeletons|0\.40 / 0.802|0\.30|0\.65|0\.40||
||Skeleton Archers|0\.40 / 0.802|0\.25|0\.80|0\.60||
||Skeleton Captains|0\.40 / 0.802|0\.35|0\.60|0\.40||
||Scavengers|0\.40 / 0.553|0\.30|0\.60|0\.35||
||Winged Fiends|0\.65|0\.45|0\.50|0\.25||
||The Hiddens|0\.40 / 0.553|0\.40|0\.60|0\.40||
||Goat Men|0\.40|0\.30|0\.60 / 0.60|0\.40 / 0.00||
||Goat Men Archers|0\.40|0\.30|0\.80|0\.65||
||Overlords|0\.50|0\.30|0\.75 / 0.50|0\.40 / 0.00||
||Gargoyles|0\.70|0\.50|0\.70|0\.35||
||Magma Demons|0\.50|0\.35|0\.70 / 0.90|0\.20 - 0.454 / 0.705||
1. The second value is for the War Cry animation (see chapter 5.5.9 under Fallen One for more information).
1. The second value is for the fade in/out animation.

1. The second value is for the feasting upon a carcass animation.

1. Have two hits in one attack.

1. The Magma Demon actually hit at 0.65 while the other three types hit at 0.70.

**Diablo**

||**Monster type**|**Walk time**|**Hit recovery time**|**Attack time**|**Hit time**||
| :- | :- | :- | :-: | :- | :- | :- |
||Horned Demons|0\.40|0\.30|0\.70|0\.35||
||Spitting Terrors|0\.40|0\.40|0\.60 / 0.20|0\.40 / 0.00||
||Lightning Demons|0\.40|0\.20|0\.90 / 0.70|0\.25 - 0.651 / 0.40||
||Balrogs|0\.35|0\.05|0\.70 / 1.00|0\.40 / 0.15||
||Vipers|0\.55|0\.25|0\.65|0\.40||
||Succubi|0\.40|0\.35|0\.80|0\.50||
||Knights|0\.40|0\.20|0\.80|0\.40||
||Mages|0\.05 / 1.002|0\.40|1\.00|0\.40||
||The Butcher|0\.40|0\.30|0\.60|0\.40||
||Skeleton King|0\.30|0\.30|0\.80 / 0.303|0\.40 / 0.003||
||Diablo (Diablo)|0\.30|0\.30|0\.80 / 0.80|0\.20 / 0.55||
||Diablo (Hellfire)|0\.30|0\.10|0\.80 / 0.80|0\.20 / 0.55||
||Golem|0\.80 / 1.004|0\.00|0\.60|0\.35||
1. Have two hits in one attack.
1. The second value is for the fade in/out animation.

1. The second value is for the revive skeleton animation.

1. The second value is for the fade in animation.

|<a name="page107"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**||**Created by Pedro Faria**||||
| :- | :- | :- | :- | :- | :- |
|||||||
|**Hellfire - Hive**||||||
|**Monster type**|**Walk time**|**Hit recovery time**|**Attack time**|**Hit time**||
|The Shredded|0\.50|0\.25|0\.60|0\.35||
|Felltwin|0\.65|0\.55|0\.75|0\.40||
|Hellboar|0\.50|0\.30|0\.75|0\.35||
|Hork Spawn|0\.60|0\.55|0\.70|0\.40||
|Stinger|0\.50|0\.30|0\.60|0\.40||
|Venomtail|0\.50|0\.30|0\.60|0\.40||
|Psychorb|0\.65|0\.35|0\.65|0\.40||
|Necromorb|0\.65|0\.35|0\.65|0\.40||
|Arachnon|0\.50|0\.30|0\.75|0\.40||
|Spider Lord|0\.50|0\.30|0\.75 / 0.50|0\.40 / 0.40||
|Lashworm|0\.65|0\.30|0\.75|0\.40||
|Torchant|0\.60|0\.30|0\.60|0\.40||
|Hork Demon|0\.40|0\.30|0\.80 / 0.451|0\.40 / 0.401||
|The Defiler|0\.40|0\.30|0\.70 / 0.60|0\.40 / 0.40||
|1  The second value is for the|spawning Hell Spawn animation.|||||
|||||||
|**Hellfire - Crypt**||||||
|**Monster type**|**Walk time**|**Hit recovery time**|**Attack time**|**Hit time**||
|Gravedigger|1\.20 / 0.801|0\.30|0\.60|0\.30||
|Tomb Rat|0\.40|0\.30|0\.60|0\.40||
|Devil Kin Brute|0\.40|0\.40|0\.55|0\.30||
|Firebat|0\.80|0\.30|0\.70|0\.40||
|Hellbat|0\.80|0\.30|0\.70|0\.40||
|Skullwing|0\.40|0\.30|1\.00|0\.35||
|Bone Demon|0\.40|0\.30|1\.00 / 0.80|0\.40 / 0.60||
|Lich|0\.50|0\.35|0\.50|0\.40||
|Arch Lich|0\.50|0\.35|0\.50|0\.40||
|Satyr Lord|0\.65|0\.45|0\.70|0\.40||
|Crypt Demon|0\.90|0\.40|0\.60|0\.40||
|Biclops|0\.55|0\.30|0\.80|0\.40||
|Flesh Thing|1\.20|0\.30|0\.75|0\.40||
|Reaper|0\.50|0\.30|0\.70|0\.40||
|Na-Krul|0\.30|0\.15|0\.80 / 0.80|0\.35 / 0.25||
1	The second value is for the digging upon a carcass animation.


## 5.4 Unique monsters

Unique monsters always appear on a specific dlvl and are based on one of the normal monsters. They can also have a special ability (attack type) not normally available to that monster. Often, especially on the earlier levels, they have a group of normal monsters (a mob in the tables) around them. The monsters of that mob also have the same special ability as their boss and have their HP doubled (after any modification for difficulty level). Any stat not given in the unique monster tables is identical to that of the monster it is based on. Generally, any information given in chapter 5.1 also applies to unique monsters unless stated otherwise below.

I have tried to fit in all the data for each unique monster into the tables below, this means that it can at a first glance seem complicated and confusing but the alternative would have been to split up the data into several tables.


**Type**

This is the monster the unique monster is based on. Unless otherwise changed, it has all the stats and abilities of the monster it is based on.


**Attack type**

This will list the attack type of the unique monster (and its followers). It will be in italic if it differ from the normal attack type for that monster For information about attack types, see chapter 5.3.3. Most unique monsters that appear in quests have their own special attack type. It is normally related to the attack type the monster normally has but may have some differences. They are noted as *special* in the tables below.


**Attack type and Intelligence factor**

This list the intelligence factor for the unique monster (and its followers). For information about the intelligence factor, see chapter 5.3.3.


**Mob**

If the unique monster has a mob of normal monsters around it, it is listed here. Otherwise the unique monster will be alone.


**Dungeon level**

This is the dlvl the unique monster will appear on. It cannot appear on any other dlvl, and it will only (and always) appear if the monster it is based on is present on the dlvl.


**Monster level**

Note that unique monsters have two different mlvl. One is used for combat and experience point award (battle), and one is used for item generation of items dropped by the unique monster (item). The mlvl used for combat and experience points follow one of the following two formulas:

mlvlunique = 2×dlvl

mlvlunique = mlvlnormal + 5

The lower formula is only used for certain unique monsters in quests. It should be apparent from the table which of the two formulas was used. For item generation the mlvl of a unique monsters is equal to the mlvl of the monster it is based on. Both mlvl are listed in the tables below to avoid confusion.

Most unique monsters receive the normal +15/+30 addition to their mlvl on nightmare and hell difficulty. However, some special monsters receive this bonus twice. Apart from some of the special monsters (see chapter 5.2.2 and 5.2.4), this is also true for Arch-Bishop Lazarus, Blackjade and Red Vex).


**Hit points**

The HP in the tables below are for Diablo. For Hellfire, you should add 49 for nightmare and 97 for hell difficulty (99 and 197 in multi player). All unique monsters have more Hit Points than normal monsters of their type. The number of Hit Points for unique monsters is always the same and never varies within a range like for normal monsters.


**Damage**

All unique monsters do more damage than normal monsters. The listed value shows the range of the damage.


**Resistance and immunity**

Unlike normal monsters, unique monsters have the same resistances and immunities on all three difficulty levels. For an explanation on how resistance and immunity is shown, see chapter 5.1.


**Experience points**

Experience points given for killing a unique monster follows that of normal monsters (see chapter 5.1). The base experience for a unique monster is twice that of a normal monster. However, there seems to be a bug with experience points for unique monsters. The calculations for nightmare and hell difficulty increase and seem to be applied twice. This will in most cases mean the experience points will overflow and wrap around (maximum base experience points is 65535). For that reason, I have not given any base experience points for unique monsters.


**Armor Class and To Hit**

Generally, a unique monster has the same AC and To Hit as a normal monster. There are exceptions, though, where the unique monster can get a different AC *or* a different To Hit (but never both). Due to a bug, this changed AC and To Hit is not updated for difficulty level, and will thus be the same on all difficulties.

If the monster has any AC or To Hit that differs from the base monster, it will be noted in a note under the table.

**Zombies**

||**Name**|**Type**|**Attack type**|**Intf**|**Mob**|**dlvl**|**mlvl**|**mlvl**|**HP**|**Damage**|**MFL**||||
| :- | :- | :- | :- | :-: | :-: | -: | :-: | :-: | -: | -: | :- | :- | :- | :- |
||||||||**battle**|**items**|||||||
||||||||4|1|85|4|-|12|||
||Rotfeast the Hungry|Zombie|*Skeleton*|3|Yes|2|19|1|256|12|-|28|I--||
||||||||34|1|343|22|-|54|||
||||||||4|1|133|4|-|8|||
||Soulpus|Zombie|Zombie|0||2|19|1|400|12|-|20|-RR||
||||||||34|1|535|22|-|38|||
||||||||6|2|102|9|-|24|||
||Rotcarnage1|Ghoul|Zombie|3|Yes|3|21|2|307|22|-|52|I-R||
||||||||36|2|411|42|- 102||||
||||||||6|4|156|15|-|30|||
||Goretongue|Rotting Carcass|*Skeleton*|1||3|21|4|469|34|-|64|I--||
||||||||36|4|627|66|- 126||||
||1  Has an AC of|45 on all difficulty levels.|||||||||||||
||||||||||||||||
||**Fallen Ones with spear**||||||||||||||
||**Name**|**Type**|**Attack type**|**Intf**|**Mob**|**dlvl**|**mlvl**|**mlvl**|**HP**|**Damage**|**MFL**||||
||||||||**battle**|**items**|||||||
||||||||4|1|51|6|-|18|||
||Pukerat the Unclean|Fallen One, spear|Fallen One|3||2|19|1|154|16|-|40|-R-||
||||||||34|1|207|30|-|78|||
||||||||6|5|178|9|-|21|||
||Bongo|Devil Kin, spear|Fallen One|3|Yes|3|21|5|535|22|-|46|||
||||||||36|5|715|42|-|90|||
||||||||8|7|220|10|-|18|||
||Snotspill1|Dark One, spear|*Special*|3||4|23|7|661|24|-|40|--R||
||||||||38|7|883|46|-|78|||
||1  Only appears|in a quest in single player.|||||||||||||
||||||||||||||||
||**Fallen Ones with sword**||||||||||||||
||**Name**|**Type**|**Attack type**|**Intf**|**Mob**|**dlvl**|**mlvl**|**mlvl**|**HP**|**Damage**|**MFL**||||
||||||||**battle**|**items**|||||||
||||||||4|1|77|1|-|5|||
||Bladeskin the Slasher1|Fallen One, sword|Fallen One|0||2|19|1|232|6|-|14|-R-||
||||||||34|1|311|10|-|26|||
||||||||6|3|66|6|-|16|||
||Gutshank the Quick|Carver, sword|*Winged Fiend*|2|Yes|3|21|3|199|16|-|36|-R-||
||||||||36|3|264|30|-|70|||
||||||||10|7|270|12|-|25|||
||Shadowcrow2|Dark One, sword|*Hidden*|2|Yes|5|25|7|811|28|-|54|||
||||||||40|7|1 083|54|- 106||||
1. Has an AC of 45 on all difficulty levels.
1. Has the ability to disappear, like The Hiddens.

||<a name="page110"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|||||**Created by Pedro Faria**|||||||||
| :- | :- | :- | :- | :- | :- | -: | :- | :- | :- | :- | :- | :- | :- | :- |
||||||||||||||||
|**Skeletons - Undead**|||||||||||||||
|**Name**|**Type**|**Attack type**|**Intf**|**Mob**|**dlvl**|**mlvl**|**mlvl**|**HP**|**Damage**||**MFL**||||
||||||||**battle**|**items**|||||||
||||||||4|1|54|6|-|15|||
|Boneripper|Skeleton|*Winged Fiend*|0|Yes|2|19|1|163|16|-|34||II-||
||||0||||34|1|219|30|-|66|||
||||||||4|2|91|4|-|10|||
|Bonehead Keenaxe1|Corpse Axe|Skeleton|2|Yes|2|19|2|274|12|-|24||I--||
||||||||34|2|367|22|-|46|||
||||||||8|4|75|21|-|24|||
|Madeye the Dead2|Burning Dead|*Winged Fiend*|0|Yes|4|23|4|226|46|-|52||II-||
||||||||38|4|303|90|- 102||||
1. Has a base To Hit of 100 on all difficulty levels.
1. Has an AC of 30 on all difficulty levels.

**Skeleton Archers**

||**Name**|**Type**|**Attack type**|**Intf**|**Mob**|**dlvl**|**mlvl**|**mlvl**|**HP**|**Damage**|**MFL**||||
| :- | :- | :- | :- | :-: | :-: | -: | :-: | :-: | -: | -: | :- | :- | :- | :- |
||||||||**battle**|**items**|||||||
||||||||4|3|49|6|-|9|||
||Deadeye|Skeleton Archer|*Goat Archer*|0||2|19|3|148|16|-|22|IR-||
||||||||34|3|199|30|-|42|||
||||||||6|5|125|6|-|10|||
||Skullfire|Corpse Bow|*Goat Archer*|1||3|21|5|376|16|-|24|-I-||
||||||||36|5|503|30|-|46|||
||||||||8|7|120|6|-|16|||
||Blackash the Burning|Burning Dead Arch.|*Goat Archer*|0|Yes|4|23|7|361|16|-|36|II-||
||||||||38|7|483|30|-|70|||
||||||||||||||||
||**Skeleton Captains**||||||||||||||
||**Name**|**Type**|**Attack type**|**Intf**|**Mob**|**dlvl**|**mlvl**|**mlvl**|**HP**|**Damage**|**MFL**||||
||||||||**battle**|**items**|||||||
||||||||6|6|108|12|-|20|||
||Brokenhead Bangshield|Corpse Captain|Skeleton|3|Yes|3|21|6|325|28|-|44|I-R||
||||||||36|6|432|54|-|86|||
||||||||10|10|300|18|-|26|||
||Shadowdrinker1|Horror Captain|*Hidden*|1|Yes|5|25|10|901|40|-|56|IRR||
||||||||40|10|1 203|78|- 110||||
||1  Has the ability|to disappear, like The|Hiddens. Has an AC|of 45 on|all difficulty levels.||||||||||
||||||||||||||||
||**Scavengers**||||||||||||||
||**Name**|**Type**|**Attack type**|**Intf**|**Mob**|**dlvl**|**mlvl**|**mlvl**|**HP**|**Damage**|**MFL**||||
||||||||**battle**|**items**|||||||
||||||||4|2|60|3|-|20|||
||Shadowbite|Scavenger|*Skeleton*|3|Yes|2|19|2|181|10|-|44|-I-||
||||||||36|2|243|18|-|86|||
||||||||6|4|120|10|-|18|||
||El Chupacabras|Plague Eater|*Goat Man*|0|Yes|3|21|4|361|24|-|40|-R-||
||||||||36|4|483|46|-|78|||
||||||||8|6|150|16|-|20|||
||Pulsecrawler1|Shadow Beast|Scavenger|0|Yes|4|23|6|451|36|-|44|-IR||
||||||||38|6|603|70|-|86|||
||||||||8|8|180|18|-|25|||
||Spineeater|Bone Gasher|Scavenger|1|Yes|4|23|8|541|40|-|54|--I||
||||||||38|8|723|78|- 106||||
1	Has an AC of 45 on all difficulty levels.

||<a name="page111"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|||||**Created by Pedro Faria**|||||||||
| :- | :- | :- | :- | :- | :- | -: | :- | :- | :- | :- | :- | :- | :- | :- |
||||||||||||||||
|**Winged Fiends**|||||||||||||||
|**Name**|**Type**|**Attack type**|**Intf**|**Mob**|**dlvl**|**mlvl**|**mlvl**|**HP**|**Damage**||**MFL**||||
||||||||**battle**|**items**|||||||
||||||||8|7|135|9|-|27|||
|Moonbender|Blink|Winged Fiend|0|Yes|4|23|7|406|22|-|58||-I-||
||||||||38|7|543|42|- 114||||
||||||||10|7|135|9|-|22|||
|Wrathraven|Blink|Winged Fiend|2|Yes|5|25|7|406|22|-|48||-I-||
||||||||40|7|543|42|-|94|||
||||||||10|9|246|12|-|28|||
|Foulwing1|Gloom|*Horned Demon*|3|Yes|5|25|9|738|28|-|60||-R-||
||||||||40|9|987|54|- 118||||
1. Due to having the Horned Demon attack type, Foulwing and his mob will do full charged attacks with both damage (0-0 / 4-4 / 6-6) and putting the player into hit recovery. For more information, see chapter 6.1.7.

**The Hiddens**

|**Name**||**Type**||**Attack type**||**Intf**||**Mob**|**dlvl**||**mlvl**||**mlvl**||**HP**||**Damage**|**MFL**|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :-: | :- | :-: | :- | :- | :- | :- | :- |
||||||||||||**battle**||**items**||||||

|||||||6|5|117|6|-|18||
| :- | :- | :- | :- | :- | :- | -: | -: | -: | -: | -: | -: | :- |
|Warpskull|Hidden|Hidden|2|Yes|3|21|5|352|16|-|40|-RR|
|||||||36|5|471|30|-|78||
||||||||||||||
|**Goat Men**|||||||||||||
|**Name**|**Type**|**Attack type**|**Intf**|**Mob**|**dlvl**|**mlvl**|**mlvl**|**HP**|**Damage**|**MFL**|||
|||||||**battle**|**items**||||||
|||||||8|7|120|6|-|16||
|Gharbad the Weak1|Flesh Clan|*Special*|3||4|23|7|361|16|-|36|--I|
|||||||38|7|483|30|-|70||
|||||||12|10|276|12|-|24||
|Deathshade Fleshmaul2|Stone Clan|*Horned Demon*|0||6|27|10|829|28|-|52|IR-|
|||||||42|10|1 107|54|- 102|||
|||||||12|12|315|24|-|34||
|Bloodgutter|Fire Clan|*Winged Fiend*|1|Yes|6|27|12|946|52|-|72|-I-|
|||||||42|12|1 263|102|- 142|||
|||||||14|14|250|20|-|28||
|Blighthorn Steelmace3|Night Clan|*Horned Demon*|0|Yes|7|29|14|751|44|-|60|--R|
|||||||44|14|1 003|86|- 118|||
1. Only appears in quests in single player.
1. Due to having the Horned Demon attack type, Deathshade and its mobs will do full charged attacks with both damage (0-0 / 4-4 / 6-6) and putting the player into hit recovery. For more information, see chapter 6.1.7. Has an AC of 46 on all difficulty levels.

1. Due to having the Horned Demon attack type, Blighthorn and its mobs will do full charged attacks with both damage (30-30 / 64-64 / 126-126) and putting the player into hit recovery. For more information, see chapter 6.1.7. Has an AC of 45 on all difficulty levels.

**Goat Men Archers**

||**Name**|**Type**|**Attack type**|**Intf**|**Mob**|**dlvl**|**mlvl**|**mlvl**|**HP**|**Damage**|**MFL**||||
| :- | :- | :- | :- | :-: | :-: | -: | :-: | -: | -: | -: | :- | :- | :- | :- |
||||||||**battle**|**items**|||||||
||||||||10|8|207|3|-|16|||
||Bloodskin Darkbow1|Flesh Clan Archer|Goat Archer|0|Yes|5|25|8|622|10|-|36|-RR||
||||||||40|8|831|18|-|70|||
||||||||14|12|321|13|-|21|||
||Blightfire2|Fire Clan Archer|Goat Archer|2|Yes|7|29|12|964|30|-|46|-I-||
||||||||44|12|1 287|58|-|90|||
||||||||14|14|303|15|-|28|||
||Gorestone3|Night Clan Archer|Goat Archer|1|Yes|7|29|14|910|34|-|60|--R||
||||||||44|14|1 215|66|- 118||||
1. Has an AC of 55 on all difficulty levels.
1. Has the ability to fire Blood Stars instead of arrows, like Succubi.

1. Has a base To Hit of 70 on all difficulty levels.

||<a name="page112"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|||||**Created by Pedro Faria**|||||||||||
| :- | :- | :- | :- | :- | :- | -: | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
||||||||||||||||||
|**Overlords**|||||||||||||||||
|**Name**||**Type**|**Attack type**|**Intf**|**Mob**|**dlvl**|**mlvl**|**mlvl**|**HP**|**Damage**||**MFL**|||||
||||||||||**battle**|**items**|||||||
||||||||||12|10|210|16|-|23|||
|Bilefroth the Pit Master||Overlord|*Winged Fiend*|1|Yes|6|27|10|631|36|-|50||IIR|||
||||||||||42|10|843|70|-|68|||
||||||||||16|14|315|24|-|35|||
|Baron Sludge1||Mud Man|*Hidden*|3|Yes|8|31|14|946|52|-|74||IRR|||
||||||||||46|14|1 263|102|- 146||||
||||||||||18|16|483|25|-|30|||
|Oozedrool||Toad Demon|Overlord|3|Yes|9|33|16|1 450|54|-|64||--R|||
||||||||||48|16|1 935|106|- 126||||
||1  Has the ability|to disappear, like The|Hiddens. Has an AC|of 75 on|all difficulty levels.||||||||||||
||||||||||||||||||
|**Gargoyles**|||||||||||||||||
|**Name**||**Type**|**Attack type**|**Intf**|**Mob**|**dlvl**|**mlvl**|**mlvl**|**HP**|**Damage**||**MFL**|||||
||||||||||**battle**|**items**|||||||
||||||||||14|13|342|18|-|26|||
|Nightwing the Cold||Gargoyle|*Winged Fiend*|1|Yes|7|29|13|1 027|40|-|56||I-R|||
||||||||||44|13|1 371|78|- 114||||
||||||||||20|19|405|15|-|35|||
|Goldblight of the Flame1||Blood Claw|Gargoyle|0|Yes|10|35|19|1 216|34|-|74||II-|||
||||||||||50|19|1 623|66|- 146||||
||||||||||24|23|525|20|-|40|||
|Viletouch||Death Wing|Gargoyle|3|Yes|12|39|23|1 576|44|-|84||--I|||
||||||||||54|23|2 103|86|- 166||||
||1  Has an AC of 80 on all difficulty levels.||||||||||||||||
||||||||||||||||||
|**Magma Demons**|||||||||||||||||
|**Name**||**Type**|**Attack type**|**Intf**|**Mob**|**dlvl**|**mlvl**|**mlvl**|**HP**|**Damage**||**MFL**|||||
||||||||||**battle**|**items**|||||||
||||||||||16|13|303|18|-|22|||
|Firewound the Grim||Magma Demon|Magma Demon|0|Yes|8|31|13|910|40|-|48||IR-|||
||||||||||46|13|1 215|78|-|94|||
||||||||||||||||||
|**Horned Demons**|||||||||||||||||
|**Name**||**Type**|**Attack type**|**Intf**|**Mob**|**dlvl**|**mlvl**|**mlvl**|**HP**|**Damage**||**MFL**|||||
||||||||||**battle**|**items**|||||||
||||||||||18|15|351|25|-|34|||
|Breakspine||Mud Runner|Horned Demon|0|Yes|9|33|15|1 054|54|-|72||-R-|||
||||||||||48|15|1 407|106|- 142||||
||||||||||20|19|525|20|-|40|||
|Blackstorm1||Obsidian Lord|Horned Demon|3|Yes|10|35|19|1 576|44|-|84||I-I|||
||||||||||50|19|2 103|86|- 166||||
||||||||||22|17|477|25|-|30|||
|Bluehorn1||Frost Charger|Horned Demon|1|Yes|11|37|17|1 432|54|-|64||IR-|||
||||||||||53|17|1 911|106|- 126||||
1	Has an AC of 90 on all difficulty levels.

||<a name="page113"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|||||**Created by Pedro Faria**||||||||||
| :- | :- | :- | :- | :- | :- | -: | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|||||||||||||||||
|**Acid Beasts**||||||||||||||||
|**Name**|**Type**||**Attack type**|**Intf**|**Mob**|**dlvl**|**mlvl**|**mlvl**|**HP**|**Damage**||**MFL**||||
|||||||||**battle**|**items**|||||||
|||||||||12|11|303|12|-|32|||
|Deathspit1|Acid Beast||*Fast Spit*|0|Yes|6|27|11|910|28|-|68||-RR||
|||||||||42|11|1 215|54- 134|||||
|||||||||16|15|240|12|-|20|||
|Chaoshowler1|Poison Spitter||*Fast Spit*|0|Yes|8|31|15|721|28|-|44||||
|||||||||46|15|963|54|-|86|||
|||||||||20|15|450|20|-|30|||
|Plaguewrath1|Poison Spitter||*Fast Spit*|2|Yes|10|35|15|1 351|44|-|64||IR-||
|||||||||50|15|1 803|86|- 126||||
||1  Never attacks|in melee but always uses|fast spit instead.|||||||||||||
|||||||||||||||||
|**Lightning Demons**||||||||||||||||
|**Name**|**Type**|**Attack type**|**Intf**|**Mob**|**dlvl**|**mlvl**|**mlvl**|**HP**|**Damage**||**MFL**|||||
|||||||||**battle**|**items**|||||||
|||||||||18|18|411|25|-|36|||
|Brokenstorm|Red Storm|Magma Demon|2|Yes|9|33|18|1 234|54|-|76||--I|||
|||||||||48|18|1 647|106|- 150||||
|||||||||20|20|501|20|-|35|||
|The Flayer|Storm Rider|Magma Demon|1|Yes|10|35|20|1 504|44|-|74||RRI|||
|||||||||50|20|2 007|86|- 146||||
|||||||||26|24|612|1|-|60|||
|Doomcloud|Maelstorm|Magma Demon|1||13|41|24|1 837|6|- 124||-RI||||
|||||||||56|24|2 451|10|- 246||||
|||||||||||||||||
|**Balrogs**||||||||||||||||
|**Name**|**Type**||**Attack type**|**Intf**|**Mob**|**dlvl**|**mlvl**|**mlvl**|**HP**|**Damage**||**MFL**||||
|||||||||**battle**|**items**|||||||
|||||||||24|24|711|35|-|40|||
|Windspawn1|Vortex Lord||*Skeleton*|1|Yes|12|39|24|2 134|74|-|84||II-||
|||||||||54|24|2 847|146|- 166||||
|||||||||26|24|771|20|-|55|||
|Gorefeast1|Vortex Lord||*Skeleton*|3||13|41|24|2 314|44|- 114||-R-|||
|||||||||56|24|3 087|86|- 226||||
|||||||||26|26|750|25|-|40|||
|Blackskull1|Balrog||*Skeleton*|3|Yes|13|41|26|2 251|54|-|84||I-R||
|||||||||56|26|3 003|106|- 166||||
||1  Never casts|Inferno but always attacks|by melee instead.|||||||||||||
|||||||||||||||||
|**Vipers**||||||||||||||||
|**Name**|**Type**||**Attack type**|**Intf**|**Mob**|**dlvl**|**mlvl**|**mlvl**|**HP**|**Damage**||**MFL**||||
|||||||||**battle**|**items**|||||||
|||||||||22|21|444|15|-|32|||
|Fangspeir1|Cave Viper||*Skeleton*|1|Yes|11|37|21|1 333|34|-|68||-I-||
|||||||||52|21|1 779|66|- 134||||
|||||||||24|23|570|25|-|35|||
|Viperflame1|Fire Drake||*Skeleton*|1|Yes|12|39|23|1 711|54|-|74||-IR||
|||||||||54|23|2 283|106|- 146||||
|||||||||28|25|681|15|-|50|||
|Fangskin1|Gold Viper||*Skeleton*|2|Yes|14|43|25|2 044|34|- 104||I-R|||
|||||||||58|25|2 727|66|- 206||||
1	Will never do the short range Viper charge.

||<a name="page114"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|||||**Created by Pedro Faria**|||||||||
| :- | :- | :- | :- | :- | :- | -: | :- | :- | :- | :- | :- | :- | :- | :- |
||||||||||||||||
|**Succubi**|||||||||||||||
|**Name**|**Type**|**Attack type**|**Intf**|**Mob**|**dlvl**|**mlvl**|**mlvl**|**HP**|**Damage**||**MFL**||||
||||||||**battle**|**items**|||||||
||||||||24|24|444|10|-|20|||
|Witchfire the Unholy|Succubus|Goat Archer|3|Yes|12|39|24|1 333|24|-|44||IIR||
||||||||54|24|1 779|46|-|86|||
||||||||26|26|310|30|-|40|||
|Witchmoon|Snow Witch|Goat Archer|3||13|41|26|931|64|-|84||--R||
||||||||56|26|1 243|126|- 166||||
||||||||28|28|726|30|-|50|||
|Stareye the Witch|Hell Spawn|Goat Archer|2||14|43|28|2 179|64|- 104||-I-|||
||||||||58|28|2 907|126|- 206||||
||||||||30|28|825|20|-|55|||
|Bloodlust1|Hell Spawn|Goat Archer|1||15|45|28|2 476|44|- 114||I-I|||
||||||||60|28|3 303|86|- 223||||
||||||||33|28|400|30|-|50|||
|Blackjade2|Hell Spawn|*Special*|3||15|63|28|1 201|64|- 104||I-R|||
||||||||93|28|1 603|126|- 206||||
||||||||33|28|400|30|-|50|||
|Red Vex2|Hell Spawn|*Special*|3||15|63|28|1 201|64|- 104||IR-|||
||||||||93|28|1 603|126|- 206||||
1. Always appears in every multi player game.
1. Always appears in Arch-Bishop Lazarus’ room.

**Knights**

||**Name**|**Type**|**Attack type**|**Intf**|**Mob**|**dlvl**|**mlvl**|**mlvl**|**HP**|**Damage**|**MFL**||||
| :- | :- | :- | :- | :-: | :-: | :-: | :-: | :-: | -: | -: | :- | :- | :- | :- |
||||||||**battle**|**items**|||||||
||||||||24|24|525|25|-|25|||
||Lionskull the Bent|Black Knight|Skeleton|2|Yes|12|39|24|1 576|54|-|54|III||
||||||||54|24|2 103|106|- 106||||
||||||||26|26|400|1|-|60|||
||Rustweaver|Doom Guard|Skeleton|3||13|41|26|1 201|6|- 124|III|||
||||||||56|26|1 603|10|- 246||||
||||||||26|28|850|35|-|50|||
||Warlord of Blood1|Steel Lord|*Special*|3||13|41|28|2 551|74|- 104|III|||
||||||||56|28|3 403|146|- 206||||
||||||||28|26|672|30|-|50|||
||Graywar the Slayer|Doom Guard|Skeleton|1||14|43|26|2 017|64|- 104|--R|||
||||||||58|26|2 691|126|- 206||||
||||||||28|28|831|40|-|50|||
||Steelskull the Hunter|Steel Lord|Skeleton|3||14|43|28|2 494|84|- 104|--R|||
||||||||58|28|3 327|166|- 206||||
||||||||28|30|500|0|-|0|||
||Lachdanan1,2|Blood Knight|*Special*|3||14|43|30|1 501|4|-|4|||
||||||||58|30|2 003|6|-|6|||
||||||||32|30|1 050|20|-|60|||
||Sir Gorash3|Blood Knight|Skeleton|1||16|47|30|3 151|44|- 124||||
||||||||62|30|4 203|86|- 246||||
1. Only appears in a quest in single player.
1. His stats are actually uninteresting as you will never fight against him.

1. Always appear in every game.

||<a name="page115"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|||||**Created by Pedro Faria**|||||||||
| :- | :- | :- | :- | :- | :- | -: | :- | :- | :- | :- | :- | :- | :- | :- |
||||||||||||||||
|**Mages**|||||||||||||||
|**Name**|**Type**|**Attack type**|**Intf**|**Mob**|**dlvl**|**mlvl**|**mlvl**|**HP**|**Damage**||**MFL**||||
||||||||**battle**|**items**|||||||
||||||||16|25|360|16|-|40|||
|Zhar the Mad1|Counselor|*Special*|3||8|31|25|1 081|36|-|84||IRR||
||||||||46|25|1 440|70|- 166||||
||||||||28|27|540|30|-|40|||
|Dreadjudge|Magistrate|Mage|1|Yes|14|43|27|1 621|64|-|84||IRR||
||||||||58|27|2 163|126|- 166||||
||||||||30|29|850|25|-|40|||
|The Vizier|Cabalist|Mage|2|Yes|15|45|29|2 551|54|-|84||-I-||
||||||||60|29|3 403|106|- 166||||
||||||||35|30|600|30|-|50|||
|Arch-Bishop Lazarus2|Advocate|*Special*|3||15|65|30|1 801|64|- 104||IRR|||
||||||||95|30|2 403|126|- 206||||
1. Has the ability to fire Fireballs instead of Firebolts, like Advocates. Only appears in a quest in single player.
1. Always appears in every game.


## 5.5 Monster AI

In this chapter, a more detailed explanation of the monster’s AI, artificial intelligence, is given. That is, it will explain how the monster decide what to do. It will also explain in more detail how monsters act in general. Basically one can say that a monster can do 3 different things; move in some way, attack in some way or stand still in some way.


### 5.5.1 General information

Just like a player, a monster will always have a specific action which it will be doing. Also, just as players, it must finish the current action before it can chose to do a new action. Some outside events may sometimes force a monster into a new specific action. Such events be the monster being hit and set into hit recover, a Fallen One retreating due to having a companion killed.

As explained in chapter 6, monsters, players and other things in the game are updated in a specific order and once every 0.05 seconds. During the update of each monster it will typically continue with the monster’s current action and if it during the update reaches the end of that action it terminates it.

When a monster terminates an action, it will be set into *stand* mode. Stand mode is basically the monster doing nothing (note *delaying* is basically standing but for a predetermined time). The first thing that happens when a monster is set to *stand* mode is that it will check for a target. Thus, a monster always has a target, even if it is not activated and no enemy is in sight. For a description of target selection, see chapter 5.5.6. When a monster is in *stand* mode it will check for a new action by following a special script specific for the attack type the monster has. Note that a unique monster, and its mob if any, may have its attack type changed, see chapter 5.4, it will then follow the script of the new attack type. For a list of attack type for each monster, see chapter 5.3.3. The script may either end up in the monster being set into a new action type, or remaining in *stand* mode.

At any time, the game, for each monster, thus has complete knowledge of what target the monster has. It also knows where the target is and will as appropriate, calculate the distance to the target. It also always know what action the monster performed previous to being set to *stand* mode. In addition, while in stand mode, a special counter will keep track of how long the monster have been in *stand* mode. All this may often be important when going through the various scripts to decide the next action.

Within the scripts, some common tasks are very often performed either at the start or at the end. One of them is calculate the distance to its target. The game will also check the direction in which the target is located. This is usually used to determine in what direction the monster will walk. This chapter will *not* deal with path algorithms used, or explain how a monster walk. Many monsters will walk towards the target in the closest possible way, others will (at times depending on the distance to the target) instead walk around the target and so on. This chapter will generally just tell that the monster will chose to *walk* as its next action. Usually at the end of the script, if the monster is still in *stand* mode, it will turn around towards it target if necessary.


### 5.5.2 Activating monsters

All monsters on a new level starts in a non active state (monsters with the Hidden attack type are an exception as they are always active, see chapter 5.5.9 under the *Hidden* subsection). As soon as a monster is within a players light radius and the view between the monster and the player is not obstructed by walls, the monster will be activated. While not activated, most monsters will not act although some exceptions exists, see chapter 5.5.7. Examples of such exceptions are archers and Succubi still being able to fire at golems or if a monster is attacked in any way. When a monster leaves the light radius of a player, it will continue to act for 12.75 seconds until it is set into non active status again unless it during that time, again enter the light radius of a player or is ”activated” again. Some monsters with the capability of following players outside their current view will try to walk around possible obstacles to get to the former target when it get out of the light radius. See chapter 5.3.3 for more information about which monsters have this capability.


### 5.5.3 About walking

There are several different ways monsters walk in the game. The exact nature of how monster walking is done will not always be described in detail. Some general comments is needed though. Below are given very general description of some common walk behavior. They are given as a general information. Changes and diversions may exists. Also, if while walking the path is blocked, monsters may behave slightly different. Some times it will try alternative paths and other times abort its walk and reconsider its action. Some monsters have very specific walk behavior and those will be described within the actual AI script.

Walking towards target:	This means the monster will generally walk towards the target in the closes

possible way. It will typically walk around smaller obstacles. Example of this walk type are The Hiddens and Skeletons.

Walking towards last seen position: Same as walking towards target, but the game will unless the target is within line of sight, walk towards the location where the target was last seen. This is not the same as having the ability to follow the target when it is out of line of sight. A monster will always walk towards the last seen position first before it tries to find a path to a target outside its current line of sight. If there is no such path it will simply walk around the last seen location until it is deactivated due to time. Example of this walk behavior is Balrogs, Gargoyles and Scavengers.

Walk away from target:	Will try to walk away from target, this includes walking sideways if the path is

blocked directly away from target. It will however not include walking past the target. A good example of this behavior is mages trying to escape from a player. This is also the reason why it is possible to trap monsters in corners. This type of walking is usually used for monsters retreating. Examples of monsters using this walk type is Hidden, Succubi, Archers and Mages.

Walk in circle:	Many monsters uses the circling type of walk. It basically means the monster

walks in a circular path around the target, often without either increasing nor decreasing the distance. Usually the monster using circular walk will once it has started that type of walking, do it until it has walked a distance equal to twice the current max distance to the target (max distance being the higher of the two distance values x and y in a coordinate system). It will also terminate the circle walk if it enters a new area or the distance to the target is reduced to 1. The direction will typically be chosen with a 50/50 chance for clockwise and counter clockwise. Examples of this walk type is Balrogs, Lightning Demons, Spitters, Diablo and Skeleton King.


### 5.5.4 About charging

If a monster has the possibility to charge and it has been decided that it should charge, the game will check if there is really a path along which to charge that is not blocked by for example lava or a fence. If that is the case, the script will generally continue finding another action to perform as if it was decided to not charge.


### 5.5.5 About ranged attack

When the game has decided to do a ranged attack, it will check if line of sight is blocked. If that is the case, the script will generally continue finding another action to perform as if it was decided to not do a ranged attack. Note however, that this check many times will not detect all hindrance which may result in the ranged attack being performed but yet hit an obstacle before reaching the target.


### 5.5.6 Target selection

When a monster is to choose which player character to attack (if there is more than one present in the game) it will generally chose the one that is closest. However, the process of finding out who is the closest is somewhat non intuitive as the game does not calculate the true distance, but separates distances for the 2 main axis of the dungeon. This is most easily explained with an example.

1. The dungeon is divided into several ”squares” of which each square can hold a monster, player, or some dungeon inventory. Call the axis of squares running from the upper left to the lower right X, and the one running from lower left to the upper right Y.

1. The game will then calculate the distance to each character separately for X and Y direction.
1. It will then for each character use the largest distance of X and Y.
1. Comparing the distance got from step 3, it will attack the one with the shortest distance.
1. If two characters are equally close, the one that has first entered the game will be the target. It is thus wise to have Warriors enter and create a game, then have the Rogues enter it and finally the Sorcerers. If someone leaves the game, the next person to enter the game will take the place of the character that just left, *not* the last place.

A monster will, of course, only consider those characters, including golems, that are within its current visible range and are not out of sight due to a wall or other obstacle. Golems are only targeted if adjacent to the monster or if the monster is a skeleton archer, goat archer or succubi at any distance.

If the target ever disappears form the sight of the monster, it tends to walk up to the last position the target was seen. If the target is still not visible, it will try to pick a new target. Some monsters, as noted in chapter 5.3.3, have the ability to follow a target even if it is out of sight. In that case, they will not walk up to the last position of the target or stop, but will instead find the closest way to the target if it is not too far away.


### 5.5.7 Non even distributed random numbers

Diablo and Hellfire uses a pretty good algorithm for random numbers, unfortunately it is at times used improperly which result in somewhat non random results at time. One of those cases exists in the AI scripts of Spitters, Magma Demons, Lightning Demons, Bone Demons and Diablo. Contrary to other AI scripts they use Rnd[10000] in some cases. Unfortunately the algorithm for random numbers only use 15 bits to calculate random numbers (it uses 32 bits internally but the random number is based on 15 bits only). This has the side effect that large values used in Rnd[x] will not be evenly distributed. In the case of Rnd[10000] lower values will be more common as there are really only 32 768 possible random integers. This is further complicated by the fact that the game then as a second random number in those AI scripts mentioned above uses a Rnd[100] but still compare the result as if it was a Rnd[10000] meaning the result will always default as if it was a low random number.

A further problem is the fact that the game reseeds the random number generator before processing the monsters. This is done to keep the game better in synch in multi player. Unfortunately this also cause problems in that monsters will not always act as they are supposed to, cause long streaks of the same result. An example is a monster missing continuously for almost an infinite time when they in fact should hit way more often due to having a auto To Hit for example (see chapter 5.1 under To Hit). This only affect monster behavior though, nothing else like item drops or the behavior of spells.


### 5.5.8 Reseed bug

In an attempt to keep monsters more in synch between computers in a multi player game, Blizzard has unfortunately used a rather strange and incorrect way of reseeding the random number generator in Diablo right before processing monsters (technically each monster has its own seed used for its behavior and it is the seeds of the monsters that are reseeded). This may cause the familiar result of a monster getting ”stuck” with a particular behavior or result both when acting and when attacking. This is unfortunate.


### 5.5.9 AI scripts

Here each of the different attack types will be described. Many monsters, but not all, have special behavior types of an overreaching nature. Often composed of several actions performed in succession either until completed or aborted for some reason. They will be explained separately at the start of each script. A *general* section describes things usually performed every time. This includes a monster under an overreaching behavior.

The step by step instructions to follow are divided into several sections depending on the distance to the target. Use the appropriate one. Some times further conditions may also be given. For the specific step by step, you should use them in the following way. Always start at number 1. If at anytime it says *goto #*, where # is a number, immediately move to that line and continue from there. If it at any time says *exit*, the script has finished and you should not read any more. If you exit or reach the end without a new action being set, the monster will continue to stand and will check again 0.05 seconds later, that is during the next update, see chapter 6.1for more information about how the game updates monsters and other things.

The scripts will only refer to attack options such as melee attack or ranged attack. For information about what type of ranged attack monsters have, see chapter 4.2.

Finally note that although quite detailed, there might still be many special cases, exceptions and other smaller facts omitted. It is still my belief that it is a comprehensive explanation of each attack type that will cover almost all cases.

Some common abbreviations are used in this chapter:

4. Distance to target. A distance of 1 means the target is adjacent ( see chapter 6.1.9 for a description on how to calculate distance to a walking target).

R	Usually a random number, the specific script will tell exactly how the random number is achieved.

Intf	Intelligence factor, see chapter 5.3.3 and 5.4.

light	Refers to the light radius of players.

**Zombie**

General

1. if out of light, exit
1. R = Rnd[100]

Distance = 1

1. if R < 2×Intf + 10, do melee attack, exit
1. continue to stand still

Distance = 2 to 2×Intf + 3

1. if R < 2×Intf + 10, walk towards target, exit
1. continue to stand still

Distance > 2×Intf + 3

1. if R >= 2×Intf + 10, continue to stand still, exit
1. calculate new R = Rnd[100]
1. if R < 2×Intf + 20, walk in random direction (if blocked, continue to stand still), exit
1. continue to walk in the same direction as last time (if blocked, continue to stand still)

**Fallen One**

When a monster is killed, any Fallen Ones within 5 squares will be set into *retreat* mode. Depending on what subtype the monster is the distance it will retreat is as explained in the table below. The distance is the distance it will walk, not necessarily the final distance to the target if the target has moved since the start of the retreat.

|**Fallen Ones**|**Retreat distance**|
| :- | -: |
|Fallen One|7|
|Carver|5|
|Devil Kin|3|
|Dark One|2|

Occasionally a Fallen One will do a war cry. It is recognized by the monster jumping up and screaming. When that happens any Fallen One within range (see table below), unless using another attack type, will be set into war cry mode. The war cry mode last for a specific time depending on the subtype doing the actual war cry, see table below. During the war cry mode, they will walk straight for the closest target and attack. If adjacent it will continue to attack without pausing until the time runs out for the war cry mode. Unfortunately the war cry mode also ends as soon as any close by monster is killed and the fallen one is set into retreat mode.

|**Fallen Ones**|**Distance**|**Time (sec)**|
| :- | -: | -: |
|Fallen One|4|5\.25|
|Carver|5|6\.75|
|Devil Kin|6|8\.25|
|Dark One|7|9\.75|

When doing a war cry, the monster will gain 2×Intf + 2 hit points. The current hit points will never go above the maximum value though.


War cry

1. if D = 1, do melee attack, exit
1. walk towards target

Retreating

1. Walk away from target until distance achieved

General

1. if not active, exit
1. if the monster has been standing for an even multiple of 0.55 seconds (0.60 if using a sword) and Rnd[4] = 0, do war cry, exit

1. if not active, exit
1. R = Rnd[100]

Distance = 1

1. if last action was delay, do melee attack, exit
1. if R < 2×Intf + 20, do melee attack, exit
1. do delay for (Rnd[10] + 10 - 2×Intf)/20 seconds

Distance > 1

1. if last action was delay, walk towards last seen position of target, exit
1. if R < 4×Intf + 65, walk towards last seen position of target, exit
1. do delay for (Rnd[10] + 15 - 2×Intf)/20 seconds

**Skeleton**

General

1. if not active, exit
1. R = Rnd[100]

Distance = 1

1. if last action was delay, do melee attack, exit
1. if R < 2×Intf + 20, do melee attack, exit
1. do delay for (Rnd[10] + 10 - 2×Intf)/20 seconds

Distance > 1

1. if last action was delay, walk towards last seen position of target, exit
1. if R < 4×Intf + 65, walk towards last seen position of target, exit
1. do delay for (Rnd[10] + 15 - 2×Intf)/20 seconds

**Skeleton Archer**

General

1. if not active, exit
1. R = Rnd[100]

Distance = 1 to 3

1. if last action was walking and standtime is 0 and R < 2×Intf + 63, walk away from target, exit
1. if standtime is greater than 1 second and R < 2×Intf + 13, walk away from target, exit

Distance > 3

1. if R < 2×Intf + 3, do ranged attack

**Scavenger**

The Scavenger AI has a special eating/digging mode activated when their HP reaches a low enough value. It will then seek the closes carcass of a dead monster within sight and walk up to it to eat/dig. While eating/digging, it will generate HP faster than normally, see chapter 5.1 under Hit Points for more information.


Eating/Digging

1. if monster is part of a unique monsters mob, remove it from mob
1. if at carcass, go into eat/dig mode, exit
1. walk towards closest carcass

General

1. if curHP < maxHP/2, set eating/digging mode, exit
1. if not active, exit
1. R = Rnd[100]

Distance = 1

1. if last action was delay, do melee attack, exit
1. if R < 2×Intf + 20, do melee attack, exit
1. do delay for (Rnd[10] + 10 - 2×Intf)/20 seconds

Distance > 1

1. if last action was delay, walk towards last seen position of target, exit
1. if R < 4×Intf + 65, walk towards last seen position of target, exit
1. do delay for (Rnd[10] + 15 - 2×Intf)/20 seconds

**Winged Fiends**

The Winged Fiend AI has a special retreat mode activated after having done a melee attack. It consists of walking away from the target on location and then walking into new adjacent location of the target. The result is a sort of V shaped walk.


Retreat

1. if last volunteer action, except walk, was not attack, exit from Retreat mode
1. if last walk was away from target, randomly walk either to the right or the left of target, exit
1. walk away from target

General

1. if not active, exit
1. R = Rnd[100]

Distance = 1

1. if R < 4×Intf + 8, do melee attack
1. if R < 4×Intf + 8 and the monster is a familiar, spawn lightning bolt attack

Distance = 2 to 3

1. if last action was walking and standtime is 0 and R < Intf + 63, walk towards target, exit
1. if standtime is greater than 1 second and R < Intf + 13, walk towards target

Distance > 3

1. if R < 4×Intf + 33 and the monster is a Gloom, do charge
1. if last action was walking and standtime is 0 and R < Intf + 63, walk towards target, exit
1. if standtime is greater than 1 second and R < Intf + 13, walk towards target


**Hidden**

As soon as a monster having the Hidden attack type, even if it is not a The Hiddens monster type, is stunned, it will retreat. Usually away from the player but the Unseen will instead move diagonally away. The distance it will retreat is explained in the table below. If the current target is a monster, away is defined as away form the controlling player.

|**Intelligence factor**|**Retreat distance**|
| -: | -: |
|0|8|
|1|7|
|2|6|
|3|5|

Hiddens are always active, that is, they move around regardless if you have activated them or not.


Retreat

1. if the monster is an Unseen, retreat diagonally randomly to the right or left, away from the target, exit
1. retreat straight away from target

General

1. R = Rnd[100]
1. if D < 5 - Intf and not visible, fade in, exit
1. if D > 5 - Intf and visible, fade out, exit

Distance = 1

1. if R < 4×Intf + 10, do melee attack

Distance > 1

1. if last action was walking and standtime is 0 and R < Intf + 64, walk towards target, exit
1. if standtime is greater than 1 second and R < Intf + 14, walk towards target

**Goat Man**

When finishing a circle walk, a monster using the Goat Man attack type will start walking towards the last seen position of the target.


General

1. if not active, exit
1. R = Rnd[100]

Distance = 1

1. if R >= 2×Intf + 23, exit
1. if curHP >= maxHP/2, do melee attack, exit
1. if Rnd[2] = 0, do melee attack, exit
1. do special spin attack

Distance > 1, out of light

1. if last action was walking and standtime is 0 and R < 2×Intf + 78, walk towards last seen position of target, exit

1. if standtime is greater than 1 second and R < 2×Intf + 28, walk towards last seen position of target

Distance = 1 to 3, in light

1. if target is in another area, use out of light AI
1. if last action was walking and standtime is 0 and R < 2×Intf + 78, walk towards last seen position of target, exit

1. if standtime is greater than 1 second and R < 2×Intf + 28, walk towards last seen position of target

Distance > 3, in light

1. if target is in another area, use out of light AI
1. if D > 3 and Rnd[4] = 0, start circle walk, exit

3. if last action was walking and standtime is 0 and R < 2×Intf + 78, walk towards last seen position of target, exit

3. if standtime is greater than 1 second and R < 2×Intf + 28, walk towards last seen position of target

**Overlord**

General

1. if not active, exit
1. R = Rnd[100]

Distance = 1

1. if R < 4×Intf + 15, do melee attack, exit
1. if R < 4×Intf + 20, do second melee attack

Distance > 1

1. if last action was walking and standtime is 0 and R < Intf + 70, walk towards target, exit
1. if standtime is greater than 1 second and R < Intf + 20, walk towards target

**Gargoyle**

By stone *state* is meant when in actual stone form. By stone *mode* is meant both when in stone state and while moving away from a target due to low HP. While in stone state, Gargoyles will heal faster than usual, see chapter 5.1.

When finishing a circle walk, a monster using the Gargoyle attack type will start walking towards the last seen position of the target.


Stone mode

1. if D < Intf + 2, mark as not in stone mode
1. if curHP >= maxHP/2, mark as not in stone mode
1. if D >= Intf + 2, go into stone state, exit
1. walk away from target

General

1. if not active, exit
1. R = Rnd[100]
1. if curHP < maxHP/2, go into stone mode

Distance = 1

1. if R >= 2×Intf + 23, exit
1. do melee attack

Distance > 1, out of light

1. if last action was walking and standtime is 0 and R < 2×Intf + 78, walk towards last seen position of target, exit

1. if standtime is greater than 1 second and R < 2×Intf + 28, walk towards last seen position of target

Distance 1 to 3, in light

1. if target is in another are, use out of light AI
1. if last action was walking and standtime is 0 and R < 2×Intf + 78, walk towards last seen position of target, exit

1. if standtime is greater than 1 second and R < 2×Intf + 28, walk towards last seen position of target

Distance > 1, in light

1. if target is in another are, use out of light AI
1. if D > 3 and Rnd[4] = 0, start circle walk, exit
1. if last action was walking and standtime is 0 and R < 2×Intf + 78, walk towards last seen position of target, exit

1. if standtime is greater than 1 second and R < 2×Intf + 28, walk towards last seen position of target


**Goat Archer**

General

1. if not active, exit
1. if out of sight of target and it is a player, walk towards last seen position of target, exit
1. R = Rnd[100]
1. if last action was a ranged attack, de delay for Rnd[20]/20 seconds, exit

Distance = 1 to 3

1. if R < 10×Intf + 70, walk away from target, exit

Distance > 3

1. do ranged attack

**Fast Spit**

General

1. if not active, exit
1. if out of sight of target and it is a player, walk towards last seen position of target, exit
1. R = Rnd[100]

Distance = 1 to 3

1. if R < 10×Intf + 70, walk away from target, exit

Distance > 3

1. do ranged attack

**Magma Demon**

When finishing a circle walk, a monster using the Magma Demon attack type will start walking towards the last seen position of the target.


Circle Walk

1. If R < 100×(5×Intf + 5), do ranged attack, exit (after this ranged attack, the monster will resume circle walk)
1. continue with circle walk

General

1. if not active, exit
1. R = Rnd[10000]

Distance = 1

1. if R < 100×(5×Intf + 5), do ranged attack, exit
1. if R < 100×(10×Intf + 60), do attack, exit
1. do delay for (Rnd[10] + 5)/20 seconds

Distance > 1, out of light

1. calculate new R = Rnd[100]
1. if R < 100×(10×Intf + 50), walk towards last seen position of target, exit
1. if last action was walking and standtime is 0 and R < 100×(10×Intf + 80), walk towards last seen position of target, exit

1. do delay for (Rnd[10] + 5)/20 seconds

Distance = 2, in light

1. if target is in another area, use out of light AI
1. if R < 100×(5×Intf + 5), do ranged attack, exit
1. calculate new R = Rnd[100]
1. if R < 100×(10×Intf + 50), walk towards last seen position of target, exit
1. if last action was walking and standtime is 0 and R < 100×(10×Intf + 80), walk towards last seen position of target, exit

1. do delay for (Rnd[10] + 5)/20 seconds

Distance > 2, in light

1. if target is in another area, use out of light AI
1. if Rnd[4] = 0, start circle walk, exit
1. if R < 100×(5×Intf + 10), do ranged attack, exit
1. calculate new R = Rnd[100]
1. if R < 100×(10×Intf + 50), walk towards last seen position of target, exit
1. if last action was walking and standtime is 0 and R < 100×(10×Intf + 80), walk towards last seen position of target, exit

1. do delay for (Rnd[10] + 5)/20 seconds

Due to using Rnd[10000], the random number will not be evenly distributed, see chapter 5.5.7. In the steps where a new R = Rnd[100] is calculated, it is not a typo of mine, but most likely a bug and should have read R = Rnd[10000]


**Viper**

Monsters with the Viper attack type will not walk straight towards the location of the monster as most other monsters. Instead, it will use a sort of winding walk. It will go through a cycle and the walk direction it aims for is slightly of either clockwise or counterclockwise (if the correct direction is north, it will aim for a direction either northwest or northeast). If the monster is then not facing this new direction, it will turn one step towards it and walk in that direction. The table below summarize how the cycle of aimed direction is done.

|**Cycle step**|**change of direction**|||**New aimed direction**||||||
| -: | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|||**N**|**NE**|**E**|**SE**|**S**|**SW**|**W**|**NW**|
|1|counterclockwise|NW|N|NE|E|SE|S|SW|W|
|2|counterclockwise|NW|N|NE|E|SE|S|SW|W|
|3|none|N|NE|E|SE|S|SW|W|NW|
|4|clockwise|NE|E|SE|S|SW|W|NW|N|
|5|clockwise|NE|E|SE|S|SW|W|NW|N|
|6|none|N|NE|E|SE|S|SW|W|NW|

General

1. if not active, exit
1. R = Rnd[100]

Distance = 1

1. if last action was delay or charge, do attack, exit
1. if R < Intf + 20, do attack, exit
1. do delay for (Rnd[10] + 10 - Intf)/20 seconds

Distance = 2

1. if last action was charge, act as distance > 2
1. if charge is not possible, act as distance > 2
1. do charge

Distance > 2

1. if last action was delay, walk, exit
1. if R < 2×Intf + 65, walk, exit
1. do delay for (Rnd[10] + 15 - Intf)/20 seconds

**Spit**

When finishing a circle walk, a monster using the Spit attack type will start walking towards the last seen position of the target.


Circle Walk

1. If R < 100×(5×Intf + 5)/2, do ranged attack, exit (after this ranged attack, the monster will resume circle walk)

1. continue with circle walk

General

1. if not active, exit
1. R = Rnd[10000]

Distance = 1

1. if R < 100×(5×Intf + 5)/2, do ranged attack, exit
1. if R < 100×(10×Intf + 60), do attack, exit
1. do delay for (Rnd[10] + 5)/20 seconds

Distance > 1, out of light

1. calculate new R = Rnd[100]
1. if R < 100×(10×Intf + 50), walk towards last seen position of target, exit
1. if last action was walking and standtime is 0 and R < 100×(10×Intf + 80), walk towards last seen position of target, exit

1. do delay for (Rnd[10] + 5)/20 seconds

Distance = 2, in light

1. if target is in another area, use out of light AI
1. if R < 100×(5×Intf + 5)/2, do ranged attack, exit
1. calculate new R = Rnd[100]
1. if R < 100×(10×Intf + 50), walk towards last seen position of target, exit
1. if last action was walking and standtime is 0 and R < 100×(10×Intf + 80), walk towards last seen position of target, exit

1. do delay for (Rnd[10] + 5)/20 seconds

Distance > 2, in light

1. if target is in another area, use out of light AI
1. if Rnd[8] = 0, start circle walk, exit
1. if R < 100×(5×Intf + 10)/2, do ranged attack, exit
1. calculate new R = Rnd[100]
1. if R < 100×(10×Intf + 50), walk towards last seen position of target, exit
1. if last action was walking and standtime is 0 and R < 100×(10×Intf + 80), walk towards last seen position of target, exit

1. do delay for (Rnd[10] + 5)/20 seconds

Due to using Rnd[10000], the random number will not be evenly distributed, see chapter 5.5.7. In the steps where a new R = Rnd[100] is calculated, it is not a typo of mine, but most likely a bug and should have read R = Rnd[10000]


**Butcher**

1. if not active, exit

1. if D =1, attack, exit
1. walk towards target

**Balrog**

When finishing a circle walk, a monster using the Balrog attack type will start walking towards the last seen position of the target.


General

1. if not active, exit
1. if D > 4, continue with skeleton AI, exit
1. R = Rnd[10000]

Distance = 1

1. if R < 5×Intf + 5, do spell attack, exit
1. calculate new R = Rnd[100]
1. if R >= 10×Intf + 40, do delay for (Rnd[10] + 5)/20 seconds, exit
1. if Rnd[2] = 0, do spell attack, exit
1. do melee attack

Distance > 1, out of light

1. if R < 10×Intf + 50, walk towards last seen position of target, exit
1. if last action was walk and R < 10×Intf + 80, walk towards last seen position of target, exit
1. do delay for (Rnd[10] + 5)/20 seconds

Distance = 2, in light

1. if last action was circle walk, do spell attack, exit
1. if R < 5×Intf + 5, do spell attack, exit
1. calculate new R = Rnd[100]
1. if R < (10×Intf + 50), walk towards last seen position of target, exit
1. if last action was not walk, walk towards last seen position of target, exit
1. do delay for (Rnd[10] + 5)/20 seconds

Distance > 2, in light

1. if target is in same area, start circle walk, exit
1. if last action was circle walk, do spell attack, exit
1. if R < 5×Intf + 10, do spell attack, exit
1. calculate new R = Rnd[100]
1. if R < (10×Intf + 50), walk towards last seen position of target, exit
1. if last action was not walk, walk towards last seen position of target, exit
1. do delay for (Rnd[10] + 5)/20 seconds

**Skeleton King**

When finishing a circle walk, a monster using the Skeleton King attack type will start walking towards the last seen position of the target.


General

1. if not active, exit
1. R = Rnd[10000]

Distance = 1

1. in single player, if R < 5, then do revive skeleton, exit
1. if R < Intf + 20, do melee attack

Distance > 1, out of light

1. if last action was walking and standtime is 0 and R < Intf + 75, walk towards last seen position of target, exit

1. if standtime is greater than 1 second and R < Intf + 25, walk towards last seen position of target, exit
1. do delay for (Rnd[10] + 10)/20 seconds

Distance = 2, in light

1. in single player, if R < 5, then do revive skeleton, exit
1. if last action was walking and standtime is 0 and R < Intf + 75, walk towards last seen position of target, exit

1. if standtime is greater than 1 second and R < Intf + 25, walk towards last seen position of target, exit
1. do delay for (Rnd[10] + 10)/20 seconds

Distance > 2, in light

1. if target is in another area, use out of light AI
1. if Rnd[4] = 0, start circle walk, exit
1. in single player, if 4×Intf + 35, then do revive skeleton, exit
1. if last action was walking and standtime is 0 and R < Intf + 75, walk towards last seen position of target, exit

1. if standtime is greater than 1 second and R < Intf + 25, walk towards last seen position of target, exit
1. do delay for (Rnd[10] + 10)/20 seconds

**Horned Demon**

When finishing a circle walk, a monster using the Horned Demon attack type will start acting normally but will not pick circle walk as its next action.

General

1. if not active, exit
1. R = Rnd[10000]

Distance = 1

1. if R < 2×Intf + 28, do melee attack, exit

Distance = 2 to 4

1. if last action was walking and standtime is 0 and R < 2×Intf + 33, walk towards last seen position of target, exit

1. if standtime is greater than 1 second and R < 2×Intf + 83, walk towards last seen position of target
1. do delay for (Rnd[10] + 10)/20 seconds

Distance > 4

1. if target is in same area Rnd[4] > 0 then start circle walk
1. if R < 2×Intf + 43 and the line of sight is clear, do charge attack, exit
1. if last action was walking and standtime is 0 and R < 2×Intf + 33, walk towards last seen position of target, exit

1. if standtime is greater than 1 second and R < 2×Intf + 83, walk towards last seen position of target
1. do delay for (Rnd[10] + 10)/20 seconds

**Mage**

Mages have the ability to disappear (phase in and phase out), much like The Hiddens. They will phase out whenever they initiate any walking (including circle walk). When the walking is over, even if it is in the same location as they started the walk, they will phase in. Thus one can say that they are non visible while walking.

When finishing a circle walk, a monster using the Mage attack type will start walking towards the last seen position of the target.


Retreat mode

1. if D < 3, walk away from target

General

1. if not active, exit
1. R = Rnd[10000]

Distance = 1

1. if curHP < maxHP/2, go into retreat mode
1. if last action was a delay, do flash attack, exit
1. if R < 2×Intf + 20, do flash attack, exit
1. do delay for (Rnd[10] + 10 - 2×Intf)/20 seconds

Distance > 1

1. if in light and R < 5×Intf + 50, do ranged attack, exit
1. calculate new R = Rnd[100]
1. if R < 30, enter circle walk, exit
1. do delay for (Rnd[10] + 10 - 2×Intf)/20 seconds

**Special**

Special AI scripts are used for most quest monsters. For those not mentioned specifically previously, the only difference from a normal AI script of that monster type is quest related things such as talking. The actual AI behavior when you fight those monsters are identical to the normal AI and is summarized in the table below.

|<a name="page128"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|**Created by Pedro Faria**|||
| :- | :- | :- | :- |
|||||
||**Unique monster**|**AI script to use**||
||Snotspill|Fallen One||
||Gharbad the Weak|Goat Man||
||Blackjade|Succubi||
||Red Vex|Succubi||
||Warlord of Blood|Skeleton||
||Lachdanan|n/a||
||Zhar the Mad|Mage||
||Arch-Bishop Lazarus|Mage||

## 5.6 Summary of various monster stats

This chapter summarizes various properties of monsters and lets you review them without being confused by other non related properties. All data below can, of course, be found in the complete tables in chapter 5.2 -5.4.


### 5.6.1 Resistances, immunities and uniques for monsters

This is a summary of the resistance’s and immunities of monsters, as well as on what level they appear. Good for a quick look when you first enter a level and see the monsters for the first time. It also lists on what level, if any, a unique monster might appear. For data on the unique monsters, see chapter 5.3. I have also added the ability to open doors, *Door*, and to follow you around walls, *Follow*, for each monster.

|**Dlvl**|**Name of Monster**|**MFL**|**MFL**|**Door**|**Follow**|**Unique monsters, dlvl**|
| :-: | :- | :- | :- | :- | :-: | :- |
||||**Hell**||||
|1-2|Zombie|I--|I--|||Rotfeast, 2, Soulpus, 2|
|2-3|Ghoul|I--|I--|||Rotcarnage, 3|
|2-4|Rotting Carcass|I--|IR-|||Goretongue, 3|
|3-5|Black Death|I--|I-R||||
|1-3|Fallen One, spear|||||Pukerat the Unclean, 2|
|2-3|Carver, spear||||||
|2-4|Devil Kin, spear||-R-|||Bongo, 3|
|3-5|Dark One, spear||--R|||Snotspill, 4|
|1-3|Fallen One, sword|||||Bladeskin the Slasher, 2|
|2-3|Carver, sword|||||Gutshank the Quick, 3|
|2-4|Devil Kin, sword||-R-||||
|3-5|Dark One, sword||--R|||Shadowcrow, 5|
|1-2|Skeleton|I--|I--|||Boneripper, 2|
|2-3|Corpse Axe|I--|I--|||Bonehead Keenaxe, 2|
|2-4|Burning Dead|IR-|II-|||Madeye the Dead, 4|
|3-5|Horror|I-R|I-R||||
|2-3|Skeleton Archer|I--|I--|||Deadeye, 2|
|2-4|Corpse Bow|I--|I--|||Skullfire, 3|
|3-5|Burning Dead Archer|IR-|II-|||Blackash the Burning, 4|
|4-6|Horror Archer|I-R|I-R||||
|1-3|Skeleton Captain|I--|I--||||
|2-4|Corpse Captain|I--|I--|||Brokenhead Bangshield, 3|
|3-5|Burning Dead Captain|IR-|II-||||
|4-6|Horror Captain|I-R|I-R||Yes|Shadow Drinker, 5|

|<a name="page129"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**||||**Created by Pedro Faria**|||||
| :- | :- | :- | :- | :- | :- | :- | :- | :- |
||||||||||
|**dlvl**|**Name of Monster**|**MFL**||**MFL**|**Door**|**Follow**|**Unique monsters, dlvl**||
|||||**Hell**|||||
|1-3|Scavenger|||-R-|||Shadowbite, 2||
|2-4|Plague Eater|||--R|||El Chupacabras, 3||
|3-5|Shadow Beast|||-R-|||Pulsecrawler, 4||
|3-6|Bone Gasher|R--||--R|||Spineeater, 4||
|2-3|Fiend|---||---|||||
|3-5|Blink|---||---|||Moonbender, 4, Wrathraven, 5||
|4-6|Gloom|R--||R--||Yes|Foulwing, 5||
|6-8|Familiar|R-I||R-I||Yes|||
|2-5|Hidden|---||---|||Warpskull, 3||
|5-7|Stalker|---||---||Yes|||
|6-8|Unseen|R--||I--||Yes|||
|7,8-10|Illusion Weaver|RR-||IR-||Yes|||
|2,4-6|Flesh Clan|---||---|Yes|Yes|Gharbad the Weak, 4||
|5-7|Stone Clan|R--||I--|Yes|Yes|Deathshade Fleshmaul, 6||
|6-8|Fire Clan|-R-||-I-|Yes|Yes|Bloodgutter, 6||
|7-9|Night Clan|R--||I--|Yes|Yes|Blighthorn Steelmace, 7||
|2,4-6|Flesh Clan Archer|---||---|Yes||Bloodskin Darkbow, 5||
|5-7|Stone Clan Archer|R--||I--|Yes||||
|6-8|Fire Clan Archer|-R-||-I-|Yes|Yes|Blightfire, 7||
|7-9,10|Night Clan Archer|R--||I--|Yes|Yes|Gorestone, 7||
|4,5-7|Overlord|---||-R-|||Bilefroth the Pit Master, 6||
|7-9|Mud Man|---||--I||Yes|Baron Sludge, 8||
|8-10|Toad Demon|I--||I-R||Yes|Oozedrool, 9||
|10-12|Flayed One|RI-||II-||Yes|||
||||||||||
|**dlvl**|**Name of Monster**|**MFL**||**MFL**|**Door**|**Follow**|**Unique monsters, dlvl**||
|||||**Hell**|||||
|5-7|Winged-Demon|IR-||II-|Yes||||
|7-9|Gargoyle|I-R||I-I|Yes||Nightwing the Cold, 7||
|9-11|Blood Claw|II-||IIR|Yes||Goldblight of the Flame, 10||
|10-12|Death Wing|I-I||IRI|Yes||Viletouch, 12||
|8-9|Magma Demon|IR-||II-|Yes|Yes|Firewound the Grim, 8||
|8-10|Blood Stone|II-||II-|Yes|Yes|||
|9-11|Hell Stone|II-||II-|Yes|Yes|||
|9-11|Lava Lord|II-||II-|Yes|Yes|||
|5,7-9|Horned Demon|---||-R-|Yes|Yes|||
|8-10|Mud Runner|---||-R-|Yes|Yes|Breakspine, 9||
|9-11|Frost Charger|I-R||I-R|Yes|Yes|Bluehorn, 11||
|10-12|Obsidian Lord|I-R||III|Yes|Yes|Blackstorm, 10||
|6-8|Acid beast|---||I--|||Deathspit, 6||
|8-10|Poison Spitter|---||I--|||Chaoshowler, 8, Plaguewrath, 10||
|10-12|Pit Beast|R--||I-R|||||
|12-14|Lava Maw|RI-||II-|||||
|9-11|Red Storm|I-R||I-I|Yes|Yes|Brokenstorm, 9||
|10-12|Storm Rider|R-I||I-I|Yes|Yes|The Flayer, 10||
|11-13|Storm Lord|R-I||I-I|Yes|Yes|||
|12-14|Maelstorm|R-I||I-I|Yes|Yes|Doomcloud, 13||
|10-12|Slayer|RI-||RI-|Yes|Yes|||
|11-13|Guardian|RI-||RI-|Yes|Yes|||
|12-14|Vortex Lord|RI-||RI-|Yes|Yes|Windspawn, 12, Gorefeast, 13||
|13-15|Balrog|RI-||RIR|Yes|Yes|Blackskull, 13||

|<a name="page130"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**||||**Created by Pedro Faria**|||||
| :- | :- | :- | :- | :- | :- | :- | :- | :- |
||||||||||
|**dlvl**|**Name of Monster**|**MFL**||**MFL**|**Door**|**Follow**|**Unique monsters, dlvl**||
|||||**Hell**|||||
|11-13|Cave Viper|I--||I--||Yes|Fangspeir, 11||
|12-14|Fire Drake|IR-||II-||Yes|Viperflame, 12||
|13-14|Gold Viper|I-R||I-R||Yes|Fangskin, 14||
|15-15|Azure Drake|-RR||IRI||Yes|||
|12-14|Succubus|R--||IR-|Yes||Witchfire the Unholy, 12||
|13-15|Snow Witch|--R||I-R|Yes||Witchmoon, 13||
|14-15|Hell Spawn|R-I||IIR|Yes|Yes|Stareye the Witch, 14, Bloodlust, 151||
|15-15|Soul Burner|RIR||III|Yes|Yes|||
|12-14,16|Black Knight|R-R||R-I||Yes|Lionskull the Bent, 12||
|13-15|Doom Guard|RR-||RI-||Yes|Rustweaver, 13, Graywar, 14||
|13,14-15|Steel Lord|RIR||IIR||Yes|Warlord of Blood, 13, Steelskull, 14||
|13-14,16|Blood Knight|IRI||IRI||Yes|Lachdanan, 14, Sir Gorash, 16||
|13-14|Counselor|RRR||RRR|Yes||Zhar the Mad, 8||
|14-15|Magistrate|RIR||IIR|Yes||Dreadjudge, 14||
|15-15|Cabalist|RRI||IRI|Yes||The Vizier, 15||
|15,16-16|Advocate|IRI||III|Yes||Arch-Bishop Lazarus, 15||
1	Black Jade and Red Vex also appear on level 15 in Arch-Bishop Lazarus’ chamber.

The new monsters in Hellfire do not have any unique monsters. That is the reason there is no such field in the table below.

|**Dlvl**|**Name of**|**MFL**|**MFL**|**Door**|**Follow**|**dlvl**|**Name of**|**MFL**|**MFL**|**Door**|**Follow**|
| :-: | :- | :- | :- | :-: | :-: | :-: | :- | :- | :- | :-: | :- |
|**Hive**|**Monster**||**Hell**|||**Crypt**|**Monster**||**Hell**|||
|1-2|The Shredded|-RR|-RR|||1-1|Gravedigger|--I|RRI|Yes||
|1-2|Felltwin|---|IR-|Yes|Yes|1-2|Tomb Rat|---|-RR|||
|1-2|Hellboar|-RR|---||Yes|1-2|Devil Kin Brute|-RR|RRR|||
|2-3|Hork Spawn|I--|I--|||1-2|Firebat|-I-|RIR|||
|1-2|Stinger|---|--R|||3-4|Hellbat|RIR|RII|||
|3-4|Venomtail|--R|-RI|||1-2|Skullwing|-RR|-RR|||
|1-2|Psychorb|---|-R-|||3-4|Bone Demon|-II|-II|||
|3-4|Necromorb|-R-|-IR|||1-2|Lich|--R|RRI|||
|1-2|Arachnon|---|--R||Yes|3-4|Arch Lich|RRI|III|||
|3-4|Spider Lord|--R|-RI||Yes|1-2|Satyr Lord|-RR|RII|||
|3-4|Lashworm|---|-R-|||2-3|Crypt Demon|IRR|IIR|||
|3-4|Torchant|-I-|RIR|||3-4|Biclops|--R|-RR|Yes||
|||||||3-4|Flesh Thing|RRR|RRR|||
|||||||3-4|Reaper|IIR|III|||

### 5.6.2 Resistances, immunities and mob for unique monsters

This is a summary of the unique monsters sorted by dlvl instead of monster type. This makes it very easy to quickly see what potential unique monsters can appear on a dlvl, especially if you have seen what monster types are present, as a unique monster will always appear if its monster type is present on the dungeon level.

|<a name="page131"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|||**Created by Pedro Faria**||||
| :- | :- | :- | :- | :- | :- | :- |
||||||||
|**Dlvl**|**Name**|**Type**|**Mob**|**MFL**|**New attack type**||
|**2**|Bladeskin the Slasher|Fallen One, sword||-R-|||
||Bonehead Keenaxe|Corpse Axe|Yes|I--|||
||Boneripper|Skeleton|Yes|II-|Winged Fiend||
||Deadeye|Skeleton Archer||IR-|Goat Archer||
||Pukerat the Unclean|Fallen One, spear|Yes|-R-|||
||Rotfeast the Hungry|Zombie|Yes|I--|Skeleton||
||Shadowbite|Scavenger|Yes|-I-|Skeleton||
||Soulpus|Zombie||-RR|||
|**3**|Bongo|Devil Kin, spear|Yes||||
||Brokenhead Bangshield|Corpse Captain|Yes|I-R|||
||El Chupacabras|Plague Eater|Yes|-R-|Goat Man||
||Goretongue|Rotting Carcass||I--|Skeleton||
||Gutshank the Quick|Carver, sword|Yes|-R-|Winged Fiend||
||Rotcarnage|Ghoul|Yes|I-R|||
||Skullfire|Corpse Bow||-I-|Goat Archer||
||Warpskull|Hidden|Yes|-RR|||
|**4**|Blackash the Burning|Burning Dead Archer|Yes|II-|Goat Archer||
||Gharbad the Weak1|Flesh Clan||--I|||
||Madeye the Dead|Burning Dead|Yes|II-|Winged Fiend||
||Moonbender|Blink|Yes|-I-|||
||Pulsecrawler|Shadow Beast|Yes|-IR|||
||Snotspill1|Dark One, spear||--R|Special||
||Spineeater|Bone Gasher|Yes|--I|||
|1  Only appears in quests in single player.|||||||
||||||||
|**Dlvl**|**Name**|**Type**|**Mob**|**MFL**|**New attack type**||
|**5**|Bloodskin Darkbow|Flesh Clan Archer|Yes|-RR|||
||Foulwing|Gloom|Yes|-R-|Horned Demon||
||Shadowcrow1|Dark One, sword|Yes||Hidden||
||Shadowdrinker1|Horror Captain|Yes|IRR|Hidden||
||Wrathraven|Blink|Yes|-I-|||
|**6**|Bilefroth the Pit Master|Overlord|Yes|IIR|Winged Fiend||
||Bloodgutter|Fire Clan|Yes|-I-|Winged Fiend||
||Deathshade Fleshmaul2|Stone Clan|Yes|IR-|Horned Demon||
||Deathspit3|Acid Beast|Yes|-RR|Fast Spit||
|**7**|Blightfire4|Fire Clan Archer|Yes|-I-|Succubi||
||Blighthorn Steelmace2|Night Clan|Yes|--R|Horned Demon||
||Gorestone|Night Clan Archer|Yes|--R|||
||Nightwing the Cold|Gargoyle|Yes|I-R|Winged Fiend||
|**8**|Baron Sludge1|Mud Man|Yes|IRR|Hidden||
||Chaoshowler3|Poison Spitter|Yes||Fast Spit||
||Firewound the Grim|Magma Demon|Yes|IR-|||
||Zhar the Mad5|Counselor||IRR|Special||
1. Has the ability to disappear, like The Hiddens.
1. Has the ability to charge, like Horned Demons.

1. Never attacks in melee but always uses fast spit instead.

1. Has the ability to fire Blood Stars instead of arrows, like Succubi.

1. Has the ability to fire Fireballs instead of Firebolts, like Advocates. Only appears in quests in single player.

|<a name="page132"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|||**Created by Pedro Faria**||||
| :- | :- | :- | :- | :- | :- | :- |
||||||||
|**Dlvl**|**Name**|**Type**|**Mob**|**MFL**|**New attack type**||
|**9**|Breakspine|Mud Runner|Yes|-R-|||
||Brokenstorm|Red Storm|Yes|--I|||
||Oozedrool|Toad Demon|Yes|--R|||
|**10**|Blackstorm|Obsidian Lord|Yes|I-I|||
||The Flayer|Storm Rider|Yes|RRI|||
||Goldblight of the Flame|Blood Claw|Yes|II-|||
||Plaguewrath1|Poison Spitter|Yes|IR-|Fast Spit||
|**11**|Bluehorn|Frost Charger|Yes|IR-|||
||Fangspeir2|Cave Viper|Yes|-I-|Skeleton||
|**12**|Lionskull the Bent|Black Knight|Yes|III|||
||Viletouch|Death Wing|Yes|--I|||
||Viperflame2|Fire Drake|Yes|-IR|Skeleton||
||Windspawn3|Vortex Lord|Yes|II-|Skeleton||
||Witchfire the Unholy|Succubus|Yes|IIR|||
1. Never attacks in melee but always uses fast spit instead.
1. Will never do the short range Viper charge.

1. Never casts Inferno but always attacks by melee instead.

|**Dlvl**|**Name**|**Type**|**Mob**|**MFL**|**New attack type**|
| :-: | :- | :- | :-: | :- | :- |
|**13**|Blackskull1|Balrog|Yes|I-R|Skeleton|
||Doomcloud|Maelstorm||-RI||
||Gorefeast|Vortex Lord||-R-|Skeleton|
||Rustweaver|Doom Guard||III||
||Warlord of Blood2|Steel Lord||III|Special|
||Witchmoon|Snow Witch||--R||
|**14**|Dreadjudge|Magistrate|Yes|IRR||
||Fangskin3|Gold Viper|Yes|I-R|Skeleton|
||Graywar the Slayer|Doom Guard||--R||
||Lachdanan2|Blood Knight|||Special|
||Stareye the Witch|Hell Spawn||-I-||
||Steelskull the Hunter|Steel Lord||--R||
|**15**|Blackjade4|Hell Spawn||I-R|Special|
||Bloodlust5|Hell Spawn||I-I||
||Arch-Bishop Lazarus6|Advocate||IRR|Special|
||Red Vex4|Hell Spawn||IR-|Special|
||The Vizier|Cabalist|Yes|-I-||
|**16**|Sir Gorash6|Blood Knight||||
1. Never casts Inferno but always attacks by melee instead.
1. Only appears in quests in single player.

1. Will never do the short range Viper charge.

1. Always appears in Arch-Bishop Lazarus’ room.

1. Always appears in every multi player game.

1. Always appears in every game.


### 5.6.3 Experience points from monsters

Chapter 5.2 listed the base number of experience points you receive for a monster, as well as the formula for calculating how much you actually get depending on your current level. The tables below list the last level your character will receive full experience (200×clvl or the total experience points needed for advancing to the next clvl divided by 20, whichever is the lowest, see chapter 2.6 for more information) for killing a monster.. It will also list the last level you receive any experience at all for killing a monster (always at a level 9 higher than the monsters level). It gives you those levels for all three difficulty settings. As there is no cap on experience points awarded for killing a monster in single player, that information only applies to multi player.

|<a name="page133"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**||||**Created by Pedro Faria**||||||
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|||||||||||
|||**Normal**|**Nightmare**||**Hell**|||||
|**Levels**|**Name of Monster**|**Full**|**Any**|**Full**|**Any**|**Full**||**Any**||
|1-2|Zombie|-|10|13|25|27||40||
|2-3|Ghoul|-|11|13|26|28||41||
|2-4|Rotting Carcass|1|13|15|28|30||43||
|3-5|Black Death|2|15|17|30|32||45||
|1-3|Fallen One, spear|-|10|13|25|27||40||
|2-3|Carver, spear|-|12|14|27|29||42||
|2-4|Devil Kin, spear|1|14|16|29|31||44||
|3-5|Dark One, spear|2|16|17|31|33||46||
|1-3|Fallen One, sword|-|10|13|25|27||40||
|2-3|Carver, sword|1|12|14|27|29||42||
|2-4|Devil Kin, sword|2|14|16|29|31||44||
|3-5|Dark One, sword|2|16|17|31|33||46||
|1-2|Skeleton|-|10|13|25|27||40||
|2-3|Corpse Axe|-|11|13|26|28||41||
|2-4|Burning Dead|1|13|15|28|30||43||
|3-6|Horror|2|15|17|30|32||45||
|2-3|Skeleton Archer|1|12|14|27|29||42||
|2-4|Corpse Bow|2|14|16|29|31||44||
|3-5|Burning Dead Archer|3|16|18|31|34||46||
|3-6|Horror Archer|4|18|20|33|37||48||
|1-2|Skeleton Captain|-|11|14|26|28||41||
|2-4|Corpse Captain|2|13|15|28|31||43||
|3-5|Burning Dead Captain|3|15|18|30|33||45||
|4-6|Horror Captain|4|17|20|32|36||47||
|||||||||||
|||**Normal**|**Nightmare**||**Hell**|||||
|**Levels**|**Name of Monster**|**Full**|**Any**|**Full**|**Any**|**Full**||**Any**||
|1-3|Scavenger|-|11|14|26|28||41||
|2-4|Plague Eater|1|13|15|28|30||43||
|3-5|Shadow Beast|3|15|17|30|33||45||
|3-5|Bone Gasher|4|17|20|32|36||47||
|2-3|Fiend|1|12|14|27|29||42||
|3-5|Blink|3|16|18|31|34||46||
|4-6|Gloom|4|18|20|33|36||48||
|5-8|Familiar|4|22|22|37|39||-||
|2-5|Hidden|2|14|16|29|32||44||
|5-7|Stalker|4|18|21|33|37||48||
|6-8|Unseen|6|20|23|35|40||-||
|7,8-10|Illusion Weaver|9|22|27|37|44||-||
|2,3-6|Flesh Clan|4|17|19|32|35||47||
|5-7|Stone Clan|5|19|21|34|38||49||
|6-8|Fire Clan|6|21|24|36|41||-||
|7-9|Night Clan|8|23|26|38|43||-||
|2,3-6|Flesh Clan Archer|4|17|19|32|35||47||
|5-7|Stone Clan Archer|5|19|21|34|38||49||
|6-8|Fire Clan Archer|6|21|23|36|40||-||
|7-10|Night Clan Archer|8|23|26|38|43||-||
|4,5-7|Overlord|5|19|21|34|38||49||
|7-9|Mud Man|8|23|26|38|43||-||
|8-10|Toad Demon|10|25|28|40|46||-||
|10-12|Flayed One|15|29|33|44|50||-||

|<a name="page134"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**||||**Created by Pedro Faria**||||||
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|||||||||||
|||**Normal**|**Nightmare**||**Hell**|||||
|**Levels**|**Name of Monster**|**Full**|**Any**|**Full**|**Any**|**Full**||**Any**||
|5-6|Winged-Demon|5|18|21|33|37||48||
|7-9|Gargoyle|8|22|26|37|43||-||
|9-11|Blood Claw|14|28|32|43|50||-||
|10-11|Death Wing|17|32|36|47|50||-||
|7-9|Magma Demon|8|22|25|37|42||-||
|7-10|Blood Stone|9|23|27|38|44||-||
|9-11|Hell Stone|11|25|29|40|47||-||
|8-12|Lava Lord|14|27|32|42|49||-||
|5,6-9|Horned Demon|8|22|26|37|43||-||
|8-10|Mud Runner|10|24|28|39|45||-||
|9-11|Frost Charger|12|26|30|41|48||-||
|10-12|Obsidian Lord|13|28|32|43|50||-||
|6-8|Acid beast|6|20|23|35|40||-||
|8-10|Poison Spitter|9|24|27|39|44||-||
|10-12|Pit Beast|15|30|34|45|50||-||
|12-14|Lava Maw|20|34|39|49|50||-||
|9-11|Red Storm|14|27|32|42|50||-||
|10-12|Storm Rider|16|29|34|44|50||-||
|11-13|Storm Lord|18|31|37|46|50||-||
|12-14|Maelstorm|20|33|39|48|50||-||
|10-12|Slayer|16|29|34|44|50||-||
|11-13|Guardian|18|31|37|46|50||-||
|12-14|Vortex Lord|21|33|39|48|50||-||
|13-15|Balrog|23|35|41|-|50||-||
|||||||||||
|||**Normal**|**Nightmare**||**Hell**|||||
|**Levels**|**Name of Monster**|**Full**|**Any**|**Full**|**Any**|**Full**||**Any**||
|11-13|Cave Viper|17|30|36|45|50||-||
|12-14|Fire Drake|20|32|38|47|50||-||
|13-14|Gold Viper|22|34|40|49|50||-||
|14-15|Azure Drake|24|36|43|-|50||-||
|10-14|Succubus|22|33|40|48|50||-||
|13-15|Snow Witch|24|35|42|-|50||-||
|14-15|Hell Spawn|26|37|44|-|50||-||
|14-15|Soul Burner|27|39|46|-|50||-||
|12-14,16|Black Knight|21|33|39|48|50||-||
|13-15|Doom Guard|23|35|41|-|50||-||
|13-15|Steel Lord|25|37|44|-|50||-||
|12-16|Blood Knight|28|39|47|-|50||-||
|13-14|Counselor|23|34|41|49|50||-||
|14-15|Magistrate|25|36|43|-|50||-||
|14-15|Cabalist|27|38|46|-|50||-||
|15-16|Advocate|28|39|47|-|50||-||

|<a name="page135"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**||||**Created by Pedro Faria**||||||
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|||||||||||
|||**Normal**|**Nightmare**||**Hell**|||||
|**Levels**|**Name of Monster**|**Full**|**Any**|**Full**|**Any**|**Full**||**Any**||
|1-2|The Shredded|10|32|31|47|49||-||
|1-2|Felltwin|7|31|28|46|47||-||
|1-2|Hellboar|9|32|30|47|49||-||
|2-3|Hork Spawn|4|31|26|46|44||-||
|1-2|Stinger|6|31|28|46|46||-||
|3-4|Venomtail|11|33|32|48|50||-||
|1-2|Psychorb|5|31|27|46|46||-||
|3-4|Necromorb|12|33|33|48|50||-||
|1-2|Arachnon|6|31|28|46|46||-||
|3-4|Spider Lord|13|33|33|48|50||-||
|3-4|Lashworm|6|29|27|44|45||-||
|3-4|Torchant|12|31|32|46|50||-||
|||||||||||
|||**Normal**|**Nightmare**||**Hell**|||||
|**Levels**|**Name of Monster**|**Full**|**Any**|**Full**|**Any**|**Full**||**Any**||
|1|Gravedigger|18|35|38|-|50||-||
|1-2|Tomb Rat|16|33|36|48|50||-||
|1-2|Devil Kin Brute|20|36|40|-|50||-||
|1-2|Firebat|18|33|37|48|50||-||
|3-4|Hellbat|25|38|44|-|50||-||
|1-2|Skullwing|22|36|41|-|50||-||
|3-4|Bone Demon|28|39|47|-|50||-||
|1-2|Lich|21|34|40|49|50||-||
|3-4|Arch Lich|26|39|45|-|50||-||
|1-2|Satyr Lord|22|37|41|-|50||-||
|2-3|Crypt Demon|23|37|42|-|50||-||
|3-4|Biclops|26|39|45|-|50||-||
|3-4|Flesh Thing|25|37|44|-|50||-||
|3-4|Reaper|30|39|48|-|50||-||

### 5.6.4 Monster levels

Below follows lists of all monsters in the order of their mlvl. Of course, on nightmare difficulty all mlvl are 15 higher and on hell difficulty they are 30 higher.

**Diablo**

||**Monster**|**mlvl**|**Monster**|**mlvl**|**Monster**|**mlvl**|**Monster**|**mlvl**||
| :- | :- | :-: | :- | :- | :- | :- | :- | :-: | :- |
||Fallen One|1|Shadow Beast|6|Magma Demon|13|Death Wing|23||
||Skeleton|1|Blink|7|Blood Stone|14|Fire Drake|23||
||Zombie|1|Burning Dead Ar.|7|Mud Man|14|Black Knight|24||
||Corps Axe|2|Dark One|7|Night Clan|14|Maelstorm|24||
||Ghoul|2|Bone Gasher|8|Mud Runner|15|Succubus|24||
||Scavenger|2|Flesh Clan|8|Poison Spitter|15|Vortex Lord|24||
||Skeleton Captain|2|Horror Captain|8|Hell Stone|16|Counselor|25||
||Carver|3|Gloom|9|Toad Demon|16|Gold Viper|25||
||Fiend|3|Horror Archer|9|Frost Charger|17|Lava Maw|25||
||Skeleton Archer|3|Stalker|9|Lava Lord|18|Balrog|26||
||Burning Dead|4|Winged-Demon|9|Red Storm|18|Doom Guard|26||
||Corpse Captain|4|Overlord|10|Blood Claw|19|Snow Witch|26||
||Plague Eater|4|Stone Clan|10|Obsidian Lord|19|Azure Drake|27||
||Rotting Carcass|4|Acid Beast|11|Flayed One|20|Magistrate|27||
||Corps Bow|5|Unseen|11|Slayer|20|Hell Spawn|28||
||Devil Kin|5|Fire Clan|12|Storm Rider|20|Steel Lord|28||
||Hidden|5|Familiar|13|Cave Viper|21|Cabalist|29||
||Black Death|6|Gargoyle|13|Pit Beast|21|Advocate|30||
||Burning Dead Cp.|6|Horned Demon|13|Guardian|22|Blood Knight|30||
||Horror|6|Illusion Weavers|13|Storm Lord|22|Soul Burner|30||

|<a name="page136"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**||||**Created by Pedro Faria**|||||
| :- | :- | :- | :- | :- | :- | :- | :- | :- |
||||||||||
|**Hellfire**|||||||||
|**Monster**|**mlvl**|**Monster**|**mlvl**|**Monster**|**mlvl**|**Monster**|**mlvl**||
|Lashworm|20|Hellboar|23|Lich|25|Hellbat|29||
|Arachnon|22|The Shredded|23|Gravedigger|26|Arch Lich|30||
|Felltwin|22|Firebat|24|Devil Kin Brute|27|Biclops|30||
|Hork Spawn|22|Necromorb|24|Skullwing|27|Bone Demon|30||
|Psychorb|22|Spider Lord|24|Crypt Demon|28|Reaper|30||
|Stinger|22|Tomb Rat|24|Flesh Thing|28||||
|Torchant|22|Venomtail|24|Satyr Lord|28||||

### 5.6.5 Monster types

In the table below is listed in summary what type of monster, animal, undead or demon, each monster in the game belong to.

|**Animals**|**Undead**|**Demons**|
| :- | :- | :- |
|Fallen Ones|Skeletons|Balrogs|
|Hell Spawns1|Skeleton Archers|The Butcher|
|Horned Demons|Skeleton Captains|Diablo|
|Scavengers|Skeleton King|Familiars2|
|Spitting Terrors|Zombies|Gargoyles|
|Winged Fiends3|Arch Lich|Goat Men|
|Arachnon|Bone Demons|Goat Men Arch.|
|Devil Kin Brute|Gravedigger|The Hiddens|
|Firebat|Lich|Knights|
|Hellbat|The Shredded|Lightning Demons|
|Lashworm|Skullwings|Mages|
|Necromorb||Magma Demons|
|Psychorb||Overlords|
|Satyr Lord||Succubbi4|
|Spider Lord||Vipers|
|Stinger||Biclops|
|Tomb Rat||Crypt Demon|
|Torchant||The Defiler|
|Venomtail||Felltwin|
|||Flesh thing|
|||Hellboar|
|||Hork Demon|
|||Hork Spawn|
|||Na-Krul|
|||Reaper|

1. In Hellfire only, in Diablo they are demons. All other type of Succubi are demons.
1. All other Winged Fiends are animals.

1. With the exception of Familiars which are demons.

1. With the exception of Hell Spawns in Hellfire which are animals.


# 6. Battle

This chapter will try to explain in more detail all the steps of combat between players and monsters. It will thus also serve as a summary of all the various information and formulas throughout the guide that handle combat. Information in this chapter can generally all be found in other chapters. It is thus advisable to read this chapter together with the rest of the guide, as other chapters may have additional information that clarifies any situation.

As melee is treated differently than other attacks by the game, so will this chapter do (normal arrows are treated the same as spells). There is also quite a difference in who is the attacker and who is the target. There are four different situations, and this chapter will try to explain each of them.

Player versus Monster

Monster versus Player

Player versus Player

Monster versus Monster

Monster versus Monster is mainly about the golem, but in Hellfire it also takes care of berserk monsters. Traps are also treated as monsters in this chapter; that is, if a trap hits a player, it is explained under Monster versus Player.

As players are always updated before monsters, the player will always get in a hit first, should a monster and a player both hit at the same time. For players, the order would be in the order they have entered a game (with the exception that if someone leaves a game, a new player will take that one’s place in the order). The order of updating is as follows:

1. Players

1. Monsters
1. Magical effects (includes arrows)

The update is done once every 0.05 seconds which explains why all timing information is given in steps of 0.05 seconds.


## 6.1 General information

Before we start discussing the actual combat, it is good to know some basic information about how players and monsters function. Each monster and player can exist in one of several possible states. Such states include things like walking, standing, attacking, casting spells, doing a hit recover, being stoned, and dying. A character or monster must finish the current action before it can start a new one. An exception to this is when you get hit. A hit will generally abort your or the monster’s current action, and if the damage is high enough, put the victim into hit recovery (or if even greater into dying mode). Players, but never monsters, can also be put into a blocking state if carrying a shield. For information about how long it takes to do various actions, see chapter 2.3 for players and chapter 5.3.4 for monsters.

The detailed information below will generally be given as a numbered list which one steps through, step by step. At some points there will be notes that certain steps are skipped under some conditions or are only done in specific cases. It is therefore wise to read through all of the part that applies to the situation before drawing any conclusions as some actions are only valid if some specific conditions, which may be presented later, are met.

Most combat situations can be divided into a few specific main steps:

A. Pre-hit	This checks for things like if the target in question is really possible as a target. A

player is, for example, mostly immune to attacks from himself, and monsters are similarly also immune to attacks from other monsters. It also includes checks if a target is available at all. For example, a bow may lose durability even if there is no target present, but for a melee weapon to lose durability it actually needs to hit something. This step will generally *not* be discussed here as it is quite uninteresting as a player of the game, but some things actually done in this step have instead been included in other steps.

B. To Hit	Here the game checks for the probability of hitting to see if a hit is really

acquired. If no hit is acquired, the next steps are generally not done.

C. Blocking	When a player is hit, the game will check if he or she managed to block the

attack or not. If a block was done, the Damage step is generally skipped.

D. Damage	Here the game will calculate the damage and take into consideration all the

applicable modifications. It will also deal the damage to the target.

E. Hit consequences	This will do all the necessary checks for things that will affect both the target

and the attacker if a hit occurs. This includes checks for hit recovery, life and mana stealing, death, and so on.

Some or all the steps above may be performed when an attack is done, and there might be additional steps not mentioned above under some circumstances.

There are also some steps done only in Hellfire or only in Diablo, in that case this is clearly mentioned at the start of the step in italic.


### 6.1.1 Mana Shield

Mana Shield is a spell that causes damage to your life to be taken instead from your mana. In the process it will also reduce the amount of damage taken. To avoid confusion on how the Mana Shield spell affects combat, it will be described in detail here. For information about such things like mana cost and requirements to read books, see chapter 4.

As already said, Mana Shield is a magical effect, and as such, it is handled in the step when all other magical effects are handled (see above) although it is processed after all other effects. It is very important to realize that the Mana Shield *never* affects any combat directly; that is, any attack, be it magical or melee, will be carried out normally and *will* do any damage to your life. Any attack will also put the target into any applicable status such as hit recovery or dying. It is not until the game processes the magical effects and reaches the Mana Shield that it actually changes the normal course of action. Unfortunately, as explained below, this will result in some bugs regarding the player status.

So, lets see in more detail how the Mana Shield works.

1. check if the player’s current life has changed since last time; if not, exit

1. if the current life has increased since last time, set the new increased life as the value to be checked for in the future and then exit

1. calculate the decrease in life since last time, this is the damage taken since last time
1. if slvl=0, skip step 5 and 6
1. *in Diablo*, calculate damage - [damage/3]
1. *in Hellfire*, calculate damage - [damage/(3×slvl)] (if slvl is higher than 7, set slvl to 7)
1. restore current life to its initial value
1. remove the amount calculated in step 5 or 6 from current mana
1. if mana has not reached 0, then if the player was previously in dying mode, set player into standing mode, finally exit

1. if mana has reached 0 or gone below 0, set it to 0 and reduce life with the amount that was below 0
1. terminate the Mana Shield
1. if life has not reached 0, then if the player was previous in dying mode set player into standing mode, finally exit

1. set player into dying mode

As can be seen from the above, if the player was set to dying mode during the normal attacks, it will be put into standing mode by the Mana Shield, and thus avoid, for example, hit recovery, which would in some cases had been the more correct mode. It also prevents knock backs as it is not checked in the normal attack routines if the player died. Finally, it avoids any further attacks done in the last turn while the player was dead. An example of this would be if 3 monsters hit you all at the same time; the first one kills you, and the other two monsters’ attacks are then not done as you are already dead. Later in the turn when the magical effects are processed, the Mana Shield restores your life, reduces the damage from mana instead, and puts you back into life. You have then effectively avoided the attack from the last two monsters. This does not happen too often, as the attacks of the monsters need to be done at the *exact* same time.

In Hellfire, there are some additional bugs related to the Mana Shield (those bugs were fixed in Diablo, version 1.07). When you run out of mana, and the Mana Shield is terminated, you will take excessive damage (up to twice the damage of the latest attack). It is also possible to cast more than one Mana Shield and although this will not affect the efficiency of the Mana Shield, you will take excessive damage from *each* Mana Shield when you run out of mana and all the Mana Shields are terminated.


### 6.1.2 Fire Wall, Flame Wave and Ring of Fire

Fire Wall and Flame Wave are special in that they are the only spells that can hurt the caster of the spells. They are also special in that when attacking players (including the caster), they will attack as if they where magic traps, that is, the To Hit is always 40%. When attacking monsters, they will use the normal To Hit calculations.


### 6.1.3 Reflect

Actually, the Reflect spell is handled properly in the step by step lists later on. I just wanted to mention that Reflect, contrary to Mana Shield, is handled within the actual damage routines by a flag set on the character. If set, the damage will be reduced properly and reflected back to the monster. This is how the Mana Shield should have been implemented to avoid all the problems and bugs associated with it.


### 6.1.4 Life and Mana stealing

Items with the effect of life stealing and mana stealing work independently of each other. An item with the 5% stealing will always supersede the 3% stealing and they are thus *not* cumulative (you can still have one item with 3% mana stealing and one with 5% life stealing though). Similarly, two items with 3% stealing or two with 5% stealing are not cumulative either.

The random life stealing effect only found on The Undead Crown *is* cumulative with other life stealing though as it is handled separately from normal life stealing. Life and mana stealing only work against monsters, never against players (the exception is the random life stealing, but as The Undead Crown only exists in single player it doesn’t matter).

The table below summarizes the end result when you have two items of life or mana stealing. If there is any way to get three items with life or mana stealing, simply do it as a two step process, first checking two of the items, then take the end result and check it with the third effect.

||**3% mana**|**5% mana**|**3% life**|**5% life**|<b>random life<sup>1</sup></b>|
| :- | -: | -: | -: | -: | -: |
|**3% mana**|3% mana|5% mana|3% mana|3% mana|3% mana|
||||3% life|5% life|0-12.5% life|
|**5% mana**|5% mana|5% mana|5% mana|5% mana|5% mana|
||||3% life|5% life|0-12.5% life|
|**3% life**|3% mana|5% mana|3% life|5% life||
||3% life|3% life|||3-15.5% life|
|**5% life**|3% mana|5% mana|5% life|5% life||
||5% life|5% life|||5-17.5% life|
|<b>random life<sup>1</sup></b>|3% mana|5% mana||||
||0-12.5% life|0-12.5% life|3-15.5% life|5-17.5% life|0-12.5% life|

1	Steals a random amount of life between 0 and 12.5% each time you hit.


### 6.1.5 Fire and Lightning damage on melee weapons

When you do an attack that does additional fire or lightning damage, this will be handled by the game separately. Upon hit (even if the actual attack misses), the game will spawn an additional magical effect of the appropriate type, which will then be handled normally during the magical effect update. When hitting, the effect will use normal magical To Hit, and all resistance and other effects that normally work against magic apply normally. It will then deal the amount of fire or lighting damage your character currently does. The magical effect will only hit once but it will try to hit up to 7 times (9 if fire) before it ends.


### 6.1.6 Fire and Lightning damage on bows

Fire and lightning attacks on bows work pretty much the same as the ones on melee weapons. There are some exceptions. As arrows to start with are already effects, there is no need to spawn a special effect for the extra fire and lightning damage like there is for melee weapons. Instead, as soon as the fire or lightning arrow hits and has done its non magical damage, the effect will switch into a fire or lightning damage attack, quite similar to the one spawned for melee attacks. This extra fire or lightning attack will, as opposed to with melee attacks, hit more than once and will try 7 times (9 if fire) before it ends. Any extra fire or lightning damage from any item other than the bow will be added despite the fact that this is a ranged attack.

Fire and lightning arrows are quite buggy and the list below tries to summarize some of the bugs related to them.

- The to hit calculations for the fire and lightning attack part, although magical, still use normal arrow to hit formulas.
- The fire and lightning damage is *not* halved for player versus player like all other magical damage is.

- Unlike melee fire and lightning damage, they can hit and deal damage more than once. This might not be a bug but probably is.

- Damage calculations for the fire and lightning part still include the normal character damage and will even apply such modifiers as +% damage to the fire and lightning damage. Basically, the damage range of the fire and lightning damage is treated as the ”bow damage range” and thus modified as appropriately for a normal arrow attack.

- Despite what is said above, both monsters and players *will* resist the damage if they have resistance to the appropriate magic type (fire or lightning).

- The actual fire and lightning damage will often not hit the same place as the arrow did, meaning one will often escape the extra high damage caused by fire and lightning bows. {blockable?}

Note that in the chapters below, the bugs regarding fire and lightning arrows will not be mentioned. The list above should be sufficient for knowing the end effects.


### 6.1.7 Charge attacks

Charges are special in that they are treated as magical effects while the actual charge is conducted; that is, the monster moves during the effect update phase, but as soon as it hits, it turns into an almost normal melee attack. Below are listed what special conditions apply to Charge attacks.

- A Gloom will never attack with its charge, it simply uses it as a mean of transportation.

- The base to hit of the monster charge attack is 500%, this is then modified normally according to chapter 6.2.3.
- Blocking is handled normally for a charge attack, and so is damage.

- Vipers will never put a target into hit recovery.

- Horned Demons and other monsters that get the special charge ability (unique monsters and their party) will automatically put a target into hit recovery upon hit and will also knock back the target.

Either intentionally or due to a bug, monsters that are charging, can at times cross lava that is otherwise impassable in the caves.


### 6.1.8 How spells really work

Before we go into detail about the actual attacks, it might be good to learn some basic information on how the game handles spells. This chapter will try to briefly explain this so that it not only gets easier to understand the chapter about non-melee attacks, but also how spells really work. Non-melee attacks are basically magic in nature. An exception is arrows, but think of them as any other projectile, like fireball, and you will see that there is really not much difference. Each spell or missile in the game is an effect, and in the effect update procedure each effect is processed and can do a number of things.

Easiest to understand are the missile spells, the ones like Fireball, Charged Bolt, or Holy Bolt. They are basically an effect that moves around in the dungeon at a certain speed and often in a straight line. As soon as it enters a location it checks if it contains a potential target (monsters are immune to other monsters and players are often immune to their own spells and so on). If there is a potential target, it will try to attack, and it is this attack this chapter on Battle will explain in more detail. It will also check if it has hit a wall or some other dungeon feature and, if so, terminate.

Some spells like Elemental and Flame Wave (which are in fact several flames, each an effect, moving side by side) will not terminate if they hit a target like a Fireball does. They will, regardless of if they hit or not, continue to move, and can thus hit multiple targets. Some spells consist of multiple missiles, such as Nova and Charged bolt. A Fire Wall is a typical example of a spell that can hit a target repeatedly.

Sometimes a spell can actually consist of several effects. The Lightning spell is such an example. The main spell is totally invisible and starts at the position of the source and travels away at a certain speed (see chapter 4.1.2). Each time it enters a new location it will spawn a new effect, a non moving lighting bolt with a certain duration that will sit in the location and try to hit anything in the location until its duration is over at which time it is removed. As the individual bolts are spawned with a certain delay the further away they are from the original source, they will also disappear with the same delay. The total effect is a seemingly moving stream of lighting bolts when in fact it is stationary bolts, where the duration of the individual bolts determines what looks like the length of the lighting stream. The speed of the stream is actually the speed of the initial invisible moving spell effect that spawns the bolts. Many other spells work in a similar way.

As already said, a spell can either be terminated upon hitting or go on even if it hits. In addition to that, most spells have a duration after which they will also be terminated. Most missile spells will also be terminated when they hit a wall or other dungeon feature. In addition to the above, each effect, when it attacks, can be set to be blockable or not. The check for blocking will only be done for those spells that are blockable. See chapter 4.1.2 for information about blockable spells. Finally, each effect can be either Fire, Lightning, Magic, or other (arrows are special).

Some effects will, of course, never attack; examples of such effects are Mana Shield and Infravision.


### 6.1.9 Possible targets of attacks

As already explained, an attack will typically always hit a specific location (with some exceptions). Normally, only a single monster or player can occupy a location at any time (although, due to bug, at times a monster and a player may end up in the same location, this is usually due to using the Teleport or Phasing spell). As long as a monster or a player is not moving between locations, it is always attackable in the location it occupies, regardless of what it do. Some activities will make the monster or player not hitable, but that is a different matter, examples of such things are an Illusion Weaver retreating, a player during the first 0.5 seconds upon entry of a new dungeon level. But what about when a monster or a player is walking between two locations. Where can it be attacked? The answer is that it depends on the type of attack and the direction of the walk. In the table below are listed all the various cases that may exist. It also tells in what location the monster or player is put in case the walk is interrupted, that is, when the target go into a hit recovery.

|||<b>Target locations depending on direction of walk of target<sup>1</sup></b>|||
| :- | :- | :- | :- | :- |
|**Situation**|<b>NW, N or NE<sup>2</sup></b>|<b>SW, S or SE<sup>2</sup></b>|<b>W or E<sup>2</sup></b>||
|Player attack monster in melee|Both|Both|Both||
|Player attack player in melee|Both|Both|Both||
|Monster attack player in melee|Special|Special|Special||
|Monster attack monster in melee|Both3|Both3|Both3||
|Spells4|attacking player|Leaving|Entering|None|
|Spells4|attacking monsters not Stone Cursed|Both|Both|Both|
|Spells4|attacking monsters Stone Cursed|Leaving|Entering|None|
|Fire Wall, Flame Wave or Ring of Fire|Leaving|Entering|None||
|attacking player or monster|||||
|Hit recovery location for player|Leaving|Entering|Leaving||
|Hit recovery location for monster|Leaving|Leaving|Leaving||
|Location used for distance calculations|Leaving|Entering5|Leaving||

1. *Both* means that the target can be hit in both the location he is leaving and the location he is entering, *leaving* means that the target can only be hit in the location it is leaving, *entering* means that the target can only be hit in the location it is entering, *none* means that it can’t be hit in any of the locations. Monsters attacking players are handled in a special way explained below.
1. For the definition of north, see chapter 1.3.

1. A monster that attack another monster will always check for To Hit no matter where the target is at the time to check for To Hit. A monster will never initiate a melee attack unless the target at that time is in an adjacent location which means that usually it can hit in both locations and in addition further away in the rare occasions that the target has managed to get further away.

1. Excluding Fire Wall, Flame Wave and Ring of Fire.

1. Distance to a golem is measured to the Leaving location.

Monsters attacking players in melee does not specifically check for the location of the attack. Instead, upon attack it will check for the distance from the monster to the player. The locations used to calculate the distance is for the monster the location it is occupying and for the player it depends on the direction it is walking. When walking W, NW, N, NE or E, it is always the location the player is leaving and while walking SW, S or SE it is always the location the player is entering.

This has some important consequences that it is good to know about. When walking away from a monster it will thus always miss the check for the To Hit is done after you have started walking downwards on the screen and it will always have a normal chance of hitting you until you have completely reach your new location while walking upwards or sideways from the monster. Further more, if the walk is aborted by an attack, the player will be put in the location as indicated in the table above which means if you walk downwards, you will in such cases always be ”pushed” downwards (regardless of the direction of the attacker) but when walking in other directions, you will be ”pushed” back into the location you were leaving. Further more, when deciding upon what action to perform, see chapter 5.5 the distance is similarly always calculated in the same way. This result in the situation that when you are walking towards a monster it will only initiate a melee attack while you are walking, if you are walking SW, S or SE. If you walk in any other direction towards the monster it will consider you non adjacent up until you have reached the location adjacent to the monster.

Finally, as it is the distance from the monster to the player that counts when a monster attack a player, a monster will always check for To Hit against a player in those cases they occupy the same locations (can happen due to a bug) but a player will only be able to hit an adjacent location when doing a melee attack and can thus not attack the monster within its location.


### 6.1.10 Spell and arrow speeds

In the rest of the Guide, the speed of spells and arrows are given with a number in the 16 - 63 range (rarely going below 8). Here, a brief description is made in an attempt to convert those speeds to real speeds in the dungeon measured in reference to the tiles in the dungeon. This is also useful for estimating the distance penalty of arrows.

Any missile in the game (be it an arrow or a spell) will use true trigonometrical calculations for its movement, both for location and speed. Thus, it takes a missile longer to move through a location diagonally than straight along a side (roughly 40% longer) as opposed to character and monster movement which takes the same time regardless of it being diagonally or not. In addition, missiles actually move in small jumps each frame. That is, depending on their speed, they will move a certain distance each frame. For the purpose of keeping track of missiles, the game actually uses 22 extra bits of precision for its location, think of it as each location actually being divided in roughly 92 680 times 92 680 smaller locations. This higher precision is used for smooth movement *only*, for actual To Hit purposes the missile is simply considered to be in one location, regardless of where in the location it is. This have a few implications though. If the distance a missile is moved each frame is smaller than a location, it may end up staying in a location for more than one frame. In addition, it may, when not moving in straight angles along the locations, only enter the corner of some locations and may thus never really exist in a location that it in fact should pass through (for movement straight along the locations, this should never happen as it requires a speed value above 64 which does not exists in the game).

Some missile types prevents trying to hit the same location more than once (should it not manage to move into a new location when updated each frame) while most do not and may thus try to hit a target in a location more than once. This will of course make the total chance of hitting a target somewhat higher than it should be. This phenomenon is not that uncommon but extremely hard to predict or give exact numbers on as it depends both on the exact speed of the missile and in what direction you fire it. As you can virtually fire a missile in any direction, the possibilities are numerous. One should be aware of this phenomenon though as it might affect the result if anyone would actually measure the actual hit percentages of missiles.

To calculate the distance a missile of a specific speed travels, only examples of movement straight along the locations in the dungeon will be considered. It should be easy to apply to movement in any direction with true trigonometry. A missile with a speed value of 64, will travel exactly diagonally through one location each frame. This corresponds to traveling 1.4 locations in a straight line along the locations side. Alternatively you may say that a speed of 45.3 travels a location in one frame straight along the side of a location. The distance traveled per second can thus easily be calculated as:

Locations a missile travel per second:	25×speed/45.3

As the distance penalty of an arrow is increased by 1 each frame, the total distance penalty per location (see chapter 2.1.4 and 5.1 for more information) can be calculated as:

For characters:	distance×distance/2 = (45.3/speed)×(45.3/speed)/2 = 1 048/(speed×speed)

For monsters:	distance×distance = (45.3/speed)×(45.3/speed) = 2 048/(speed×speed)

As noted, for some locations, the fact that the missile will try to hit more than once may make the actual To Hit be slightly different. Also note that a missile will actually start traveling in the location where the player or monster it originates from is currently standing in. It may at times take more than one frame to reach the next location but in no case will a missile make a To Hit check in its location of origin.


### 6.1.11 Some general notes about the formulas

In most cases it should be obvious from whom the stat in a formula should be taken. Monsters do not have Dex or clvl for example. In some cases, for example with players attacking players or when there is some bonus, it might not be so obvious and there is an additional note telling if it is from the target or the attacker (or if it is for the monster or player as appropriate). This is also done when it is not obvious what value should be used, for example if it is a base To Hit or a modified To Hit.

Any part of the formula that is only applicable in Hellfire is shown in italic.



## 6.2 Melee attacks

Here we will only discuss melee attacks; this does *not* apply to attacks with bows, and is always done to an adjacent target.


### 6.2.1 Player versus Monster

**To Hit**

1. if the target monster is an Illusion Weaver that is currently running away, exit as it is at the moment immune to any attack
1. if the target monster is Stone Cursed, the attack is an automatic hit, go directly to damage calculations
1. calculate 50 + Dex/2 + ToHititems + clvl + bonusplayer

1. *in Hellfire*, if the player has any item with the ”penetrate armor” effect, temporarily reduce Acmonster as appropriate
1. subtract Acmonster

1. *in Hellfire*, if the attack is an adjacent quarter damage attack, subtract 70 - 2×clvl (minimum 30)
1. if the value calculated is below 5, set it to 5
1. if the value calculated is above 95, set it to 95
1. the value now achieved is the final chance to hit (FTH)
1. a hit is secured if Rnd[100] < FTH

The steps 3-8 above can be summarized to:

FTH = 50 + Dex/2 + ToHititems + clvl + bonusplayer - Acmonster *- penaltyquarter damage*

- *In Diablo*, ToHititems includes the effect of items with the ”penetrate armor” effect.

- The bonusplayer is 20 for Warriors and 0 for all other classes.

- penaltyquarter damage only apply to certain attacks in Hellfire, see chapter 2.2.2 for more information.

- Note that if FTH is below 5 or above 95 it is adjusted to 5 and 95. This is commonly referred to as the auto hit and auto miss of a character.

**Damage**

1. calculate Rnd[maxbase weapon damage - minbase weapon damage + 1] + minbase weapon damage (this is basically a random value within the weapons base damage range)
1. add +% damage

3. add +damage

3. add character damage
3. if the attacker is a Warrior or Barbarian then double damage if Rnd[100] < clvl (critical hit)
3. if the monster is undead or an animal, adjust the damage according to the table in chapter 5.1 under monster type, that is, under certain circumstances multiply damage by 1.5 or divide damage by 2

3. if the monster is a demon, triple the damage if the player is carrying any item with the ”+200% damage versus demons” effect

3. *in Hellfire*, if the attacker has an item with the devastation effect and Rnd[100] < 5, triple the damage
3. *in Hellfire*, if the attacker has an item with the jester’s effect 50% of the time multiply damage by Rnd[100]/100, the other 50% multiply damage by 5×(Rnd[100]+20)/100

3. *in Hellfire*, if the attack is an adjacent ”quarter” damage attack, divide the damage by 4 (hence the ”quarter” damage)

3. *in Hellfire*, if the attacker has an item with the peril effect, double the damage
3. the value now achieved is the final damage (FD)
3. deal FD to the target

Steps 1-4 above will generate a damage value that is within the range shown for damage on the character screen.

Steps 5-12 above will further modify the damage by factors that will not be shown on the character screen.

Step 9 above is actually done as:

1. calculate Rnd[200]

1. if the value is below 100 multiply the damage by this value and then divide by 100
1. otherwise subtract 80 and multiply by 5, then multiply the damage by this value and divide by 100

**Hit consequences**

1. *in Hellfire*, if the attacker has an item of doppelganger’s effect and the monster is not Diablo or an unique monster, duplicate the monster if Rnd[100] < 5
1. *in Hellfire*, if the attacker has an item with the peril effect, take the damage from step 3 under Damage above, modify it for the -damage effect and deal it to the attacker

1. if the attacker has an item equipped that has the ”random life stealing” effect, calculate Rnd[FD/8] and add this to current life (while checking so that current life never exceeds max life)

1. if the attacker has an item equipped that has 3% mana stealing, calculate 0.03×FD
1. if the attacker has an item equipped that has 5% mana stealing, calculate 0.05×FD
1. if the attacker do *not* have any item of *corruption* add the amount calculated in step 4 or 5 to the current mana (while checking so that current mana never exceeds max mana)

1. if the attacker has an item equipped that has 3% life stealing, calculate 0.03×FD
1. if the attacker has an item equipped that has 5% life stealing, calculate 0.05×FD
1. add the amount calculated in step 7 or 8 to the current life (while checking so that current life never exceeds max life)

1. *in Hellfire*, if the attacker hit and has an item equipped with the decay effect, subtract 5 from its To Hit bonus, if it reaches -100%, destroy the item

1. if the attacker hit, check for weapon durability loss
1. if the monster was *not* Stone Cursed and the player had an item with the ”knock back” effect, move the monster one step backwards (backwards is defined according to the monster’s facing)

1. mark the attacker to be entitled to experience points when the monster dies
1. if the target was not a golem and it was not resistant to the spell and FD >= mlvl+3, put monster into hit recovery; a Scavenger or Grave Digger will also be set in a mode to find a carcass to feast/dig upon

1. if the target was a Hidden type of monster and it was not resistant to the spell, put monster into hit recovery as well as in retreat mode (see chapter 5.5.9 under Hidden).

1. if the monster died, check for any item dropping (see chapter 3.8) and add any experience to the players that are eligible for it (see chapter 2.6)

1. if the monster died and it was Diablo, terminate game and show ending movie for players on dlvl 16

### 6.2.2 Player versus Player

**To Hit**

1. calculate 50 + Dexattacker/2 + ToHititems,attacker + clvlattacker + bonusattacker

1. calculate Dextarget/5 + Acitems,target + bonustarget
1. subtract the value in step 2 from the value in step 1

4. if the value calculated is below 5, set it to 5

4. if the value calculated is above 95, set it to 95
4. the value now achieved is the final chance to hit (FTH)
4. a hit is secured if Rnd[100] < FTH

The steps 1-6 above can be summarized to:

FTH = 50 + Dexattacker/2 + ToHititems,attacker + clvlattacker + bonusattacker - Dextarget/5 - Acitems,target - bonustarget

- *In Diablo*, ToHititems includes the effect of items with the ”penetrate armor” effect.

- The bonusattacker is 20 for Warriors and 0 for all other classes.

- The bonustarget is clvl/4 for Barbarians, depends on the armor type for Monks (0 for non unique plate, clvl/2 for non unique mail or unique plates and 2×clvl for light armor and unique mail or if naked), and 0 for all other classes.

- Note that if FTH is below 5 or above 95 it is adjusted to 5 and 95. This is commonly referred to as the auto hit and auto miss of a character.

**Block**

1. if the target is doing anything other than standing still or performing a melee attack, skip blocking

1. if the target is not a Monk and is not carrying a shield, skip blocking
1. if the target is a Monk and is not carrying a shield, a staff or has at least one hand bear, skip blocking
1. calculate Dextarget + 2×clvltarget + bonustarget

1. subtract 2×clvlattacker
1. if the value calculated is below 0, set it to 0
1. if the value calculated is above 100, set it to 100
1. the value now achieved is the final chance to block (FB)
1. a block of the attack is done if Rnd[100] < FB

The steps 3-8 above can be summarized to:

FB = Dextarget + 2×(clvltarget - clvlattacker) + bonustarget

- The bonustarget is 30 for Warriors and Barbarians, 25 for Monks and Bards, 20 for Rogues, and 10 for Sorcerers. Note that there seems to be a bug that makes all those bonus values be 0.
- It is possible to achieve 100% blocking.

**Damage**

1. calculate Rnd[maxbase weapon damage - minbase weapon damage + 1] + minbase weapon damage (this is basically a random value within the weapons base damage range)
1. add +% damage
1. add +damage
1. add character damage
1. if the attacker is a Warrior or Barbarian then double damage if Rnd[100] < clvlattacker (critical hit)

1. the value now achieved is the final damage (FD)
1. deal FD to the target

Steps 1-4 above will generate a damage value that is within the range shown for damage on the character screen.

Steps 5-6 above will further modify the damage by factors that will not be shown on the character screen.


**Hit consequences**

1. if the attacker has an item equipped that has the ”random life stealing” effect, calculate Rnd[FD/8] and add this to current life (while checking so that current life never exceeds max life). It is worth noticing that in normal Diablo, the random stealing effect is *only* present on a single player quest item, so this step is this never performed.
1. *in Hellfire*, if the attacker hit (regardless of blocking) and has an item equipped with the decay effect, subtract 5 from its To Hit bonus, if it reaches -100%, destroy the item

1. if the attacker hit (regardless of blocking), check for weapon durability loss

4. if the attacker hit and the target did not block, check if life went down to 0 or below, if so put target player into death mode and skip further steps

4. if FD >= clvltarget and the target did not block then put target player into hit recovery and check for durability loss on helm and armor

4. if the target blocked, put target player into block mode and check for durability loss on shield

For the probabilities of durability losses, see chapter 3.7.1.


### 6.2.3 Monster versus Player

**To Hit**

1. calculate 30 + ToHitbase,monster + 2×mlvl

1. calculate Dex/5 + Acitems,player + bonusplayer + 2×clvl
1. subtract the value in step 2 from the value in step 1
1. *in Hellfire*, if the player has extra AC versus Demons or Undead, subtract 40/20 if the monster is of the correct type

1. if the value calculated is below 15, set it to 15
1. on dlvl 14 if the value calculated is below 20, set it to 20
1. on dlvl 15 if the value calculated is below 25, set it to 25
1. on dlvl 16 if the value calculated is below 30, set it to 30
1. the value now achieved is the final chance to hit (FTH)
1. a hit is secured if Rnd[100] < FTH

The steps 1-9 above can be summarized to:

FTH = 30 + ToHitbase,monster + 2×(mlvl-clvl) - Dex/5 - Acitems,player - bonusplayer

- ToHitbase,monster is the value found in the tables for each monster in chapter 5.2 and 5.4. For the second attack of Magma Demons it is 10 higher, and for the second attack of Lightning Demons it is 20 lower. For charges the base value is always 500%.

- For unique monsters, use mlvlbattle

- The bonusplayer is clvl/4 for Barbarians, depends on the armor type for Monks (0 for non unique plate, clvl/2 for non unique mail or unique plates, and 2×clvl for light armor and unique mail or if naked), and 0 for all other classes.

- Note that the FTH is adjusted for auto hit values.

**Block**

1. if the target is doing anything other than standing still or performing a melee attack, skip blocking

1. if the target is not a Monk and is not carrying a shield, skip blocking
1. if the target is a Monk and is not carrying a shield, a staff or has at least one hand bear, skip blocking
1. calculate Dex + 2×clvl + bonusplayer

1. subtract 2×mlvl
1. if the value calculated is below 0, set it to 0
1. if the value calculated is above 100, set it to 100
1. the value now achieved is the final chance to block (FB)
1. a block of the attack is done if Rnd[100] < FB

The steps 3-8 above can be summarized to:

FB = Dex + 2×(clvl - mlvl) + bonusplayer

- The bonusplayer is 30 for Warriors and Barbarians, 25 for Monks and Bards, 20 for Rogues, and 10 for Sorcerers. Note that there seems to be a bug that makes all those bonus values be 0.
- For unique monsters, use mlvlbattle

- In the cases according to step 1-2 above when a block is not checked, the game actually DOES a random check, but the value checked against is 100 and thus will never result in a block.
- It is possible to achieve 100% blocking.


**Damage**

1. calculate Rnd[maxbase damage - minbase damage + 1] + minbase damage (this is basically a random value within the monsters base damage range)
1. add -damage
1. if damage is below 1, set it to 1
1. *in Hellfire*, if the player has a Reflect spell running, calculate the final reflected damage (FRD) by multiplying the damage by (Rnd[10] + 20)/100

1. *in Hellfire*, if the player has a Reflect spell running, subtract FRD from the damage calculated in steps 1-3
1. the value now achieved is the final damage (FD)
1. deal FD to target

**Hit consequences**

1. *in Hellfire*, if the monster hits and the player has a Reflect spell running, reflect FRD to it and check for death and hit recovery of the monster normally
1. if the monster hits and it is a Black Death, remove 1 permanently from life
1. if the player has any item equipped that has the ”damage to attacker” effect, deal Rnd[3] + 1 damage to it and check for death and hit recovery of the monster normally

1. if the monster had the knock back ability, move the player one step backwards (backwards is defined according to the player’s facing)

1. if the attacker hits and the target did not block, check if life went down to 0 or below; if so, put target player into death mode and skip further steps

1. if FD >= clvl and the target did not block, put target player into hit recovery and check for durability loss on helm and armor

1. if the target blocked, put target player into block mode and check for durability loss on shield

For the probabilities of durability losses, see chapter 3.7.1.


### 6.2.4 Monster versus Monster

**To Hit**

1. if the target monster is an Illusion Weaver that is currently running away, exit as it is at the moment immune to any attack
1. if the target is a monster that is Stone Cursed, the attack is an automatic hit, go directly to damage calculations

1. the monsters base To Hit will also be the monsters final chance to hit (FTH) so the AC of the target has no effect

1. a hit is secured if Rnd[100] < FTH

**Damage**

1. calculate Rnd[maxbase damage - minbase damage + 1] + minbase damage (this is basically a random value within the monsters base damage range)
1. the value now achieved is the final damage (FD)
1. deal FD to target

**Hit consequences**

1. if the target was *not* Stone Cursed and the attacker had attack type with the ”knock back” effect, move the target one step backwards (backwards is defined according to the target’s facing).
1. if the attacker was a golem, mark the golem’s owner to be entitled to experience points when the monster dies

1. if FD >= mlvltarget+3 or if the target is a Hidden type of monster put target into hit recovery; a Scavenger or Grave Digger will also be set in a mode to find a carcass to feast/dig upon

1. if the target died, check for any item dropping (see chapter 3.8) and add any experience to the players that are eligible for it (see chapter 2.6)

1. if the target died and it was Diablo, terminate game and show ending movie

## 6.3 Non melee attacks

Here we will deal with all other attacks, which include spells, arrows and traps (which are either spells or arrows). As there are so many more possibilities and special cases, some sections have been divided up to handle specific cases.


### 6.3.1 Player versus Monster

**To Hit**

1. if the effect is Holy Bolt and the monster is not undead or Diablo, exit as other monsters are immune

1. if the target monster is an Illusion Weaver that is currently running away, exit as it is at the moment immune to any attack

1. if the monster is immune to the spell type, exit as it can’t be damaged
1. if the target is a monster that is Stone Cursed, the attack is an automatic hit, go directly to damage calculations

1. if the effect is an arrow, calculate 50 + Dex + ToHititems + clvl + bonusplayer - distance×distance/2

1. if the effect is an arrow, subtract Acmonster
1. if the effect is a spell, calculate 50 + Mag + bonusplayer
1. if the effect is a spell, subtract 2×mlvl
1. if the value calculated is below 5, set it to 5
1. if the value calculated is above 95, set it to 95
1. the value now achieved is the final chance to hit (FTH)
1. a hit is secured if Rnd[100] < FTH

The steps 5-11 above can be summarized to:

FTHarrow = 50 + Dex + ToHititems + clvl + bonusplayer - distance×distance/2 - Acmonster FTHspell = 50 + Mag + bonusplayer - 2×mlvl

- The bonusplayer for arrows is 10 for Warriors and Bards, 20 for Rogues, and 0 for all other classes.

- The bonusplayer for spells is 20 for Sorcerers, 10 for Bards, and 0 for all other classes.

- Note that if FTH is below 5 or above 95 it is adjusted to 5 and 95. This is commonly referred to as the auto hit and auto miss of a character.

**Damage**

1. for spells, the actual damage is calculated upon cast. For information about damage ranges for spells, see chapter 4.1.2.
1. if the effect is an arrow, calculate Rnd[maxbase weapon damage - minbase weapon damage + 1] + minbase weapon damage (this is basically a random value within the weapons base damage range)

1. if the effect is an arrow, add +% damage
1. if the effect is an arrow, add +damage
1. if the effect is an arrow, add character damage
1. if the effect is a spell and the monster has resistance, divide damage by 4
1. if the spell is Bone Spirit, damage is [current lifemonster]/3

1. the value now achieved is the final damage (FD)
1. deal FD to the target

Steps 2-5 above will generate a damage value that is within the range shown for damage on the character screen.

Note that in Hellfire, Diablo and Bone Demons have resistance to Holy Bolt.


**Hit consequences**

1. for firing bows, the durability loss check is done regardless of a hit or miss; it is checked each time the character *fires*
1. if the monster was *not* Stone Cursed and the player had a bow with the ”knock back” effect, move the monster one step backwards (backwards is defined according to the monster’s facing)

1. if the attack was done with arrows or by a spell to which the monster was not resistant, mark the attacker to be entitled to experience points when the monster die

1. if the target was not a golem and it was not resistant to the spell and FD >= mlvl+3, put monster into hit recovery; a Scavenger or Grave Digger will also be set in a mode to find a carcass to feast/dig upon

1. if the target was a Hidden type of monster and it was not resistant to the spell, put monster into hit recovery as well as in retreat mode (see chapter 5.5.9 under Hidden).

1. if the monster had no specific target before, set the player as the target, this basically activates a monster that gets hit regardless of distance

7. if the monster died, check for any item dropping (see chapter 3.8) and add any experience to the players that are eligible for it (see chapter 2.6)

7. if the monster died and it was Diablo, terminate game and show ending movie

### 6.3.2 Player versus Player

**To Hit**

1. if the target is immune to the spell type, exit as it can’t be damaged; this is true for spells like Apocalypse and Holy Bolt
1. if the effect is an arrow, calculate 50 + Dexattacker + ToHititems,attacker + clvlattacker + bonusattacker - distance×distance/2

1. if the effect is an arrow, calculate Dextarget/5 + Acitems,target + bonustarget2.1.4

1. subtract the value in step 3 from the value in step 2
1. if the effect is a spell, calculate 50 + Magattacker + bonusattacker

1. if the effect is a spell, subtract 2×clvltarget
1. if the value calculated is below 5, set it to 5
1. if the value calculated is above 95, set it to 95
1. the value now achieved is the final chance to hit (FTH)
1. a hit is secured if Rnd[100] < FTH

The steps 2-9 above can be summarized to:

FTHarrow = 50 + Dexattacker + ToHititems,attacker + clvlattacker + bonusattacker - distance×distance/2 - Dextarget/5 -

Acitems,target - bonustarget

FTHspell = 50 + Magattacker + bonusattacker - 2×clvltarget

- The bonusattacker for arrows is 10 for Warriors and Bards, 20 for Rogues, and 0 for all other classes.

- The bonusattacker for spells is 20 for Sorcerers, 10 for Bards, and 0 for all other classes.

- The bonustarget is clvl/4 for Barbarians, depends on the armor type for Monks (0 for non unique plate, clvl/2 for non unique mail or unique plates and 2×clvl for light armor and unique mail or if naked) and 0 for all other classes.

- Note that if FTH is below 5 or above 95 it is adjusted to 5 and 95. This is common referred to as the auto To Hit and auto miss of a character.

**Block**

1. if the target is doing anything other than standing still or performing a melee attack, skip blocking

1. if the target is not a Monk and is not carrying a shield, skip blocking
1. if the target is a Monk and is not carrying a shield, a staff or has at least one hand bear, skip blocking
1. if the spell type is not blockable, skip blocking
1. if the spell type is blockable but the target has resistance to it, skip blocking
1. calculate block Dextarget + 2×clvltarget + bonustarget

1. subtract 2×clvlattacker
1. if the value calculated is below 0, set it to 0
1. if the value calculated is above 100, set it to 100
1. the value now achieved is the final chance to block (FB)
1. a block of the attack is done if Rnd[100] < FB

The steps 5-10 above can be summarized to:

FB = Dextarget + 2×(clvltarget - clvlattacker) + bonustarget

- The bonustarget is 30 for Warriors and Barbarians, 25 for Monks and Bards, 20 for Rogues, and 10 for Sorcerers. Note that there seems to be a bug that makes all those bonus values be 0.

- In the cases according to step 1-4 above when a block is not checked, the game actually DOES a random check but the value checked against is 100 and thus will never result in a block.
- It is possible to achieve 100% blocking.

- Although a player will block monsters even with resistance in Hellfire, they will never block an attack from another player when having resistance.


**Damage**

1. for spells, the actual damage is calculated upon cast. For information about damage ranges for spells, see chapter 4.1.2.
1. if the effect is an arrow, calculate Rnd[maxbase weapon damage - minbase weapon damage + 1] + minbase weapon damage (this is basically a random value within the weapons base damage range)

1. if the effect is an arrow, add +% damage
1. if the effect is an arrow, add +damage
1. if the effect is an arrow and the attacker is a Rogue, add character damage
1. if the effect is an arrow and the attacker is a Warrior or Sorcerer, add double character damage
1. if the spell is Bone Spirit, damage is [current lifetarget]/3

1. if the effect is a spell, divide damage by 2
1. if the effect is a spell and the target has resistance to it, reduce the damage by the amount specified by the resistance

1. the value now achieved is the final damage (FD)
1. deal FD to the target

Steps 2-5 above will generate a damage value that is within the range shown for damage on the character screen.

Step 6 above will further modify the damage by factors that will not be shown on the character screen. Shown on character screen is normal character damage, not double, for all character classes.


**Hit consequences**

1. for firing bows, the durability loss check is done regardless of a hit or miss; it is checked each time the character *fires*
1. if the attacker hits and the target did not block, check if life went down to 0 or below; if so, put target player into death mode and skip further steps

1. if the target did not block and effect was an arrow or it was a spell and the target had no resistance to the spell type, check if FD >= clvltarget and, if so, put target player into hit recovery and check for durability loss on helm and armor

1. if the target blocked, put target player into block mode and check for durability loss on shield

### 6.3.3 Monster/Trap versus Player

Fire Wall, Flame Wave and Ring of Fire also uses this chapter when attacking players.


**To Hit**

1. if the effect is an arrow from a monster, calculate 30 + ToHitbase,monster + 2×mlvl - 2×distance

1. if the effect is an arrow from a monster, subtract Dex/5 + Acitems,player + bonusplayer + 2×clvl
1. if the effect is an arrow from a trap, calculate 100 - (Dex/5 + Acitems,player + bonusplayer + 2×clvl) / 2 - 2×distance
1. if the effect is a spell from a monster, calculate 40 + 2×mlvl
1. if the effect is a spell from a monster, subtract 2×clvl
1. if the effect is a spell from a trap or a player, set To Hit to 40
1. if the value calculated is below 10, set it to 10
1. on dlvl 14 if the value calculated is below 20, set it to 20
1. on dlvl 15 if the value calculated is below 25, set it to 25
1. on dlvl 16 if the value calculated is below 30, set it to 30
1. the value now achieved is the final chance to hit (FTH)
1. a hit is secured if Rnd[100] < FTH

The steps 1-11 above can be summarized to:

FTHmonster arrow = 30 + ToHitbase,monster + 2×mlvl - 2×distance - Dex/5 - Acitems,player - bonusplayer - 2×clvl

FTHtrap arrow = 100 - (Dex/5 + Acitems,player + bonusplayer + 2×clvl) / 2 - 2×distance

FTHmonster spell = 40 + 2×mlvl - 2×clvl

FTHtrap spell = 40

FTHplayer spell = 40

- ToHitbase,monster is the value found in the tables for each monster in chapter 5.2 and 5.4.

- Fire Wall, Flame Wave and Ring of Fire always attack players as if they were traps.

- For unique monsters, use mlvlbattle

- The bonusplayer is clvl/4 for the Barbarian, depends on the armor type for Monks (0 for non unique plate, clvl/2 for non unique mail or unique plates and 2×clvl for light armor and unique mail or if naked) and 0 for all other classes.

- Note that the FTH is adjusted for auto hit values.

**Block**

1. if the target is doing anything other than standing still or performing a melee attack, skip blocking

1. if the target is not a Monk and is not carrying a shield, skip blocking
1. if the target is a Monk and is not carrying a shield, a staff or has at least one hand bear, skip blocking
1. if the spell type is not blockable, skip blocking
1. *in Diablo*, if the spell type is blockable but the target has resistance to it, skip blocking
1. if the attacker is a monster calculate block Dex + 2×clvl + bonusplasyer

1. if the attacker is a monster subtract 2×mlvl
1. if the attacker is a trap, calculate Dextarget + bonustarget

1. if the value calculated is below 0, set it to 0
1. if the value calculated is above 100, set it to 100
1. the value now achieved is the final chance to block (FB)
1. a block of the attack is done if Rnd[100] < FB

The steps 5-11 above can be summarized to:

FB = Dex + 2×(clvl - mlvl) + bonusplayer

- The bonusplayer is 30 for Warriors and Barbarians, 25 for Monks and Bards, 20 for Rogues, and 10 for Sorcerers. Note that there seems to be a bug that makes all those bonus values be 0.
- For unique monsters, use mlvlbattle

- In the cases according to step 1-4 above when a block is not checked, the game actually DOES a random check, but the value checked against is 100 and thus will never result in a block.
- It is possible to achieve 100% blocking.

**Damage**

1. for spells and traps, the actual damage is calculated upon cast. For information about damage ranges for spells, see chapter 4.1.2 for traps and chapter 4.1.2 for spells from players.
1. if the attacker is a trap and the player has an item of thieves, divide damage by 2
1. *in Hellfire*, if the attacker is *not* a trap, divide damage by 2
1. add -damage
1. if damage is below 1, set it to 1
1. if the effect is a spell and the target has resistance to it, reduce the damage by the amount specified by the resistance

1. the value now achieved is the final damage (FD)
1. deal FD to target

**Hit consequences**

1. if the effect was an arrow and the monster had the knock back ability, move the player one step backwards (backwards is defined according to the player’s facing)
1. if the attacker hit and the target did not block, check if life went down to 0 or below; if so, put target player into death mode and skip further steps

1. if the target did not block and effect was an arrow or it was a spell and the target had no resistance to the spell type, check if FD >= clvl and, if so, put target player into hit recovery and check for durability loss on helm and armor

1. if the target blocked, put target player into block mode and check for durability loss on shield


### 6.3.4 Monster/Trap versus Monster

**To Hit**

1. if the target monster is an Illusion Weaver that is currently running away, exit as it is at the moment immune to any attack
1. if the monster is immune to the spell type, exit as it can’t be damaged
1. if the target is a monster that is Stone Cursed, the attack is an automatic hit; go directly to damage calculations

1. if the effect is an arrow, calculate 90 - Actarget - distance

1. if the effect is a spell, calculate 90 - Actarget
1. if the value calculated is below 5, set it to 5
1. if the value calculated is above 95, set it to 95
1. the value now achieved is the final chance to hit (FTH)
1. a hit is secured if Rnd[100] < FTH

The steps 4-7 above can be summarized to:

FTHarrow = 90 - Actarget - distance

FTHspell = 90 - Actarget

- Note that if FTH is below 5 or above 95 it is adjusted to 5 and 95. This is the same auto To Hit and auto miss that characters have.

**Damage**

1. for spells and traps, the actual damage is calculated upon cast. For information about damage ranges for spells, see chapter 4.1.2.
1. if the effect is a spell and the monster has resistance, divide damage by 4
1. the value now achieved is the final damage (FD)
1. deal FD to the target

**Hit consequences**

1. if the target was not a golem and it was not resistant to the spell and FD >= mlvl+3, put monster into hit recovery; a Scavenger or Grave Digger will also be set in a mode to find a carcass to feast/dig upon
1. if the target was a Hidden type of monster and it was not resistant to the spell, put monster into hit recovery as well as in retreat mode (see chapter 5.5.9).

1. if the monster died, check for any item dropping (see chapter 3.8) and add any experience to the players that are eligible for it (see chapter 2.6)

1. if the monster died and it was Diablo, terminate game and show ending movie


# 7. Shrines

Shrines are found on levels 1-8 (church and catacombs), cauldrons on levels 13-15 (hell), fountains, pools and springs on levels 1-8 and also on levels 13-16. Rarely you will also see fountains, pools and springs on level 9-12 (caves). Goat shrines are possible on any level that has Goat Men or Goat Archers (level 4-9).

![ref9]![ref2]![ref40]![ref40]

**Shrines in both Diablo and Hellfire**

||**Name of Shrine**|**Shrine Message**|**Effects**||||
| :- | :- | :- | :- | :- | :- | :- |
||Abandoned Shrine|*”The hands of men may be guided by fate”*|+2 dexterity.||||
||Creepy Shrine|*”Strength is bolstered by heavenly faith”*|+2 strength.||||
||Cryptic Shrine|*”Arcane power brings destruction”*|Casts a Nova spell and restores mana5.||||
||Divine Shrine|*”Drink and be refreshed”*|Restores health and mana. On dlvl 1-3 it gives||||
||||one Potion of Full Mana and one Potion of||||
||||Full Life. On other dlvl it gives two Potions||||
||||of Full Rejuvenation.||||
||Eerie Shrine|*”Knowledge and wisdom at the cost of self”*|+2 magic.||||
||Eldritch Shrine|*”Crimson and Azure become as the sun”*|All potions become rejuvenation potions.||||
||Enchanted Shrine1|*”Magic is not always what it seems to be”*|Lose 1 slvl for one spell (2 if it is at level 15).||||
||||All other known spells gain 1 slvl.||||
||Fascinating Shrine|*”Intensity comes at the cost of wisdom”*|Lose 10% of base mana and increases||||
||||Firebolt 2 slvl.||||
||Glimmering Shrine|*”Mysteries are revealed in the light of reason”*|Identifies all items in your inventory.||||
||Gloomy Shrine2,3|*”Those who defend seldom attack”*|+2 AC to all armor and -1 max damage to all||||
||||weapons.||||
||Hidden Shrine|*”New strength is forged through destruction”*|-10 durability to one item equipped. +10||||
||||durability to all others equipped (never||||
||||destroys an item).||||
||Holy Shrine|*”Wherever you go, there you are”*|Casts a Phasing spell5.||||
||Magical Shrine|*”While the spirit is vigilant the body thrives”*|Casts a Mana Shield spell5.||||
||Mysterious Shrine|*”Some are weakened as one grows strong”*|+5 to one attribute, -1 to all others.||||
||Ornate Shrine|*”Salvation comes at the cost of wisdom”*|Lose 10% of base mana and increases Holy||||
||||Bolt 2 slvl.||||
||Quiet Shrine|*”The essence of life flows from within”*|+2 vitality.||||
||Religious Shrine|*”Time cannot diminish the power of steel”*|Restores all items to full durability.||||
||Sacred Shrine|*”Energy comes at the cost of wisdom”*|Lose 10% of base mana and increases||||
||||Charged Bolt 2 slvl.||||
||Secluded Shrine|*”The way is made clear when viewed from above”*|Gives complete map of current level.||||
||Spiritual Shrine|*”Riches abound when least expected”*|Gives a small amount of gold to each empty||||
||||slot in your inventory. The amount given is:||||
||||Church:|Rnd[10] + 5|(5 - 14)||
||||Catacombs:|Rnd[20] + 10|(10 - 29)||
||||Caves:|Rnd[30] + 15|(15 - 44)||
||||Hell:|Rnd[40] + 20|(20 - 59)||
||Spooky Shrine4|*”Where avarice fails, patience gains reward”*|All other players get life and mana restored.||||
|||*(user),*|||||
|||*”Blessed by a benevolent companion!” (others)*|||||
||Stone Shrine|*”The powers of mana refocused renews”*|Restores charges in all staves.||||
||Tainted4|*”Those who are last may yet be first” (user),*|Does not affect user but other players get +1||||
|||*”Generosity brings its own reward” (others)*|to one attribute and -1 to all other attributes.||||
||Thaumaturgic Shrine3,5|*”What once was opened now is closed”*|Refills chests on current level.||||
||Weird Shrine2,3|*”The sword of justice is swift and sharp”*|+1 max damage to all weapons in inventory.||||
1. Enchanted shrines will never appear in Caves or Hell, not even as a Cauldron or Goat Shrine.
1. Effect only lasts for current game.

1. Only available in single player.

1. Only available in multi player.

1. All spells cast from a shrine will have an slvl of 2 in church, 4 in catacombs, 6 in caves and 8 in hell.

|<a name="page154"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|**Created by Pedro Faria**|||
| :- | :- | :- | :- |
|||||
|**Fountains, Pools, Cauldrons and other similar objects in both Diablo and Hellfire**||||
|**Name of Object**|**Message**|**Effects**||
|Blood Fountain1|[No message]|Restores 1 life each time it is used.||
|Cauldron|[Message related to the effect]|Random effect (of true Shrines only)2.||
|Fountain of Tears1|[No message]|+1 to one attribute, -1 to another attribute||
|Goat Shrine|[Message related to the effect]|Random effect (of true Shrines only)2.||
|Murky Pool1|[No message]|Casts an Infravision spell3.||
|Purifying Spring1|[No message]|Restores 1 mana each time it is used.||
1. There will never be more than one of this type on any dungeon level.
1. Thaumaturgic Shrine will never appear as a Cauldron or Goat Shrine.

1. All spells cast from a shrine will have an slvl of 2 in church, 4 in catacombs, 6 in caves and 8 in hell.

**New Shrines in Hellfire**

||**Name of Shrine**|**Shrine Message**|**Effects**||||
| :- | :- | :- | :- | :- | :- | :- |
||Glowing Shrine|*”Knowledge is power”*|If current experience is equal to or below||||
||||5000, set it to 0 and you get +[exp/1000]||||
||||Magic. If current experience is above 5000||||
||||you get +5 Magic and -5% experience||||
||Mendicant’s Shrine|*”Give and you shall receive”*|Half of money turns into experience.||||
||Murphy’s Shrine|*”That which can break will”*|For each non indestructible item you have||||
||||equipped, there is a 1/3 chance it will lose||||
||||50% of its durability. It will always start with||||
||||the helm and then proceed with left weapon||||
||||slot, right weapon slot and finally the armor.||||
||||As soon as an item has lost durability it will||||
||||exit. If no item lost durability or no non||||
||||indestructible items are equipped it takes 1/3||||
||||of your gold instead.||||
||Oily Shrine|*”That which does not kill you…”*|Warrior:|+2 Strength|||
||||Rogue:||+1 Magic, +1 Dexterity||
||||Sorcerer:|+2 Magic|||
||||Monk:|+1 Strength, +1 Dexterity|||
||||Bard:||+1 Magic, +1 Dexterity||
||||Barbarian:|+2 Vitality|||
||||It also casts a Fire Wall like spell.||||
||Shimmering Shrine|*”Spiritual energy is restored”*|Restore mana.||||
||Solar Shrine|*”You feel stronger”*|12\.00 to 18.00:|+2 Strength|||
|||*”You feel wiser”*|18\.00 to 20.00:|+2 Magic|||
|||*”You feel refreshed”*|20\.00 to 04.00:|+2 Vitality|||
|||*”You feel more agile”*|04\.00 to 12.00:|+2 Dexterity|||
||Sparkling Shrine|*”Some experience is gained by touch”*|+1000×dlvl experience points and casts a||||
||||Flash spell (part 1 only).||||
||Town Shrine|*”There’s no place like home”*|Casts Town Portal.||||

All shrines can occur on any dungeon level with the exception of the Enchanted shrine which will only occur on level 1-8. All shrines also have the same probability to occur on any dungeon level. Similarly all shrines have the same probability to be selected when you hit a Goat Shrine or a Cauldron (with the exception of Enchanted shrine mentioned above and the fact that Thaumaturgic Shrines will never appear as a Goat Shrine or a Cauldron).

To make it easier finding out what shrine you have hit when you try your luck at a goat shrine or a cauldron, the table below lists the messages (in alphabetical order) as well as what shrine they correspond to.

|<a name="page155"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**||**Created by Pedro Faria**||||
| :- | :- | :- | :- | :- | :- |
|||||||
|**Shrine Message**|**Name of Shrine**|**Shrine Message**||**Name of Shrine**||
|*”Arcane power brings..”*|Cryptic Shrine|*”That which can break will”*||Murphy’s Shrine2||
|*”Blessed by a benevolent..”*|Spooky Shrine1|*”That which does not kill you…”*||Oily Shrine2||
|*”Crimson and Azure become..”*|Eldritch Shrine|*”The essence of life flows from..”*||Quiet Shrine||
|*”Drink and be refreshed”*|Divine Shrine|*”The hands of men may be..”*||Abandoned Shrine||
|*”Energy comes at the cost of..”*|Sacred Shrine|*”The powers of mana..”*||Stone Shrine||
|*”Generosity brings its own..”*|Tainted Shrine1|*”The sword of justice is swift..”*||Weird Shrine||
|*”Give and you shall receive”*|Mendicant’s Shrine2|*”The way is made clear when..”*||Secluded Shrine||
|*”Intensity comes at the cost of..”*|Fascinating Shrine|*”There’s no place like home”*||Town Shrine2||
|*”Knowledge and wisdom at..”*|Eerie Shrine|*”Those who are last may yet..”*||Tainted Shrine||
|*”Knowledge is power”*|Glowing Shrine2|*”Those who defend seldom..”*||Gloomy Shrine||
|*”Magic is not always what it..”*|Enchanted Shrine|*”Time cannot diminish the..”*||Religious Shrine||
|*”Mysteries are revealed in the..”*|Glimmering Shrine|*”What once was opened now..”*||Thaumaturgic Shrine||
|*”New strength is forged..”*|Hidden Shrine|*”Where avarice fails, patience..”*||Spooky Shrine||
|*”Riches abound when least..”*|Spiritual Shrine|*”Wherever you go, there you..”*||Holy Shrine||
|*”Salvation comes at the cost of..”*|Ornate Shrine|*”While the spirit is vigilant the..”*||Magical Shrine||
|*”Some are weakened as one..”*|Mysterious Shrine|*”You feel more agile”*||Solar Shrine2||
|*”Some experience is gained by..”*|Sparkling Shrine|*”You feel refreshed”*||Solar Shrine2||
|*”Spiritual energy is restored”*|Shimmering Shrine2|*”You feel stronger”*||Solar Shrine2||
|*”Strength is bolstered by..”*|Creepy Shrine|*”You feel wiser”*||Solar Shrine2||
1. Message got when someone else uses the shrine.
1. Only available in Hellfire.

There exist a bug that will cause any shrine with a random effect to at times not be random and instead have a specific result. This bug is most noticeable in the first games you play without exiting Diablo completely (decreasing in probability for each dungeon level you enter, including reentering of a level). For the most time, the shrines *will* be random however. The end effect of the bug is that the randomness of those shrines favor a certain result. The favored results are summarized in the table below.

|**Name of shrine**|**Favored result**|**Name of shrine**|**Favored result**|
| :- | :- | :- | :- |
|Enchanted Shrine|Chain Lightning losing slvl|Spiritual Shrine|Irrelevant1|
|Hidden Shrine|Shield losing durability|Tainted Shrine|Dexterity increased|
|Mysterious Shrine|Dexterity increased|Murphy’s Shrine2|Second item lose durability|

1. As the shrine typically fills many slots with gold, the end effect will still be quite random depending on number of free slots.
1. Only available in Hellfire.

Due to the way the game work, it may also have some slight impact on random events that are not pre determined by the game (example of pre determined effects are item drops and result of shrines) occurring after the shrine is used. Cauldrons and Goat shrines are *not* affected by this bug.


# 8. Quests

This chapter deals with all of the quests present in Diablo and Hellfire. It only provides information on what has to be done to fulfill each quest. You have to find the best strategy for doing it yourself. Two of the quests in Hellfire are hidden quests. Chapter 1.2 provides information on how to activate them. Most quests are only available in single player mode, but some are present in both single and multi player. The table below lists each quest and the unique item (if any) you receive when you complete the quest. Normally you get it from the person who initiated the quest. Those unique items are only available in single player and information about them can be found in chapter 3.5. Note that you don’t receive all quests in every game (although some are always present), as they are randomly selected for each game. For more information, see chapter 8.1.

|**dlvl**|**Quest**|**Activated by**|**Multi player**|**Reward**|
| -: | :- | :- | :-: | :- |
|2|The Butcher|Wounded Townsman|Yes|The Butcher’s Cleaver1|
|2|Poisoned Water Supply|Pepin||Ring of Truth|
|3|The Curse of King Leoric|Ogden|Yes|The Undead Crown1|
|4|Gharbad the Weak|Gharbad|||
|4|Ogden’s Sign|Ogden||Harlequin Crest|
|5|The Magic Rock|Griswold||Empyrean Band|
|5|Valor|Book||Arkaine’s Valor|
|6|The Chamber of Bone3|Book||Guardian spell level|
|7|Halls of the Blind|Book||Optic Amulet|
|8|Zhar the Mad|Zhar the Mad|||
|9|Black Mushroom|Adria||Spectral Elixir|
|9|Slain Hero4|n/a|||
|10|Anvil of Fury|Griswold||Griswold’s Edge|
|13|Warlord of Blood|Book|||
|14|Lachdanan|Lachdanan||Veil of Steel|
|15|Archbishop Lazarus|Cain the Elder|Yes||
|16|Diablo|Cain the Elder|Yes|Dot2|
|Town|Farmer’s Orchard|Lester the Farmer|Yes7|Auric Amulet|
|Town|The Jersey’s Jersey5|Complete Nut|Yes7|Bovine Plate|
|Town|Little Girl5|Little Girl|Yes7||
|H4|The Defiler|The Defiler|Yes7|Cathedral Map|
|Town|Grave Matters|Gillian|Yes7||
|C1|Cornerstone of the World6|You|Yes7||
|C1-3|Torn Notes6|Torn Notes|Yes7|Reconstructed Note|
|C4|Na-Krul|Na-Krul|Yes7||
1. In multi player you receive a random magic item instead.
1. You receive 1 dot if you kill Diablo on normal difficulty, 2 dots if you kill him on nightmare difficulty and 3 dots if you kill him on hell difficulty. The only place where you can see your dots is Battle.net.

1. Appears in every single player game.

1. Not really a quest but appropriate to list here.

1. Hidden quests, see chapter 1.2 for information on how to activate them.

1. Never shows up in the Quest Log.

1. I think all Hellfire quests are also present in multi player.



## 8.1 How quests are chosen

In single player, the quests that will appear in a single game are chosen at random. But there is some structure in the way they are chosen. Three quests are always present in every game: The Chamber of Bone, Archbishop Lazarus, and Diablo. If you play Hellfire, all the new quests will also always be present. The other quests are all organized into groups. From each group a specific number of quests are chosen for every game. The table below summarizes the different groups and how many quests from each group are chosen each game.

|<a name="page157"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|**Created by Pedro Faria**|||
| :- | :- | :- | :- |
|||||
||**Quests in each group**|**Number Chosen**||
||The Curse of King Leoric, Poisoned Water Supply|1||
||The Butcher, Gharbad the Weak, Ogden’s Sign|2||
||The Magic Rock, Valor, Halls of the Blind|2||
||Zhar the Mad, The Black Mushroom, Anvil of Fury|2||
||Warlord of Blood, Lachdanan|1||

## 8.2 Quests in Diablo

### 8.2.1 The Butcher

This quest is present if you see a wounded townsman outside the church (in multi player it is always present). You will find The Butcher in a special red room on level 2. Killing him rewards you with The Butcher’s Cleaver in single player and a random magical item in multi player.


### 8.2.2 Poisoned water supply

This quest is present if the water in the fountain is yellow instead of blue. You will then find an entrance (dark passage) on level 2 to the small mini level where you solve the quest. To solve it, simply kill all monsters in the mini level. Go back to Pepin to get the Ring of Truth. You will know you have killed them all when the water runs blue again.


### 8.2.3 The Curse of King Leoric

If you have this quest you will find an entrance to Skeletons King’s Lair somewhere on level 3. His lair is a mini level with lots of skeletons and hidden rooms. Pull all levers and attack all crucifixes to reveal the secrets. When the Skeleton King is killed he will drop The Undead Crown. Beware, because in single player, the Skeleton King has the ability to raise dead skeletons.

In multi player Skeleton King is simply running around somewhere on level 3. Instead of being able to raise skeletons, he has the ability to steal life in multi player. When you kill him he will drop a random magic item.


### 8.2.4 Gharbad the Weak

You will find Gharbad the weak somewhere on level 4. Talk to him and then go away (off screen so you don’t see him) and then come back. You will now receive a random magical item. Go away again, and the next time you come back and talk to him he will tell you he is almost finished. The third time you come back to him, he will attack you. When killed he drops a random magical item just like any other unique monster.

The first item he gives you is created as if it had come from a normal (non unique) monster, with the exception that it will always be magical. The item he drops when you kill him is created normally as from a unique monster, with the exception that it will always be a base item within the clubs.


### 8.2.5 Ogden’s Sign

In this quest, the stair from level 4 down to level 5 is blocked by Snotspill, who wants you to go around the block and fetch him the Tavern Sign. But so does Ogden. If you bring the sign to Ogden, he will give you Harlequins Crest. Snotspill will attack you regardless of whether you give him the sign or not.


### 8.2.6 The Magic Rock

If you have this quest, you will find a rock on a pedestal somewhere on level 5. Bring the rock back to Griswold and he will give you Empyrean Band.


### 8.2.7 Valor

If you have this quest, you will find a special set of rooms on level 5 with the shape of a cross. If you enter the double doors, you will find the first blood stone. Put it on the book with the pedestal in the same room. That will open up another door in the room shaped like a cross (go outside to find it). Inside the newly opened room you find yet another blood stone. Bring it back to the book too and a third room will be opened up. In it you find the third blood stone, which, if placed on the book, will open up the final part of the ”cross”. In it you will find Arkaine’s Valor.


### 8.2.8 The Chamber of Bone

This quest is always present in single player. You must first read the book on level 6, which activates the quest. When you do, the entrance (a stair on level 6) will open up and you can go to the mini level where you solve the quest. Pull both levers to open secret rooms. In the center of the mini level you will find the chamber of bones (lots of bones there). Behind it you will find another room with a book. When you read the book inside the final room you have finished the quest and will gain a spell level of Guardian.

The chests found in the small rooms on the mini level will create items as if they came from a unique monster, that is, they will always be magical, have a higher probability of being unique and will use the +4 bonus to the ilvl for determination of the prefix and/or the suffix.


### 8.2.9 Halls of the Blind

This quest is present if you find a room shaped like an ”8” on level 7. After reading the book on the same level, two doors will open to the ”8”. Kill all Illusion Weavers inside it and the Optic Amulet will drop in the upper of the two small rooms inside the ”8”.


### 8.2.10 Zhar the Mad

You will find Zhar the Mad in a room with a book case on level 8. He will give you a book if you talk to him. As soon as you touch the book case, he will attack you (the book case will not drop any book). When you kill him he will drop a random magical item. To make the book case drop a book, you need to either use telekinesis on it before you talk to Zhar the Mad, or you should talk to Zhar the Mad a second time before touching the book case; after beating him you will then get a book from the book case.

Any book from Zhar the Mad or his book case is created from an ilvl equal to 2×dlvl. The item he drops when you kill him is created normally as from a unique monster.


### 8.2.11 Black Mushroom

This is one of the most complicated quests in Diablo. After finding a *fungal tome* on level 9 and bringing it to Adria, the quest is initiated. You will then be able to find a huge *black mushroom* on level 9. Giving the mushroom to Adria will make her tell you about the *demon’s brain* and that you should take the brain to Pepin. The first monster you kill after Adria tells you about the brain will indeed drop a brain. It does not necessarily have to be a demon, for any monster will drop it. Take the brain to Pepin, who will give you an elixir that you should give to Adria. Finally, take the elixir to Adria and she will tell you that you can keep it. It is the *spectral elixir*. After Adria tells you that you can keep it you should drink (use) it immediately. *Don’t* save the game before drinking it. It will give you +3 to all attributes. If you don’t use it right away you will not be able to use it at all. However, I have been told that if you get hold of a second spectral elixir, you can use both at once.


### 8.2.12 Slain Hero

You will find a slain hero somewhere on level 9. He will drop an item depending on your character class. The table below tells what base item each character class will get. The ilvl for item creation for items from the Slain hero is equal to 2×dlvl. The items will be given the same +4 bonus as is given to unique monsters when picking prefixes and suffixes. As such, the item creation follows the same rules and probabilities as for an item dropped from a unique monster (with the exception that the base item is not random).

|<a name="page159"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|**Created by Pedro Faria**|||
| :- | :- | :- | :- |
|||||
|**Character class**|**Item type**|<b>Base item<sup>1</sup></b>||
|Warrior|heavy armor|breast plate||
|Rogue|bow|long battle bow or long war bow||
|Sorcerer|book of|book of Lightning2||
|Monk|staff|war staff||
|Bard|sword|bastard sword||
|Barbarian|axe|battle axe||
1. It is worth noticing that the game actually checks the *picture* of the created item (except for the Sorcerer). This does of course mean that any unique of the appropriate type that has a unique picture can not be chosen. It also means that any unique item of another base item (but still within the appropriate group, such as heavy armor, bows, staffs, and so on) can be chosen if it has the picture of the base item that is supposed to be dropped.
1. The base item is of course a *book of* but the game will attach the spell Lightning to it.


### 8.2.13 Anvil of Fury

The anvil can be found on a small peninsula on level 10. It is heavily guarded by lots of monsters. Bring the anvil back to Griswold and he will give you Griswold’s Edge.


### 8.2.14 Warlord of Blood

If you find lots of Steel Lords on level 13, you have this quest. After reading the book on this level, the room next to the stairs down to level 14 will open up and you can fight the Warlord of Blood. After killing him, don’t forget to collect all the magical items on the racks in his room.


### 8.2.15 Lachdanan

Lachdanan is a unique Blood Knight that you will find on level 14. If you have this quest you will also find other Blood Knights on this level. He asks you for the golden elixir, which can be found somewhere on level 15. Bring it to him and he will give you the Veil of Steel.


### 8.2.16 Archbishop Lazarus

On level 15, you will find the Staff of Lazarus. Take it to Cain and he will initiate the quest. A red portal will open up on level 15, adjacent to the pentagram. It takes you to Lazarus’ lair, a small mini level. You will find two Books of Vileness. Stand on the small pentagram near each one and read the books. They will teleport you to new sections of the mini level. After reading both books, a new pentagram will appear at the place where you entered the mini level. Standing on it will teleport you into Lazarus’ room. Kill him and the red portal will once more appear at the entrance to the mini level. If you take it back to level 15 you will see that the pentagram has turned red and it takes you to level 16.

In multi player, you will not find the Staff of Lazarus. Lazarus himself will be in the upper corner of level 15, in a small room. Kill him to open/activate the pentagram to level 16.


### 8.2.17 Diablo

Level 16 is made up of four areas. The first one, at the top, has a lever in the middle. It opens up the maze to the right. Inside it you will find yet another lever which opens up the area to the left. Inside it are two more levers, which, if both are turned, will open up the final room where you will find Diablo. Kill him and you get to see the Game End movie. In multi player, don’t forget that you will have to pick up every item you wish to keep before killing Diablo, as you will be leaving the game after seeing the End Game movie. Only if someone is left in the game and that person is *not* on level 16 when Diablo dies will the game not be closed, and you can reenter it later. Since Diablo is treated like* a normal monster by the game, he will sometimes drop an item. It can be anything from gold to a magical item.

When Diablo dies, anyone currently on dlvl 16 will be awarded dots for the difficulty level in question. See chapter 9.4 for more information about dots.


## 8.3 Quests in Hellfire

### 8.3.1 Farmer’s Orchard

If you have not activated the hidden quests, see chapter 1.2. You will find Lester the Farmer near the cows in the town. If your character is level 15 or above, Lester will give you the Rune Bomb. Take it to the bridge adjacent to where you start. Standing on the bridge, drop it on the alien like thing on the ground. It will blow up the entrance to the Hive (The Nest). Go back to the Farmer and he will give you the Auric Amulet.


### 8.3.2 The Jersey’s Jersey

If you have activated the hidden quests (see chapter 1.2), you will not find Lester the Farmer. Instead, you will find the Complete Nut, also standing by the cows. In the Hive you will find one gray suit lying on the ground somewhere on level 3, and one brown suit lying on the ground somewhere on level 4. Bring the brown suit to the Complete Nut and he will give you the Bovine Plate.


### 8.3.3 Little Girl

If you have activated the hidden quests (see chapter 1.2), you will find a little girl standing close to the bridge just above the one that leads to the Hive. She will only appear once you have been to the Hive. When you kill the Hork Demon on level 3 of the Nest, he will drop Theodore, the teddy bear. Take it to the little girl and she will give you a random magic amulet created from an ilvl of 26. If you have not activated the hidden quests, the Hork Demon will drop a random magic amulet also created from an ilvl of 26.


### 8.3.4 The Defiler

The Defiler is the Boss of the Hive. Killing him will give you the Cathedral Map.


### 8.3.5 Grave Matters

Go to the graveyard by the church. Drop the Cathedral Map on the huge new grave you find there. It will open up the entrance to the Crypt.


### 8.3.6 Cornerstone of the World

You will find the Cornerstone of the World (the CoW) in a small room on level 1 of the Crypt. By placing an item on it, that item will be available for another character of yours in other games. There is only one Cornerstone of the World and it is common for all games; thus, as soon as you pick up the item on it in any game, you will no longer be able to get it from any of your games. Remember that you should never be in the Crypt with any of the two characters that are involved in the swap for it to work. The reason for this is that the game will save and restore the content of the CoW *if* you are on level 1 in any save game. The effect may range from not being able to transfer the item at all to actually duplicating the item (which, like the infamous cursor duplication is of course a bug). The table below should clarify the result. I recommend that you always save the game while in town when you want to transfer an item via the Cornerstone of the World. This quest will never show up in the quest log.

||**Character giving on**|**Character giving not on**|
| :- | :-: | :-: |
||**level 1 of Crypt**|**level 1 of Crypt**|
|**Character receiving on**|Not possible|Not possible|
|**level 1 of Crypt**|||
|**Character receiving not**|Transfer possible|Duplication of item|
|**on level 1 of Crypt**|||

### 8.3.7 Torn Notes

On each of the first 3 levels of the Crypt you will find one Torn Note. When you have found all three, they will combine to the Reconstructed Note, which tells you about how to open the room to Na-Krul. This quest will never show up in the quest log.


### 8.3.8 Na-Krul

Na-Krul can be found in a small room on level 4 of the Crypt. If you open his room by pulling the lever he will be a very tough opponent. However, if you read the books outside his room in the correct order, he will come out severely weaker (see chapter 5.2.4 for the difference). The correct order is:

1. In Spiritu Sanctum

1. Praedictum Otium
1. Efficio Obitus Ut Inimicus

When killed, Na-Krul will always drop four items according to the table below.

|**Item number**|**Item type**|<b>Base item<sup>1</sup></b>|
| :- | :- | :- |
|First|sword|great sword|
|Second|staff|war staff|
|Third|bow|long battle bow or long war bow|
|Fourth|book of|book of Apocalypse2|

1. It is worth noticing that the game actually checks the *picture* of the created item (except for the book). This does, of course, mean that any unique of the appropriate type that has a unique picture cannot be chosen. It also means that any unique item of another base item (but still within the appropriate group; that is, sword, staff, and bow) can be chosen if it has the picture of the base item that is supposed to be dropped.
1. The base item is of course a *book of* but the game will attach the spell Apocalypse to it.


# 10. Other useful information


## 10.1 Hot keyed messages while playing

While playing multi player games, you can set the four keys F9 - F12 to have four special messages that you can send to the other players in the game. This could be good for messages that you need to send quickly while fighting. To change these messages on a PC, you should edit the files *diablo.ini* in Diablo and *hellfire.ini* in Hellfire. For Hellfire, you must first create the file. The easiest way to do this is to copy the *diablo.ini* file from your Diablo folder into the Hellfire folder and then rename it. The syntax of the two files is identical.


## 10.2 Save files

In single player, you can save (and must save) your game whenever you want. The save files are stored in the Diablo/Hellfire folder and can easily be transferred to other computers. In multi player, you can’t save the game. Your character, its stats and items that it has equipped or carries, is saved automatically by the game as soon as you make any changes to it. Thus, there is never any need to save it. Your character in multi player is also saved in the Diablo folder. The names of the save files are summarized in the tables below. In versions previous to 1.08, the game used to save your multiplayer files in the Windows (!) folder on the PC, so you may still find those save files there. Whenever you run Diablo v1.08 or later, it will move those files to the Diablo folder but will not remove them from the Windows folder. As Hellfire is based on the 1.04 version of Diablo, it still saves the multiplayer files in the Windows folder.

**PC**

||**Game type**|**Folder**|**Name**|||
| :- | :- | :- | :- | :- | :- |
||Diablo single player|Diablo|single\_#.sv|Where # is a number in the range 0..9||
||Hellfire single player|Hellfire|single\_#.hsv|Where # is a number in the range 0..9||
||Diablo multi player|Diablo|multi\_#.sv|Where # is a number in the range 0..9||
||Hellfire multi player|Windows1|hrinfo\_#.drv|Where # is a number in the range 0..9||
1. Since the files end with .drv, the files would normally be hidden by Windows. You might have to activate *show hidden files* to see them.

**Macintosh**

||**Game type**|**Folder**|**Name**|||
| :- | :- | :- | :- | :- | :- |
||Diablo single player|Diablo|diablo single #|Where # is a number in the range 0..9||
||Diablo multi player|Diablo|diablo multi #|Where # is a number in the range 0..9||

## 10.3 Transferring save files

There is no way to transfer a save file (and thus a character) to/from single and multi player. To transfer files between computers (and even between a PC and a Mac), simply copy the save files over. Since the 1.08 patch, this is now possible without any problems for multi player files as well. For information on how to transfer a character from Diablo to Hellfire, see the *readme.txt* file in your Hellfire folder.

To transfer a multi player character from one computer to another in Hellfire (and in Diablo on the PC previous to the 1.08 patch) is a bit tricky. The reason for this is that the game has included the computer name into the save file (you can find the computer name under network in the control panel). Thus, for a save file to be playable on another machine, the computer name has to be the same as on the computer you take the character from. Otherwise, Hellfire will not recognize the save. If the computer name of the two computers is the same, one can simply copy the multi player save file from one of the computers to the other. Don’t forget to put it in the Windows folder of the new computer if it is a PC. Single player files seems to be transferable between computers, even between a PC and a Mac) without problems in any version.

If the number of the save file (the # in the name above) is already in use on the new computer it should be safe to change it to a non used number in the 0..9 range. It is very important to make sure you don’t get two characters with the exact same name this way as Diablo/Hellfire does not manage to handle such a situation well.


## 10.4 Backing up your character

In case you are worried of losing your character due to crashes or other computer problems, the easiest way to back up your character is to simply copy the save files to a safe place (a floppy disk for example). To restore it later, you simply copy the save file back to the proper folder. See chapter 10.2 for more information about the save files and where they are located.


## 10.5 Daylight-saving time problems in Diablo 1.00

Version 1.00 of Diablo had a bug concerning the daylight-saving time. Due to this bug, *any* character saved by a game from a later version will lose all its items if you run version 1.00. This is important to remember if you ever have to reinstall Diablo. If you do so, you should *not* update via Battle.net. You should *not* press the ”Multi player” option on the game menu until you have manually updated to a later version. An alternative would be to backup your characters, update in whatever way you want, and then restore your characters after you have updated.


## 10.6 Avoiding the Game End movie

Every time you or someone else kill Diablo, the game will end and the Game End movie will start to play. As the movie is quite long, it is worth using the following way to terminate it before it reaches the end. As soon as it starts, press Alt-Tab. This will bring you out to your Windows desktop. Now either press Alt-Tab again until you get back to Diablo, or click on Diablo on the Task Bar. You will then be back to the Battle.net chat room or the pre-game menu, depending on what type of game you were playing.

An alternative is to rename (or move) the file *Smackw32.dll* found in your Diablo folder. It is the file that plays the movies in the game. It will also result in that you wwill not be able to see the introduction movies though. It seems the game will not be affected in any other way if you rename or move this file but be aware that if you get into any trouble, you may have to reinstall the game. If you do this, pay attention to the Daylight-saving time problem mentioned in chapter 10.5.


## 10.7 Meaningless information about this guide**

As this is a guide about numbers and formulas it is not more than right that it has a few numbers about itself. Thus, below is a table with some information about this guide. Some of the values may vary with the printer, paper size and format used.

|<a name="page172"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|||**Created by Pedro Faria**|||||
| :- | :- | :- | :- | :- | :- | :- | :- |
|||||||||
|**Version**|**Pages**|**Paragraphs**|**Lines**|**Words**|**Characters**|**Bytes**||
|1\.00|68|10 757|13 399|26 238|104 883|594 432||
|1\.10|71|12 040|14 434|30 358|121 563|676 864||
|1\.20|91|13 611|16 119|41 978|172 594|786 944||
|1\.30|101|14 506|17 280|46 973|193 806|846 336||
|1\.31|101|14 596|17 390|47 863|197 838|859 136||
|1\.40|124|17 749|22 206|58 865|244 474|1 084 416||
|1\.50|146|18 745|23 662|74 267|306 580|1 199 104||
|1\.51|147|18 886|23 837|75 006|310 256|1 210 880||
|1\.52|147|18 953|23 929|75 864|314 175|1 219 584||
|1\.60|169|21 510|26 996|88 915|370 027|1 367 040||
|1\.61|171|21 563|27 093|90 371|376 459|1 381 840||
|1\.62|172|21 597|27 136|90 792|378 298|1 384 448||
|1\.00 to 1.10|3|1 283|1 035|4 120|16 883|82 432||
|1\.10 to 1.20|20|1 571|1 685|11 620|51 031|110 080||
|1\.20 to 1.30|10|895|1 161|4 995|31 212|59 392||
|1\.30 to 1.31|0|90|110|890|4 032|12 800||
|1\.31 to 1.40|23|3 153|4 816|11 002|46 636|225 280||
|1\.40 to 1.50|22|996|1 456|15 402|62 106|114 688||
|1\.50 to 1.51|1|141|175|739|3 676|11 776||
|1\.51 to 1.52|0|67|92|858|3 919|8 704||
|1\.52 to 1.60|22|2 557|3 067|13 051|55 852|147 456||
|1\.60 to 1.61|2|53|97|1 456|6 432|14 800||
|1\.61 to 1.62|1|34|43|421|1 839|2 608||
|1\.00 to 1.62|104|10 840|13 737|64 554|273 415|790 016||

## 10.8 The End

It is worth noticing that there are 3 kinds of people in the world, those who can count and those who can’t.