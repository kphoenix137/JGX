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

## [4. Magic](#4-magic)
- [4.1 Spells available to players](#41-spells-available-to-players)
- [4.2 Spell casting monsters](#42-spell-casting-monsters)
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


# 1. Introduction

There are a few general things about the guide that can be good to know when you read it. Below are summarized such general remarks that are valid for the whole guide but never explicitly mentioned anywhere else.

- All prices in this guide are buying prices, that is, the price that you would have to pay for an item. Some items can’t be bought, like unique items, elixirs of Vitality, and oils. The prices of those items are still listed as buying prices, however. Note that although items from Wirt initially have a value 50% higher than Griswold’s price (75% of Griswold’s price in Hellfire), they will have the normal Griswold price when you restart a new game and give away the item.

- When doing calculations, you should generally round down any number you get, as that is the way Diablo and Hellfire works. However, life, mana ,HP, and damage are actually kept track of with higher precision than shown and should not be rounded down. If you are supposed to round down *within* a formula, that will usually be indicated by [ ].

- The term *clubs* in this guide refers collectively to all blunt weapons including club, spiked club, mace, morning star, flail, war hammer and maul.

- Unless otherwise stated, the Hive dungeon levels are numbered 9-12, the same as Caves. The Crypt is numbered 13-16, the same as Hell.

- Monsters have Hit Points (HP) while players have life. For most purposes there is no difference between HP and life though.

- At times, the guide will refer to ”a turn”. Obviously Diablo and Hellfire are not turned based. Never the less, the games work at about 20 ”frames” per second. That is, each 0.05 second, the game will go through all the characters, monsters, spells, and such, and update them. This is what is meant by *turn* in this guide. As a consequence of the rate the games are updated, there is nothing in the game that can take less than 0.05 seconds and all times are evenly divisible by 0.05.

- Frequently a range of values are given. This is done in two different ways: *x - y* or *x to y*, where x and y can either be a number or some formula. Both cases are identical and the latter is usually used to avoid any confusion with interpreting the hyphen as a minus sign. Unless otherwise stated the game will pick a value within the range at random and all values have the same probability.

- North is defined as upwards on your own screen. That will be sort of diagonally compared to the general dungeon layout. One can then note that there are 8 different directions in which one can walk, turn, attack and so on in the game (the actual spells can travel in more directions but you cast them facing one of the 8 directions). When talking about directions in this Guide, it will use the above definition.

- The dungeon basically consists of square locations where each square can typically contain only one monster, player or other object. In the guide, unfortunately, the terminology used for those squares includes terms such as location, tile and square. They should all be read and understood to be the same thing.

## 1.1 Abbreviations

Throughout this guide some common abbreviations are used. They are summarized below.

| **Abbreviation** | **Meaning** |
|-------------|--------------------------------------------------|
| clvl        | character level |
| dlvl        | dungeon level |
| ilvl        | item creation level, used for creating items |
| mlvl        | monster level |
| qlvl        | quality level of base item, prefix, suffix, and unique item |
| Intf        | Intelligence factor |
| slvl        | spell level |
| Rnd[x]      | random integer in the range 0 to x-1 |
| Str         | character strength |
| Mag         | character magic |
| Dex         | character dexterity |
| Vit         | character vitality |
| [ ]         | round down |

# 2. Characters

The most important character in the game is of course you. So this guide will start by giving information about the characters you can choose to play. The available characters are listed below.

| **Class**      | **Availability** |
|---------------|----------------|
| **Warrior**   | Available in *Diablo* and *Hellfire*. |
| **Rogue**     | Available in *Diablo* and *Hellfire*. |
| **Sorcerer**  | Available in *Diablo* and *Hellfire*. |
| **Monk**      | Available in *Hellfire*. |
| **Bard**      | Hidden test character, available in *Hellfire*. |
| **Barbarian** | Hidden test character, available in *Hellfire*, added in the **1.01 patch**. |

For information about how to activate the hidden characters, see chapter 1.2. Note that the Bard uses the same graphics as the Rogue and the Barbarian uses the same graphics as the Warrior.


## 2.1 Character stats

Each character in Diablo has a set of stats (or abilities) that greatly affect how well he or she performs. This chapter will explain how these stats affect your character, how they are calculated (which is not always obvious as the game often does not show the true values of the stats), and how they can be changed. For information about how items can modify the stats, see chapter 3. The stats have been grouped into basic stats (Strength, Magic, Dexterity, Vitality, Life and Mana) and other stats (Armor Class, To Hit, Damage and Resistance). The final stat, character level, is handled in chapter 2.6. One should be aware of the fact that the clvl of a character is in fact the most important stat of them all as it enters into the calculations of many of the other stats as can be seen in this chapter.


### 2.1.1 Starting stats

Each character class has its own starting values for the basic stats. They are listed below. Also listed are which stats are increased and by how much when you gain a level. Apart from those, you also gain 5 ”points” to distribute among your four main stats until they have reached their maximum value. Shrines and some monsters have the ability to alter your stats, too. See appropriate chapters for more information.

| **Class**    | **Strength** | **Magic** | **Dexterity** | **Vitality** | **Life** | **Mana** | **Effect of Level<sup>[^1]</sup>** |
|-------------|:-----------:|----------:|:------------:|:-----------:|:--------:|---------:|:-----------------:|
| **Warrior**   | 30  | 10  | 20  | 25  | 70  | 10  | +2 life, +1 mana  |
| **Rogue**     | 20  | 15  | 30  | 20  | 45  | 22  | +2 life, +2 mana  |
| **Sorcerer**  | 15  | 35  | 15  | 20  | 30  | 70  | +1 life, +2 mana  |
| **Monk**      | 25  | 15  | 25  | 20  | 45  | 22  | +2 life, +2 mana  |
| **Bard**      | 20  | 20  | 25  | 20  | 45  | 35  | +2 life, +2 mana  |
| **Barbarian** | 40  |  0  | 20  | 25  | 70  |  0  | +2 life, +0 mana<sup>[^2]</sup>  |

[^1]: You don’t get any life or mana when gaining level 50.  
[^2]: The Barbarian also gets 1% resistance per level.


### 2.1.2 Maximum stats

When your stats turn golden they have reached their maximum value and can only be increased by wearing items that increases them further (life and mana never turn golden). The table below lists the maximum stats for each character class assuming a naked character. Note that you don’t get any life or mana when you gain level 50.

| **Class**     | **Max Strength** | **Max Magic** | **Max Dexterity** | **Max Vitality** | **Max Life** | **Max Mana** |
|--------------|---------------:|-------------:|---------------:|---------------:|-----------:|-----------:|
| **Warrior**   | 250 | 50  | 60  | 100 | 316 | 98  |
| **Rogue**     | 55  | 70  | 250 | 80  | 201 | 173 |
| **Sorcerer**  | 45  | 250 | 85  | 80  | 138 | 596 |
| **Monk**      | 150 | 80  | 150 | 80  | 201 | 183 |
| **Bard**      | 120 | 120 | 120 | 100 | 221 | 231 |
| **Barbarian** | 255 | 0  | 55  | 150 | 416 | 0  |


The table below also shows the maximum stats, but this time when equipped with items that give the maximum stat increase. Note that it is *not* possible to reach those maximum values all at once. When two numbers are given the first one belongs to Diablo and the second one to Hellfire. The reason for this is the use of four new unique rings only available in Hellfire. It does *not* take into account the possibility of the use of two new unique jewelry in Hellfire that move life to/from mana.

| **Class**   | **Max Strength** | **Max Magic** | **Max Dexterity** | **Max Vitality** | **Max Life**  | **Max Mana**  |
|------------|:---------------:|:------------:|:--------------:|:--------------:|-------------:|-------------:|
| **Warrior**  | 425 / 485       | 225 / 285    | 225 / 285      | 265 / 325      | 796 / 916    | 533 / 568    |
| **Rogue**    | 230 / 290       | 245 / 305    | 415 / 475      | 245 / 305      | 681 / 741    | 690 / 718    |
| **Sorcerer** | 220 / 280       | 425 / 485    | 250 / 310      | 245 / 305      | 618 / 618    | 1196 / 1216  |
| **Monk**     | 385             | 315          | 375            | 305            | 741          | 728          |
| **Bard**     | 370             | 360          | 360            | 340            | 761          | 865          |
| **Barbarian**| 490             | 235          | 280            | 375            | 1091         | 470          |


### 2.1.3 Life and mana

Life is based on vitality while mana is based on magic. To calculate how much life and mana you have, use the formulas listed below.

| **Class**     | **Formula for Life Calculation**                                      | **Bonus** |
|--------------|------------------------------------------------------------------------|---------:|
| **Warrior**   | `(2 × Vit`<sub>`character`</sub>`) + (2 × Vit`<sub>`items`</sub>`) + (2 × clvl) + Life`<sub>`items`</sub>  | +18  |
| **Rogue**     | `(1 × Vit`<sub>`character`</sub>`) + (1.5 × Vit`<sub>`items`</sub>`) + (2 × clvl) + Life`<sub>`items`</sub> | +23  |
| **Sorcerer**  | `(1 × Vit`<sub>`character`</sub>`) + (1 × Vit`<sub>`items`</sub>`) + (1 × clvl) + Life`<sub>`items`</sub>  | +9   |
| **Monk**      | `(1 × Vit`<sub>`character`</sub>`) + (1.5 × Vit`<sub>`items`</sub>`) + (2 × clvl) + Life`<sub>`items`</sub> | +23  |
| **Bard**      | `(1 × Vit`<sub>`character`</sub>`) + (1.5 × Vit`<sub>`items`</sub>`) + (2 × clvl) + Life`<sub>`items`</sub> | +23  |
| **Barbarian** | `(2 × Vit`<sub>`character`</sub>`) + (2.5 × Vit`<sub>`items`</sub>`) + (2 × clvl) + Life`<sub>`items`</sub> | +18  |

| **Class**     | **Formula for Mana Calculation**                                      | **Bonus** |
|--------------|------------------------------------------------------------------------|---------:|
| **Warrior**   | `(1 × Mag`<sub>`character`</sub>`) + (1 × Mag`<sub>`items`</sub>`) + (1 × clvl) + Mana`<sub>`items`</sub>  | -1  |
| **Rogue**     | `(1 × Mag`<sub>`character`</sub>`) + (1.5 × Mag`<sub>`items`</sub>`) + (2 × clvl) + Mana`<sub>`items`</sub> | +5  |
| **Sorcerer**  | `(2 × Mag`<sub>`character`</sub>`) + (2 × Mag`<sub>`items`</sub>`) + (2 × clvl) + Mana`<sub>`items`</sub>  | -2  |
| **Monk**      | `(1 × Mag`<sub>`character`</sub>`) + (1.5 × Mag`<sub>`items`</sub>`) + (2 × clvl) + Mana`<sub>`items`</sub> | +5  |
| **Bard**      | `(1.5 × Mag`<sub>`character`</sub>`) + (1.75 × Mag`<sub>`items`</sub>`) + (2 × clvl) + Mana`<sub>`items`</sub> | +3  |
| **Barbarian** | `(1 × Mag`<sub>`character`</sub>`) + (1 × Mag`<sub>`items`</sub>`) + (0 × clvl) + Mana`<sub>`items`</sub> | +0  |

- Black Deaths (a zombie type of monster) can permanently decrease your life.
- You do not get any mana or life when reaching level 50 (use clvl=49 to get the correct result).
- Some shrines might permanently decrease your max mana (see chapter 5.6.5).
- If you are on level 16, you will not lose any of your items when you die.

### 2.1.4 Armor Class and To Hit

Both Armor Class (AC) and To Hit are based on your Dexterity. Below is a summary on how they are calculated. For more information about AC and To Hit, see chapter 5.6.5.

| **Armor Class Calculation** | **Formula** |
|---------------------------|-------------|
| **Warrior, Rogue, Sorcerer** | `(Dex ÷ 5) + AC`<sub>`items`</sub> |
| **Monk with Plate Armor** | `(Dex ÷ 5) + AC`<sub>`items`</sub> |
| **Monk with Mail Armor** | `(Dex ÷ 5) + AC`<sub>`items`</sub>` + (clvl ÷ 2)` |
| **Monk with Light Armor (Leather, etc.)** | `(Dex ÷ 5) + AC`<sub>`item`s`</sub>` + (2 × clvl)` |
| **Monk with No Armor** | `(Dex ÷ 5) + AC`<sub>`items`</sub>` + (2 × clvl)` |
| **Bard** | `(Dex ÷ 5) + AC`<sub>`items`</sub> |
| **Barbarian** | `(Dex ÷ 5) + AC`<sub>`items`</sub>` + (clvl ÷ 4)` |


- When calculating AC for a Monk, unique plate is treated as mail and unique mail as leather.
- Shields only give half AC (rounded up) to the Barbarian.


| **To Hit % Calculation** | **Formula** | **Notes** |
|-------------------------|-------------|------|
| **Character Screen** | `50 + (Dex ÷ 2) + ToHit`<sub>`items`</sub> | Displayed on the in-game character screen. |
| **Melee Attack** | `50 + (Dex ÷ 2) + ToHit`<sub>`items`</sub>` + clvl + bonus` | Used for melee combat calculations. |
| **Ranged Attack (Arrows)** | `50 + Dex + ToHit`<sub>`items`</sub>` + clvl + bonus - (distance² ÷ 2)` | Distance-based penalty applies. |
| **Magic vs Monster** | `50 + Mag - (2 × mlvl) + bonus` | Spell accuracy against monsters. |
| **Magic vs Player** | `50 + Mag - (2 × clvl<sub>target</sub>) + bonus` | Spell accuracy against other players. |
| **To Hit Penalty for Adjacent Quarter Damage** | `70 - (2 × clvl)` | Minimum value: 30. |


- All magic attacks will always check for To Hit, even for spells like Lightning and Fire Wall.
- A player is immune to its own spells with the exception of Fire Wall and Flame Wave.
- Fire Wall, Flame Wave and Ring of Fire will check for To Hit like magical traps against players including the caster (but not against monsters). See chapters 4.3 and 6.1.2.
- Distance is actually a time count. It goes up by 1 twenty times each second. Arrows always have a distance factor, even if they have extra fire or lightning. For more information see chapters 4.1.2.
- Note that the effects of some oils (see chapter 3.2.1) are only visible on the stats in the character screen. They don’t show up on the information about the item.
- In Diablo, the *bashing* series of suffixes also adds to your To Hit value but it will never show up on the character screen. The amount is always fixed for a specific item and within the range of the suffix. See chapter 3.4 for more information.
- The adjacent quarter damage To Hit penalty is subtracted from the normal To Hit for the two monsters adjacent to the one you attack. For an explanation of adjacent quarter damage see chapter 2.2.2.
- For a list of the bonuses, see the table below.
- To get the final chance of hitting you subtract the AC of the enemy (monster or player). See chapter 5.1 for information about monster’s AC. The AC is not subtracted if it is a magic attack.
- When the game checks if you have hit there is always a 5% chance that you will miss, no matter what the final modified To Hit is. In the same way there is also always a 5% chance to hit, no matter what the final modified To Hit is. See chapter 5.1 for information about monster’s chance of automatic hit (they never automatically miss).

The bonus in the above formulas refers to some *hidden* To Hit modifiers specific for each character class. They are listed in the table below but do not show up in the To Hit value you see on the character screen. For the blocking bonus see chapter 2.2.

| **Class**      | **Melee** | **Arrow** | **Magic** | **Blocking<sup>[^3]</sup>** |
|--------------|:-------:|:-------:|:-------:|:---------:|
| **Warrior**   | 20      | 10      | -       | 30        |
| **Rogue**     | -       | 20      | -       | 20        |
| **Sorcerer**  | -       | -       | 20      | 10        |
| **Monk**      | -       | -       | -       | 25        |
| **Bard**      | -       | 10      | 10      | 25        |
| **Barbarian** | -       | -       | -       | 30        |

[^3]: There exists a bug where the **blocking bonus is always 0**, except during the first game a character plays.


In the table below, maximum AC and To Hit for each character class is summarized. The columns for max values from max stats are maximum values without the use of any items that specifically add to AC and To Hit (only to Dex). When two numbers are given the first one belongs to Diablo and the second one to Hellfire. The reason is that there are some new unique rings only available in Hellfire. It also excludes any effects from oils and shrines that directly affect AC or To Hit. The values are, of course, excluding such things as clvl that is factored in for computing the real final To Hit.

| **Class**      | **Max AC Naked** | **Max To Hit Naked** | **Max AC from Maxed Stats** | **Max To Hit from Maxed Stats** | **Max AC** | **Max To Hit** |
|--------------|----------------:|------------------:|----------------------:|--------------------------:|---------:|------------:|
| **Warrior**   | 12               | 80               | 45 / 57               | 162 / 192                 | 349 / 401 | 392        |
| **Rogue**     | 50               | 175              | 83 / 95               | 257 / 287                 | 385 / 425 | 487        |
| **Sorcerer**  | 17               | 92               | 50 / 62               | 175 / 205                 | 350 / 390 | 405        |
| **Monk**      | 130<sup>[^4]</sup>         | 125              | 175<sup>[^4]</sup>              | 237                        | 419       | 437        |
| **Bard**      | 24               | 110              | 72                     | 230                        | 413       | 565        |
| **Barbarian**     | 23<sup>[^4]</sup>      | 77               | 56                     | 190                        | 370       | 390        |

[^4]: For a level 50 character.



## 2.2 Fighting

The main activity in Diablo and Hellfire is fighting. You either fight against the monsters or against other players.

This chapter will briefly explain how your characters stats and the items you wear affect your character while fighting.

For a more detailed explanation on battle between players and monsters, see chapter 5.6.5.


### 2.2.1 Getting hit

When someone or something attacks you, the first step is to see if it hits you or not. Formulas for the chance of hitting a player can be found in chapter 2.1.4 (players), 4.3 (traps) and 5.1 (monsters).

When you are hit by a melee weapon, an arrow, or magic (while not having any resistance), you will try to block the attack (in Hellfire you will try to block even if you have resistance). See chapter 4 for information about what spells can be blocked. To block the attack you must have a shield. A Monk can also block with a staff and with at least one hand bare. If you fail to block or you can’t block you will get hit, which will result in damage and the possibility of having to do a hit recovery (getting stunned). For formulas for monsters hitting players, see chapter 5.1.


**Blocking**

The chance of blocking is calculated according to:

| **Blocking Type**       | **Formula** |
|------------------------|--------------------------------------------------|
| **Blocking vs Monster** | `Dex + (2 × (clvl - mlvl)) + bonus` |
| **Blocking vs Player**  | `Dex + (2 × (clvl`<sub>`target`</sub>` - clvl`<sub>`attacker`</sub>`)) + bonus` |
| **Blocking vs Trap**    | `Dex + bonus` |


- There exists a bug so that the bonus is always 0, except during the first game a character play. For information about what the bonus should be, see table under To Hit %, chapter 2.1.4.
- You can only block while standing still or while doing a melee attack.
- Monsters can never block attacks against them.

**Modified damage received**

There are a few ways by which the damage done to a player is modified depending upon the target. Below is listed what those effects are and in what order they are applied. Note that not all effects are applicable to all situations.

| **Effect**          | **Description** |
|------------------|--------------|
| *of thieves*       | Having an item with this suffix will reduce any trap damage by 50%. In Hellfire, it will also reduce the damage from any magical or ranged attack from monsters by 50%. This effect is not cumulative if you have more than one item with the suffix. |
| - Damage Taken    | Having any item with a suffix that reduces damage (or in the case of a cursed suffix, increases it), will reduce any damage, even magical, done by a monster by the combined amount of all the suffixes you are wearing. Damage can never be reduced below 1 by this effect. |
| Reflect           | In Hellfire, the Reflect spell will reduce the amount of melee damage a monster does to a player by **20 to 29%**. |
| Player vs Player  | All magic damage is halved in **player versus player** attacks. This includes the damage by **Bone Spirit**, which will only reduce **1/6** of current life. |
| Resistance        | Having any item which gives you resistance will reduce any magical attack of the same type by the total resistance of that type you have. Maximum resistance is **75%**, which is shown with the letters **MAX**. |
| Mana Shield       | If you are using a **Mana Shield**, it will reduce the damage by **33%** in *Diablo* and by **(1/(3 × slvl) × 100%)** (if slvl is higher than 7, set slvl to 7) in *Hellfire*. In addition, it will remove mana instead of life. |

Checks for hit recovery are done between step 4 and 5 and will thus not be affected by the use of Mana Shield.


**Hit recovery**

When you are hit and don’t block it, you will take damage. If the damage is big enough, your character will go through a hit recovery animation; you are stunned, during which you can’t do anything. If you get hit again before you manage to hit back or move this repeats and you are stun locked and can’t react away (for information about entering a new location, see chapter 6.1.9). The hit recovery is initiated if the following conditions are met:

Any character except the Barbarian:	damage >= clvl

Barbarian:	`damage >= 1.25×clvl`

It is worth noticing that the check for hit recovery is made prior to any damage reduction due to using a Mana Shield. There are also some bugs regarding hit recovery while using Mana Shield. So while using a Mana Shield, in addition to the requirements above, damage must also be below your current life for you to be put into hit recovery:


Any character, except the Barbarian, using Mana Shield: `current life > damage >= clvl`

Barbarian using Mana Shield: `current life > damage >= 1.25×clvl`

The table below list the time, in seconds, it takes to block and to do a hit recovery for each character class. It also lists the effects of some specific suffixes that influence blocking or hit recovery. For more information on the suffixes, see chapter 3.2.2.

| **Class/Suffix** | **Blocking** | **Fast Block<sup>[^5]</sup>** | **Hit Recovery** | **of Balance** | **of Stability** | **of Harmony** |
| :- | :-: | :-: | :-: | :-: | :-: | :-: |
| **Warrior**   | 0.10 | 0.10 | 0.30 | 0.25 | 0.20 | 0.15<sup>[^7]</sup> |
| **Rogue**     | 0.20 | 0.10 | 0.35 | 0.30 | 0.25 | 0.20<sup>[^7]</sup> |
| **Sorcerer**  | 0.30 | 0.10 | 0.40 | 0.35 | 0.30 | 0.25<sup>[^7]</sup> |
| **Monk**      | 0.15 | 0.10 | 0.30 | 0.25 | 0.20 | 0.15 |
| **Bard**      | 0.20 | 0.10 | 0.35 | 0.30 | 0.25 | 0.20 |
| **Barbarian** | 0.10 | 0.10 | 0.30<sup>[^6]</sup> | 0.25<sup>[^6]</sup> | 0.20 | 0.15 |

[^5]: Fast block indicates the use of an item with the *of Blocking* suffix or a unique item with the **fast block** effect.  
[^6]: The Barbarian has built-in *of Stability* while using an **axe or a club**, and the hit recovery time in those cases is **0.20**, unless he is using an item *of Harmony*.  
[^7]: In *Diablo* (but not in *Hellfire*), equipping three or more items that together have all three suffixes (*of Balance, of Stability,* and *of Harmony*) will **reduce hit recovery time by 0.05 seconds** to:  
- **Warrior**: 0.10
- **Rogue**: 0.15
- **Sorcerer**: 0.20
Just equipping two items with different suffixes **has no effect**.  


### 2.2.2 Damage done

Damage done by players is composed of two parts, character damage and weapon damage. The character damage is based on your character’s stats and can be calculated with the formulas below. To that damage you add the damage of any weapon, or weapons in the case of the Bard, you have equipped. For information about damage from spells, see chapter 4.

| **Class**     | **Bow Character Damage Formula**             |
|--------------|----------------------------------------------|
| **Warrior**   | `(Str × clvl) / 200`                         |
| **Rogue**     | `((Str + Dex) × clvl) / 200`                 |
| **Sorcerer**  | `(Str × clvl) / 200`                         |
| **Monk**      | `((Str + Dex) × clvl) / 600`                 |
| **Bard**      | `((Str + Dex) × clvl) / 500`                 |
| **Barbarian** | `(Str × clvl) / 600`                         |

| **Class**      | **Melee Character Damage Formula**                  |
|---------------|----------------------------------------------------|
| **Warrior**   | `(Str × clvl) / 100`                                |
| **Rogue**     | `((Str + Dex) × clvl) / 200`                        |
| **Sorcerer**  | `(Str × clvl) / 100`                                |
| **Monk** (staff or bare-handed) | `((Str + Dex) × clvl) / 150`  |
| **Monk** (other weapons)        | `((Str + Dex) × clvl) / 300`  |
| **Bard** (at least one sword)   | `((Str + Dex) × clvl) / 150`  |
| **Bard** (any weapon except sword) | `(Str × clvl) / 100`       |
| **Barbarian** (axes and clubs)  | `(Str × clvl) / 75`           |
| **Barbarian** (except axes and clubs) | `(Str × clvl) / 100`    |
| **Extra Bonus** (Barbarian without shield) | `(Vit × clvl) / 100` |

- All Bow character damage is doubled for player versus player except for Rogues.
- There are quite a few bugs associated with fire and lightning arrows which makes them often deal erroneous damage (way too high or no additional damage at all). For more information, see chapter 6.1.6.
- For the Monk, *other weapons* include just having a shield equiped.
- For the Bard, damage enhancements from the *king’s* and *merciless* series of prefixes (+% damage) are added together if they occur on both weapons. It is then applied to the sum of both weapons’ damage. Damage from enhancements of the *slaughter* series is only applicable to the weapon it comes on.
- The Barbarian can use a maul and two-handed swords in one hand.
- The Barbarian’s bonus for not using a shield does not apply if he is using a staff.
- Magic damage is halved in player versus player.

As already stated, you add weapon damage to the damage above to get the final damage. Some ”weapons” don’t have any damage listed and are given below. Shield damage only applies if you wear no other weapon and hand/feet damage only applies if you have no other weapon or shield equipped.

| **Special "Weapon"**            | **Damage Formula**             |
|---------------------------------|------------------------------|
| **Hands/Feet (except for Monk)** | `1`                            |
| **Shield (except for Monk)**     | `1 - 3`                        |
| **Feet or Shield (for Monk)**    | `clvl / 2 - clvl`              |


- The special damage for a Monk using his feet or just a shield will never be below those values listed for non Monks (min and max damage checked separately).

The table below shows maximum naked character damage for various types of weapons. As character damage is based on a character’s level, it (in the table below) only applies to level 50 characters. On top of the listed damage you should then add weapon damage and possibly modify either or both character damage and weapon damage.

| **Class**     | **Bare-handed**<sup>[^8]</sup> | **Swords** | **Clubs** | **Axes** | **Bows** | **Staves** |
|--------------|------------------:|---------:|---------:|---------:|---------:|---------:|
| **Warrior**   | 125              | 125      | 125      | 125      | 62       | 125      |
| **Rogue**     | 76               | 76       | 76       | 76       | 76       | 76       |
| **Sorcerer**  | 22               | 22       | 22       | 22       | 11       | 22       |
| **Monk**      | 100              | 50       | 50       | 50       | 25       | 100      |
| **Bard**      | 60               | 80       | 60       | 60       | 40       | 60       |
| **Barbarian** | 202              | 202<sup>[^9]</sup> | 245<sup>[^9]</sup> | 245 | 21 | 202 |

[^8]: To this value, you should add the "weapon" damage of bare hands/feet.  
[^9]: Subtract 75 if using a shield at the same time.

**Things that affect damage done**

Various things affect the amount of damage a character does. Mostly those things are related to various prefixes, suffixes, or unique properties, but a few exceptions exist. Critical Hits are explained below and type of monster is explained in chapter 5.1. The modifications to the damage can either modify weapon damage alone or your total damage; that is, both your character damage and your weapon damage. In the table below is a list of all modifications that apply to your total damage. They are each cumulative with each other and are applied on top of each other.

| **Reason**                           | **Effect**                          |
|--------------------------------------|-------------------------------------|
| **Critical Hit**                     | Double damage                      |
| **Monster type**                     | Half damage or increased damage by 50% |
| **+200% damage against demons**<sup>[^10]</sup> | Triple damage                  |
| **Suffix: *of Devastation***          | Triple damage                      |
| **Prefix: *Jester’s***                | Between zero and six times the damage |
| **Suffix: *of Peril***                | Double damage                      |

[^10]: Does not work on bows.

**Critical Hit**

Warriors and Barbarians have the ability to do a critical hit while doing melee attacks. The chance for a critical hit is clvl% and a critical hit does twice the damage.


**Adjacent quarter damage**

All the new characters in Hellfire have the ability to hit up to three monsters at a time in certain circumstances. It works by dealing ¼th of the damage to the monsters beside the one you swing at. A separate To Hit check is done for each of those monsters. The To Hit is lowered accordingly to the formula in chapter 2.1.4 under To Hit %. The adjacent quarter damage is done in the following situations:

- A Monk using a staff.

- A Bard using two swords.

- A Barbarian using an axe, a two-handed sword or a maul, without having a shield equipped at the same time.

Adjacent quarter damage can never hit a player, only monsters.


### 2.2.3 Weapon speed

A very important factor is how quickly you swing different weapons. A faster weapon not only causes more damage per unit of time, but also helps you stun lock your enemies more easily. Below are listed values for how quickly each character class swings each weapon. Only the Barbarian has different weapon speed for clubs and swords, for all other classes they are identical. The value given is the time in seconds it takes to do one swing.

| **Weapon**      | **Suffix**           | **Warrior** | **Rogue** | **Sorcerer** | **Monk** | **Bard** | **Barbarian** |
|---------------|-------------------|:----------:|:--------:|:----------:|:------:|:------:|:----------:|
| **Swords/Clubs** | Normal & Readiness | 0.45 | 0.50 | 0.60 | 0.60 | 0.50 | 0.45 / 0.40 |
|                 | Swiftness         | 0.40 | 0.45 | 0.55 | 0.55 | 0.45 | 0.40 / 0.35 |
|                 | Speed & Haste     | 0.35 | 0.40 | 0.50 | 0.50 | 0.40 | 0.35 / 0.30 |
| **Axes**        | Normal & Readiness | 0.50 | 0.65 | 0.80 | 0.70 | 0.65 | 0.40 |
|                 | Swiftness         | 0.45 | 0.60 | 0.75 | 0.65 | 0.60 | 0.35 |
|                 | Speed & Haste     | 0.40 | 0.55 | 0.70 | 0.60 | 0.55 | 0.30 |
| **Staves**      | Normal & Readiness | 0.55 | 0.55 | 0.60 | 0.40 | 0.55 | 0.55 |
|                 | Swiftness         | 0.50 | 0.50 | 0.55 | 0.35 | 0.50 | 0.50 |
|                 | Speed & Haste     | 0.45 | 0.45 | 0.50 | 0.30 | 0.45 | 0.45 |
| **Bows**        | Normal & Readiness | 0.55 | 0.35 | 0.80 | 0.70 | 0.55 | 0.55 |
|                 | Swiftness         | 0.50<sup>[^11]</sup> | 0.30<sup>[^11]</sup> | 0.75<sup>[^11]</sup> | 0.70 | 0.55 | 0.55 |
| **Other**       | Shield            | 0.45 | 0.50 | 0.45 | 0.35 | 0.50 | 0.45 |
|                 | Bare hands & feet | 0.45 | 0.50 | 0.60 | 0.35 | 0.50 | 0.45 |
|                 | Spell             | 0.70 | 0.60 | 0.40 | 0.65 | 0.60 | 0.70 |

[^11]: In Hellfire Readiness and Swiftness make the arrows fly faster, the time is still the same as for Normal.

The speed with which the arrows travel also varies with character class. Below is given the speed of arrows for all characters as well as some other factors affecting the speed of an arrow. The actual value is just a value given for comparison with other traveling effects, such as spells. The higher the number, the faster it will be. Arrows from monsters will always have a speed of 32. For the speed of arrows from traps, see chapter 4.3.

| **Arrow or Other Effect**     | **Warrior, Monk**  | **Rogue**  | **Sorcerer, Bard, Barbarian** |
|-----------------------------|:-----------------:|:---------:|:-------------------------:|
| **Normal Arrow**            | 32 + (clvl-1)/8   | 32 + (clvl-1)/4  | 32  |
| **Fire and Lightning Arrow** | 31 + clvl/8       | 31 + clvl/4      | 32  |
| **Random Speed Arrows**      | 16 + Rnd[32] + (clvl-1)/8  | 16 + Rnd[32] + (clvl-1)/4  | 16 + Rnd[32]  |
| **Readiness**<sup>[^12]</sup> | +1  | +1  | +1  |
| **Swiftness**<sup>[^12]</sup> | +2  | +2  | +2  |

[^12]: Will only affect the arrow speed in *Hellfire*. In *Diablo*, it will affect the weapon speed instead.


## 2.3 Timing information

This chapter summarizes all timing information for players. For blocking and hit recovery, this information can also be found in chapter 2.2, and for weapon speed, it can also be found in chapter 2.2.3. For monsters all timing information can be found in chapter 5.3. The table below summarizes all timing information for the different character classes.

| **Class**     | **Walk Speed** | **Hit Recovery Speed** | **Blocking Speed**<sup>[^13]</sup> | **Swing Speed** | **Hit Time**<sup>[^14]</sup> |
|--------------|:--------------:|:---------------------:|:--------------------------------:|:--------------:|:----------------:|
| **Warrior**   | 0.40  | 0.30  | 0.10  | See chap. 2.2.3  | Swing speed<sup>[^15]</sup>  |
| **Rogue**     | 0.40  | 0.35  | 0.20  | See chap. 2.2.3  | Swing speed<sup>[^15]</sup>  |
| **Sorcerer**  | 0.40  | 0.40  | 0.30  | See chap. 2.2.3  | Swing speed<sup>[^15]</sup>  |
| **Monk**      | 0.40  | 0.30  | 0.15  | See chap. 2.2.3  | Swing speed<sup>[^15]</sup>  |
| **Bard**      | 0.40  | 0.35  | 0.20  | See chap. 2.2.3  | Swing speed<sup>[^15]</sup>  |
| **Barbarian** | 0.40  | 0.30<sup>[^16]</sup>  | 0.10  | See chap. 2.2.3  | Swing speed<sup>[^15]</sup>  |

[^13]: For more information, see chapter **2.2**.  
[^14]: The **hit time** (or rather the time at which the spell effect is initialized) for a player is identical to the **swing speed** (that is, at the last frame) except for **non-targeted spells** (those for which you don’t target a specific monster or player) which have a **0.05 seconds faster hit time**.  
[^15]: The swing speed is of course the one for **casting a spell**.  
[^16]: The **Barbarian** has built-in *stability* while using an **axe** or a **club**, unless wearing an item that affects **hit recovery** in a better way.  



## 2.4 Skills

Each character class has a skill it can perform. For most classes, the skill improves as they gain levels. The various skills are summarized below.

| **Class**     | **Skill**            | **Effect**  |
|--------------|----------------------|-----------------------------------------------|
| **Warrior**   | Repair Items         | Durability loss decreases as level increases. |
| **Rogue**     | Disarm Traps         | Success chance increases with higher Dexterity. |
| **Sorcerer**  | Recharge Staves      | Charge loss decreases as level increases. |
| **Monk**      | Search               | Reveals nearby objects and hidden doors. |
| **Bard**      | Identify             | Allows identification of items. |
| **Barbarian** | Rage                 | Stat boost increases with level, but so do penalties during lethargy. |

**Warrior**

The skill of the Warrior works in the following way:

### **Item Repair Formula**
1. **If** current durability is equal to max durability, **exit**.
2. **Set** `x = 0`
3. **Add** `(clvl + Rnd[clvl])` to `x`
4. **Calculate** `y = [MaxDur / (clvl + 9)]`, **if** `y < 1`, **set** `y = 1`
5. **Decrease** `MaxDur` by `y`
6. **If** `x + CurDur < MaxDur`, **goto step 3**.
7. **Set** `CurDur = MaxDur`

If max durability ever reaches 0, the item is of course destroyed.

**Rogue**

The skill of the Rogue works in the following way:

### **Trap Disarm Formula**
1. **Calculate** `x = (2 × Dex) - (5 × dlvl)`
2. **If** `x > Rnd[100]`, **trap is disarmed**

**Sorcerer**

The skill of the Sorcerer works in the following way:

### **Staff Recharge Formula**
1. **If** `CurChrg` (current charges) **is equal to** `MaxChrg` **or** `MaxChrg` **is 0**, **exit**.
2. **Calculate** `x = Rnd[clvl / qlvl(book)] + 1`
3. **Decrease** `MaxChrg` by `1`
4. **Add** `x` to `CurChrg`
5. **If** `CurChrg < MaxChrg`, **go to** Step 3.
6. **Set** `CurChrg = MaxChrg`

It seems strange that it is not the qlvl of the spell on a staff, and I wonder what happens for a spell like resurrect where the qlvl value is -1. Any information about this is appreciated.

**Monk**

The skill of the Monk is identical to the spell with the same name.

**Bard**

The skill of the Bard is identical to the spell with the same name.

**Barbarian**

The skill of the Barbarian works in the following way:

### **Rage Formula**
1. **For 12 seconds**, gain:
   - `+ (2 × clvl)` to **Strength** and **Vitality**
   - `+ (1.5 × clvl)` to **Dexterity**
2. **For the next 12 seconds** (lethargy phase), **lose** the **same** amount from **Strength, Dexterity, and Vitality** (calculated from normal values).
3. **Afterwards**, lose `(2 × Vit)` **life**.
   - 🐞 **Bug:** Clicking any item in your inventory **restores** lost life.


## 2.5 Starting equipment

All character classes start the game with some items. These items are listed in the table below. Note that the prices for these items sometimes differ from the ones of normal items of the same type. The sword that the Bard starts with seems not to be available otherwise in the game.

| **Class**       | **Weapon**                            | **Price** | **Gold** | **Potions** |
|---------------|----------------------------------|--------:|--------:|-----------|
| **Warrior**   | Short Sword                     | 50      | 100     | 2 Potions of Healing |
|               | Club                             | 20      |         |           |
|               | Buckler                          | 50      |         |           |
| **Rogue**     | Short Bow                        | 100     | 100     | 2 Potions of Healing |
| **Sorcerer** *(Diablo)*  | Short Staff of Charged Bolt<sup>[17]</sup> *(40 charges)* | 520      | 100     | 2 Potions of Mana |
| **Sorcerer** *(Hellfire)* | Short Staff of Mana<sup>[17]</sup> *(18 charges)*  | 520      | 100     | 2 Potions of Healing |
| **Monk**      | Short Staff                      | 20      | 100     | 2 Potions of Healing |
| **Bard**      | Sword                            | 50      | 100     | 2 Potions of Healing |
|               | Dagger                           | 20      |         |           |
| **Barbarian** | Spiked Club                      | 225     | 100     | 2 Potions of Healing |
|               | Buckler                          | 50      |         |           |

[^17]: These starting staves are special in that they are *not* composed of a staff with a spell on it, but are unique base items that have the spell built into them. The prices listed are for these base items, and no additional cost is added for the spell itself.


## 2.6 Experience points

Each time you kill a monster you have a chance of receiving experience points. You receive experience for killing a monster as long as your own level is below the mlvl+10 (see chapter 5.2 and 5.6.3 for more information about mlvl and experience points). In multi player, each person that fulfills one of following requirements is entitled to receive experience points when a monster is killed.

- Killing the monster (both in melee and with spell).
- Dealing damage to the monster in either melee or with a bow (regardless of any extra fire or lightning damage even if the monster is resistant or immune to it).
- Dealing damage to the monster with a spell to which the monster is *not* resistant or immune.
- Having your golem kill or deal damage to the monster.
- Having used Telekinesis on the monster (Snotspill, Gharbad the Weak, Zhar the Mad, Warlord of Blood, Lachdanan, Arch-Bishop Lazarus, Blackjade and Red Vex are all immune to Telekinesis though).

In all cases you must be alive at the moment the monster dies and you must never have left the level in-between fulfilling any of the requirements above and the monster dying, or you will not receive any experience points. The requirement of dealing damage is fulfilled even if for some reason the damage itself is reduced to below 1 point of damage (theoretically even 0 damage will be enough). Stone Cursing a monster will *not* be enough to receive any experience points. A Guardian is treated as a normal fire spell for the purpose of deciding if the owning player is entitled to experience points. In Hellfire a Berserk monster will *not* give you experience points for the other monsters it kills.

In single player you are then rewarded the amount of experience points according to the formula below. In multi player the same formula applies, but the base experience points of the monster are first divided by the number of players that are entitled to receive experience points, which is not necessarily all players in the game.

`base × (1.0 + 0.1×(mlvl - clvl))`

So when your clvl is 10 levels higher than the mlvl, you no longer receive any experience for killing it. *Base* refers to the base experience points found in chapter 5.2 modified for the number of players that are entitled for experience points according to the explanation above.

The maximum experience you can obtain for killing a monster in multi player (both in Diablo and Hellfire) is 200×clvl or the total experience points needed for advancing to the next clvl divided by 20, whichever is the lowest. In single player there is no such a cap. With the added possibility of difficulty levels in single player in Hellfire along with no character level requirements for harder difficulty levels, you can get quite a lot of experience points when killing monsters. In Hellfire, there are also some shrines that affect your experience points (see chapter 7).

Listed below are the required experience points for each level. You will also find the maximum experience point you can be given for a monster at that character level (see above for information about this cap). Listed is also the minimum number of monsters you need to kill to reach the next level assuming you get maximum experience for each kill. This is in practice impossible and even theoretically impossible at low levels. The *Total Kills* column is simply the total minimum number of monsters needed to kill to reach a specific level and is valid for Diablo only as there is no limit on the number of experience points given for killing a monster in Hellfire. Note that the numbers under *Increase*, *Increase %, Kills,* and *Total Kills* are all how much is needed for the *next* level.

| **Level** | **Experience** | **Increase** | **Increase in %** | **Max Exp.<sup>[^18]</sup>** | **Kills** | **Total Kills** |
|---------:|-------------:|-------------:|------------------:|-----------------:|------:|------------:|
| 1  | 0             | 2,000        | n/a      | 100   | 20  | 20    |
| 2  | 2,000         | 2,620        | 131.0%   | 231   | 12  | 32    |
| 3  | 4,620         | 3,420        | 74.0%    | 402   | 9   | 41    |
| 4  | 8,040         | 4,449        | 55.3%    | 624   | 7   | 48    |
| 5  | 12,489        | 5,769        | 46.2%    | 912   | 7   | 55    |
| 6  | 18,258        | 7,454        | 40.8%    | 1,200 | 6   | 61    |
| 7  | 25,712        | 9,597        | 37.3%    | 1,400 | 7   | 68    |
| 8  | 35,309        | 12,313       | 34.9%    | 1,600 | 8   | 76    |
| 9  | 47,622        | 15,742       | 33.1%    | 1,800 | 9   | 84    |
| 10 | 63,364        | 20,055       | 31.7%    | 2,000 | 11  | 95    |
| 11 | 83,419        | 25,460       | 30.5%    | 2,200 | 12  | 106   |
| 12 | 108,879       | 32,207       | 29.6%    | 2,400 | 14  | 120   |
| 13 | 141,086       | 40,597       | 28.8%    | 2,600 | 16  | 135   |
| 14 | 181,683       | 49,392       | 27.2%    | 2,800 | 18  | 153   |
| 15 | 231,075       | 82,581       | 35.7%    | 3,000 | 28  | 181   |
| 16 | 313,656       | 110,411      | 35.2%    | 3,200 | 35  | 215   |
| 17 | 424,067       | 147,123      | 34.7%    | 3,400 | 44  | 258   |
| 18 | 571,190       | 195,379      | 34.2%    | 3,600 | 55  | 313   |
| 19 | 766,569       | 258,585      | 33.7%    | 3,800 | 69  | 381   |
| 20 | 1,025,154     | 341,073      | 33.3%    | 4,000 | 86  | 466   |
| 21 | 1,366,227     | 448,341      | 32.8%    | 4,200 | 107 | 573   |
| 22 | 1,814,568     | 587,327      | 32.4%    | 4,400 | 134 | 706   |
| 23 | 2,401,895     | 766,756      | 31.9%    | 4,600 | 167 | 873   |
| 24 | 3,168,651     | 997,549      | 31.5%    | 4,800 | 208 | 1,081 |
| 25 | 4,166,200     | 1,293,323    | 31.0%    | 5,000 | 259 | 1,340 |
| 26 | 5,459,523     | 1,670,973    | 30.6%    | 5,200 | 322 | 1,661 |
| 27 | 7,130,496     | 2,151,378    | 30.2%    | 5,400 | 399 | 2,059 |
| 28 | 9,281,874     | 2,760,218    | 29.7%    | 5,600 | 493 | 2,552 |
| 29 | 12,042,092    | 3,528,939    | 29.3%    | 5,800 | 609 | 3,161 |
| 30 | 15,571,031    | 4,495,869    | 28.9%    | 6,000 | 750 | 3,910 |
| 31 | 20,066,900    | 5,707,505    | 28.4%    | 6,200 | 921 | 4,831 |
| 32 | 25,774,405    | 7,219,994    | 28.0%    | 6,400 | 1,129 | 5,959 |
| 33 | 32,994,399    | 9,100,803    | 27.6%    | 6,600 | 1,379 | 7,338 |
| 34 | 42,095,202    | 11,430,609   | 27.2%    | 6,800 | 1,681 | 9,019 |
| 35 | 53,525,811    | 14,305,407   | 26.7%    | 7,000 | 2,044 | 11,063 |
| 36 | 67,831,218    | 17,838,843   | 26.3%    | 7,200 | 2,478 | 13,540 |
| 37 | 85,670,061    | 22,164,762   | 25.9%    | 7,400 | 2,996 | 16,536 |
| 38 | 107,834,823   | 27,439,976   | 25.4%    | 7,600 | 3,610 | 20,146 |
| 39 | 135,274,799   | 33,847,210   | 25.0%    | 7,800 | 4,340 | 24,486 |
| 40 | 169,122,009   | 41,598,222   | 24.6%    | 8,000 | 5,200 | 29,685 |
| 41 | 210,720,231   | 50,937,022   | 24.2%    | 8,200 | 6,212 | 35,897 |
| 42 | 261,657,253   | 62,143,167   | 23.7%    | 8,400 | 7,398 | 43,295 |
| 43 | 323,800,420   | 75,535,020   | 23.3%    | 8,600 | 8,784 | 52,078 |
| 44 | 399,335,440   | 91,472,909   | 22.9%    | 8,800 | 10,395 | 62,473 |
| 45 | 490,808,349   | 110,362,065  | 22.5%    | 9,000 | 12,263 | 74,735 |
| 46 | 601,170,414   | 132,655,203  | 22.1%    | 9,200 | 14,420 | 89,154 |
| 47 | 733,825,617   | 158,854,605  | 21.6%    | 9,400 | 16,900 | 106,054 |
| 48 | 892,680,222   | 190,228,390  | 21.3%    | 9,600 | 19,816 | 125,869 |
| 49 | 1,082,908,612 | 227,798,497  | 21.0%    | 9,800 | 23,245 | 149,114 |
| 50 | 1,310,707,109 | 272,788,700  | 20.8%    | 10,000 | 27,279 | 176,393 |
| **MAX** | **1,583,495,809** | **-** | **-** | **-** | **-** | **-** |

[^18]: This cap only applies to multiplayer. In single-player, there is no such cap.


Note that when you reach level 50, you don’t get any life or mana. Your other stats are updated correctly, though. After reaching level 50, you still receive experience points for killing monsters until you reach enough experience points for MAX (see below). Reaching MAX has no effect at all (apart from not being able to get any more experience of course).


## 2.7 Character level restrictions

There are a few occasions in the game where you need to have a certain character level to be allowed to access a certain difficulty or dungeon level. This chapter gives you information about those restrictions and when they apply.


**Dungeon levels**

In single player you can only enter the church when you start a new game. To access the other dungeons you have to work you way down through the dungeon levels before the entrances to the catacombs, caves, and hell open up. In Hellfire, the game will remember when an area has been opened up, and thus it will be open even if you restart a game.

In multi player, all areas are accessible from town right away, but you can go down into them only if you have reached a certain character level. The table below summarizes at what character level you can access the different areas. Even if your level is too low, it is still possible to enter an area if someone opens a portal for you.

| **Dungeon Area** | **clvl Needed to Enter<sup>[^19]</sup>** |
|-----------------|-------------------:|
| Church         | 1   |
| Catacombs     | 8   |
| Caves         | 13  |
| Hell          | 17  |
| Hive          | 15  |
| Crypt        | 15  |

[^19]: There is no requirement if you enter a level by going through a portal.



**Difficulty levels**

The table below summarizes at what character level you can enter different difficulty levels.

| **Game Type** | **Normal** | **Nightmare** | **Hell** |
|--------------|:---------:|-------------:|---------:|
| Diablo Single Player | 1  | n/a<sup>[^20]</sup> | n/a<sup>[^20]</sup> |
| Diablo Multi Player (IPX and Battle.net) | 1  | 20  | 30  |
| Diablo Modem and Direct Connection Game | 1  | 20/1<sup>[^21]</sup>  | 30/1<sup>[^21]</sup>  |
| Hellfire Single Player | 1  | 1  | 1  |
| Hellfire Multi Player (IPX and Kali) | 1  | 20  | 30  |
| Hellfire Modem and Direct Connection Game | 1  | 20/1<sup>[^21]</sup>  | 30/1<sup>[^21]</sup>  |

[^20]: It is available in the PlayStation version. Also, see chapter **2.7.1** for a way to play Single Player with different difficulties.

[^21]: The creator must be **level 20 or 30**, but anyone joining can be of any level.



### 2.7.1 Single player difficulty levels

In Hellfire you can choose to play nightmare and hell difficulty games in single player as well as in multi player. In Diablo this is not possible. However, there is a way to make the game behave as if you are playing nightmare or hell difficulty even in single player. This way monsters, for example, will have multi player stats, gold, and items drop according to the higher difficulty and so on.

To do this, first start a multi player game with the chosen difficulty. Exit it, and then start a single player game without first quitting Diablo. It will be created according to the difficulty level you chose in your last multi player game.


## 2.8 Character names

When you create a character, you also have to give it a name. Depending on if it is a single or multi player character, the characters that are allowed to use in the name differ slightly. The table below summarize all allowed characters.

| **Game Type**  | **Allowed Characters in Name** |
|--------------|--------------------------------------------|
| Any  | 0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ |
| Single Player | `!@$(){}[]=+`~^-’.:;\_|”#%&/?\*,<> SPACE` + localized characters<sup>[^22]</sup> |
| Multi Player  | `!@$(){}[]=+`~^-’.:;\_|` |

[^22]: By "localized characters," we mean characters specific to **various non-English languages**. Examples include: **å, ä, ö, ü, â, ã, ï**, and many others.  
These characters can still be entered when creating a character, but an **error message** will appear upon finalizing the name.


# 3. Items

Items play a very important role in Diablo and come in many variants. This chapter will deal with the many aspects of items. Armor and weapons can generally be said to consist of a base item, and to it you can add a prefix and/or a suffix or nothing at all and leave it as a non magical item. The item can also be a unique item instead, in which case it can have up to 6 different properties but it is still based on one of the base items. Rings and amulets work in a similar way but must always have at least one prefix or suffix, or be unique. There exist no non magical rings or amulets.

Books and oils also work in a similar way, as they consist of the base item *book of* and *oil of,* to which you then add either a spell or an oil type (for exceptions to oils see chapter 3.2.1). Scrolls, on the other hand, are each single base items and do not consist of the base item plus a spell as books do. Finally we have potions, elixirs, and runes that are all base items. In many tables in this chapter there is a reference to a qlvl. That level is used by the game when creating items; see chapter 3.8 and 3.9. Information about qlvl and occurrences of prefixes and suffixes initially came from Bostic.


## 3.1 Armor, weapons and jewelry

In the tables below are listed all the base items you can equip in the game. They can be found in the dungeons or bought from Griswold, Adria and Wirt. Jewelry can only be bought in single player, never in multi player. Listed are also all those base items upon which the quest items are based. Those special quest base items cannot be found otherwise in the game.

### Armor<sup>[^23]</sup>

| **Type**                  | **Armor Class** | **Durability** | **Requirements** | **Price** | **qlvl** |
|---------------------------|--------------:|--------------:|----------------:|---------:|--------:|
| Rags                      | 2 - 6        | 6            | -               | 5       | 1       |
| Cape                      | 1 - 5        | 12           | -               | 10      | 1       |
| Cloak                     | 3 - 7        | 18           | -               | 40      | 2       |
| Robe                      | 4 - 7        | 24           | -               | 75      | 3       |
| Quilted Armor             | 7 - 10       | 30           | -               | 200     | 4       |
| Leather Armor             | 10 - 13      | 35           | -               | 300     | 6       |
| Hard Leather Armor        | 11 - 14      | 40           | -               | 450     | 7       |
| Studded Leather Armor     | 15 - 17      | 45           | 20 Str          | 700     | 9       |
| Ring Mail                 | 17 - 20      | 50           | 25 Str          | 900     | 11      |
| Chain Mail               | 18 - 22      | 55           | 30 Str          | 1,250   | 13      |
| Scale Mail                | 23 - 28      | 60           | 35 Str          | 2,300   | 15      |
| Splint Mail               | 30 - 35      | 65           | 40 Str          | 3,250   | 17      |
| Breast Plate              | 20 - 24      | 80           | 40 Str          | 2,800   | 16      |
| Plate Mail<sup>[^24]</sup>  | 42 - 50      | 75           | 60 Str          | 4,600   | 19      |
| Field Plate<sup>[^24]</sup> | 40 - 45      | 80           | 65 Str          | 5,800   | 21      |
| Gothic Plate              | 50 - 60      | 100          | 80 Str          | 8,000   | 23      |
| Full Plate Mail           | 60 - 75      | 90           | 90 Str          | 6,500   | 25      |

[^23]: Armor can be divided into **three different categories**:
   - **Light**: Rags → Studded Leather Armor  
   - **Medium**: Ring Mail → Splint Mail  
   - **Heavy**: Breast Plate → Full Plate Mail  
   Each category gives your character a **different look**.
[^24]: These items share the **same in-game appearance**.


### Axes<sup>[^25]</sup>

| **Type**      | **Damage** | **Durability** | **Requirements** | **Price** | **qlvl** |
|--------------|----------:|--------------:|----------------:|---------:|--------:|
| Small Axe    | 2 - 10   | 24           | -               | 150      | 2       |
| Axe          | 4 - 12   | 32           | 22 Str          | 450      | 4       |
| Large Axe    | 6 - 16   | 40           | 30 Str          | 750      | 6       |
| Broad Axe    | 8 - 20   | 50           | 50 Str          | 1,000    | 8       |
| Battle Axe   | 10 - 25  | 60           | 65 Str          | 1,500    | 10      |
| Great Axe    | 12 - 30  | 75           | 80 Str          | 2,500    | 12      |

[^25]: All **axes** are **two-handed** weapons.


### Bows<sup>[^26]</sup>

| **Type**             | **Damage** | **Durability** | **Requirements**         | **Price** | **qlvl** |
|----------------------|----------:|--------------:|------------------------:|---------:|--------:|
| Short Bow           | 1 - 4     | 30           | -                        | 100      | 1       |
| Long Bow<sup>[^27]</sup>      | 1 - 6     | 35           | 25 Str, 30 Dex         | 250      | 5       |
| Hunter’s Bow<sup>[^27]</sup>  | 2 - 5     | 40           | 20 Str, 35 Dex         | 350      | 3       |
| Composite Bow       | 3 - 6     | 45           | 25 Str, 40 Dex         | 600      | 7       |
| Short Battle Bow    | 3 - 7     | 45           | 30 Str, 50 Dex         | 750      | 9       |
| Long Battle Bow<sup>[^28]</sup> | 1 - 10    | 50           | 30 Str, 60 Dex         | 1,000    | 11      |
| Short War Bow       | 4 - 8     | 55           | 35 Str, 70 Dex         | 1,500    | 15      |
| Long War Bow<sup>[^28]</sup>  | 1 - 14    | 60           | 45 Str, 80 Dex         | 2,000    | 19      |

[^26]: All **bows** are **two-handed** weapons.  
[^27]: These items have the **same picture**.  
[^28]: These items have the **same picture**.


### Clubs

| **Type**          | **Damage** | **Durability** | **Requirements** | **Price** | **qlvl** |
|-------------------|----------:|--------------:|----------------:|---------:|--------:|
| Club            | 1 - 6      | 20            | -                | 20       | 1       |
| Spiked Club     | 3 - 6      | 20            | 18 Str           | 225      | 4       |
| Mace            | 1 - 8      | 32            | 16 Str           | 200      | 2       |
| Morning Star    | 1 - 10     | 40            | 26 Str           | 300      | 3       |
| Flail           | 2 - 12     | 36            | 30 Str           | 500      | 7       |
| War Hammer      | 5 - 9      | 50            | 40 Str           | 600      | 5       |
| Maul<sup>[^29]</sup>         | 6 - 20     | 50            | 55 Str           | 900      | 10      |

[^29]: This weapon is **two-handed**, except for the **Barbarian**.


### Helms

| **Type**       | **Armor Class** | **Durability** | **Requirements** | **Price** | **qlvl** |
|---------------|--------------:|--------------:|----------------:|---------:|--------:|
| Cap          | 1             | 3             | -                | 15       | 1       |
| Skull Cap    | 2             | 4             | -                | 25       | 4       |
| Helm         | 4             | 6             | 25 Str           | 40       | 8       |
| Full Helm    | 6             | 8             | 35 Str           | 90       | 12      |
| Crown        | 8 - 12        | 40            | -                | 200      | 16      |
| Great Helm   | 10 - 15       | 60            | 50 Str           | 400      | 20      |


### Shields

| **Type**         | **Armor Class** | **Durability** | **Requirements** | **Price** | **qlvl** |
|----------------|--------------:|--------------:|----------------:|---------:|--------:|
| Buckler       | 1             | 5             | -                | 30       | 1       |
| Small Shield  | 3             | 8             | 25 Str           | 90       | 5       |
| Large Shield  | 5 - 10        | 32            | 40 Str           | 200      | 9       |
| Kite Shield   | 8 - 15        | 40            | 50 Str           | 400      | 14      |
| Gothic Shield | 14 - 18       | 60            | 80 Str           | 2,300    | 23      |
| Tower Shield  | 12 - 20       | 50            | 60 Str           | 850      | 20      |


### Staves<sup>[^30]</sup>

| **Type**             | **Damage** | **Durability** | **Requirements** | **Price** | **qlvl** |
|----------------------|:---------:|--------------:|----------------:|---------:|--------:|
| Short Staff<sup>[^31]</sup>  | 2 - 4     | 25            | -                | 30       | 1       |
| Long Staff          | 4 - 8     | 35            | -                | 100      | 4       |
| Composite Staff     | 5 - 10    | 45            | -                | 500      | 6       |
| Quarter Staff<sup>[^31]</sup> | 6 - 12    | 55            | 20 Str           | 1,000    | 9       |
| War Staff          | 8 - 16    | 75            | 30 Str           | 1,500    | 12      |

[^30]: All staves are **Two-handed**.
[^31]: These items have the **same picture**.  


### Swords

| **Type**               | **Damage** | **Durability** | **Requirements**         | **Price** | **qlvl** |
|------------------------|:---------:|--------------:|------------------------:|---------:|--------:|
| Dagger                | 1 - 4      | 16            | -                        | 60       | 1       |
| Sword<sup>[^32][^33]</sup> | 1 - 5      | 8             | 15 Str, 20 Dex           | 50       | n/a     |
| Short Sword<sup>[^33]</sup> | 2 - 6      | 24            | 18 Str                   | 120      | 1       |
| Sabre                 | 1 - 8      | 45            | 17 Str                   | 170      | 1       |
| Scimitar              | 3 - 7      | 28            | 23 Str, 23 Dex           | 200      | 4       |
| Blade                 | 3 - 8      | 30            | 25 Str, 30 Dex           | 280      | 4       |
| Falchion              | 4 - 8      | 20            | 30 Str                   | 250      | 2       |
| Long Sword           | 2 - 10     | 40            | 30 Str, 30 Dex           | 350      | 6       |
| Claymore              | 1 - 12     | 36            | 35 Str                   | 450      | 5       |
| Broad Sword         | 4 - 12     | 50            | 40 Str                   | 750      | 8       |
| Bastard Sword       | 6 - 15     | 60            | 50 Str                   | 1,000    | 10      |
| Two-Handed Sword<sup>[^34]</sup> | 8 - 16     | 75            | 65 Str                   | 1,800    | 14      |
| Great Sword<sup>[^34]</sup>       | 10 - 20    | 100           | 75 Str                   | 3,000    | 17      |

[^32]: Only available to the **Bard** as a starting weapon.  
[^33]: These items have the **same picture**.  
[^34]: These swords are **Two-handed**, except for the **Barbarian**.


### Jewelry<sup>[^35]</sup>

| **Type**  | **Durability**  | **Requirements** | **Price**  | **qlvl**       |
|-----------|:--------------:|----------------:|----------:|--------------:|
| Ring      | Indestructible | -              | 1,000     | 5, 10, 15     |
| Amulet    | Indestructible | -              | 1,200     | 8, 16         |

[^35]: Jewelry always has a **prefix and/or a suffix**, unless it is **unique**.

### Quest Items<sup>[^36]</sup>

| **Type**            | **Based on**      | **Damage** | **Armor Class** | **Durability** | **Requirements** |
|---------------------|------------------|:---------:|---------------:|--------------:|----------------:|
| Arkaine’s Valor    | Ring Mail        |     -      |       0        |       -       | 40              |
| Bovine Plate       | Full Plate Mail  |     -      |       0        |       -       | 50 Str          |
| Cleaver           | Axe               |  4 - 24    |       -        |       -       | 10              |
| Griswold’s Edge   | Broad Sword       |  4 - 12    |       -        |       -       | 40 Str          |
| Harlequin Crest   | Cap               |     -      |       0        |       -       | 15              |
| The Undead Crown  | Crown             |     -      |     15 - 15     |      50       | -               |
| Veil of Steel     | Great Helm        |     -      |     18 - 18     |      60       | -               |

[^36]: This is a list of the **base items** upon which **quest items** are based.  
It does not include **rings or amulets**, as it would make no difference.  
Note that any of the above **properties may be superseded** by one of the **unique properties** of the quest item.


## 3.2 Other base items

This chapter will give you information about all those items in the game that you can’t wear. It also has information about magic related items. However, for information about the actual spells, how they work and their use, see chapter 4. Books and most oils consist of a base item type, *book of* and *oil of* listed in the table below. Each book then has a spell assigned to it and oils have an oil type assigned.


### Books & Oils

| **Type**       | **Price** | **qlvl** |
|---------------|---------:|--------:|
| Book of       |    -     | 2, 8, 14, 20 |
| Oil of        |    -     | 10 |


### 3.2.1 Runes and oils

Runes and oils were introduced in Hellfire and do not exist in Diablo. Runes are placed in the dungeons and when a monster or player walks over them the spell is released. They can also be used directly on a target. Oils are used on items to boost their properties. Note that only effects from oils that affect the durability are carried over when you start a new game.

### Runes

| **Rune<sup>[^37]</sup>** | **Cost** | **qlvl** | **Effect<sup>[^38]</sup>** | **Requirement** |
|----------------------|--------:|--------:|------------------|--------------|
| Rune of Fire        | 100     | 1      | Casts Fireball   | No requirement |
| Rune of Lightning   | 200     | 3      | Casts Lightning Wall | Requires 13 Magic |
| Rune of Stone       | 300     | 7      | Casts Stone Curse | Requires 25 Magic |
| Greater Rune of Fire | 400    | 7      | Casts Immolation | Requires 42 Magic |
| Greater Rune of Lightning | 500 | 7    | Casts Nova | Requires 42 Magic |

[^37]: **Runes** can be found in the dungeon or bought from **Adria**.
[^38]: The runes **do not cast the exact spell** but rather a **similar version**. The **player’s level affects the damage/duration** of the runes.

Oils might need some more explanation. They are created by the game in two different ways. You won’t see that as a player and there is actually no difference in how they work depending on how they were created. The first three oils in the list below actually exist as a single base item. All other oils, including also versions of the first three ones, are created as a base item *oil of* to which an oil type is then assigned, just like spell books. They are listed below the thick line.

### Oils

| **Oil<sup>[^39]</sup>** | **Cost** | **qlvl** | **Effect<sup>[^40]</sup>** |
|-----------------------|--------:|--------:|--------------------------------------------|
| Blacksmith Oil<sup>[^41]</sup> | 100 | 1 | Restores 20% of durability or adds 1 to max durability |
| Oil of Accuracy | 500 | 1 | Adds 1-2% To Hit (if < 50) |
| Oil of Sharpness | 500 | 1 | Adds 1 to max damage (if < 30) |
| Blacksmith<sup>[^41]</sup> | 100 | 1 | Restores 20% of durability or adds 1 to max durability (if < 100) |
| Fortitude<sup>[^41]</sup> | 2,500 | 5 | Adds 10-50 to max and current durability (if < 200) |
| Permanence<sup>[^41][^42]</sup> | 15,000 | 17 | Makes an item indestructible |
| Accuracy<sup>[^42]</sup> | 500 | 1 | Adds 1-2% To Hit (if < 50) |
| Mastery<sup>[^42]</sup> | 2,500 | 10 | Adds 3-5% To Hit (if < 100) |
| Hardening<sup>[^42]</sup> | 2,500 | 1 | Adds 1-2 AC (if < 60) |
| Imperviousness<sup>[^42]</sup> | 2,500 | 10 | Adds 3-5 AC (if < 120) |
| Sharpness<sup>[^42]</sup> | 500 | 1 | Adds 1 to max damage (if max-min < 30)<sup>[^43]</sup> |
| Death<sup>[^42]</sup> | 2,500 | 10 | Adds 1 to min damage and 2 to max damage (if max-min < 30)<sup>[^43]</sup> |
| Skill<sup>[^42]</sup> | 1,500 | 4 | Decreases all requirements to use by 5-10 (may reach 0)<sup>[^44]</sup> |

[^39]: Oils **cannot be bought**, only found in dungeons.  
[^40]: Oils **only affect** the item they are used on.  
[^41]: Effect is **permanent** and **carries over** when restarting a new game.  
[^42]: **Only available in single-player mode.**  
[^43]: The **difference between min and max damage** must be **less than 30** for the effect to apply.  
[^44]: **All item requirements** are lowered by the **same amount**.  


### 3.2.2 Potions and elixirs

The tables below hold information about potions and elixirs. As always, the prices are buying prices.

### Potions

| **Potion** | **Cost** | **qlvl** | **Effect** |
|-----------|--------:|--------:|-----------|
| Potion of Healing<sup>[^45]</sup> | 50 | 1 | Restores some of your life |
| Potion of Full Healing | 150 | 1 | Restores all of your life |
| Potion of Mana<sup>[^45]</sup> | 50 | 1 | Restores some of your mana |
| Potion of Full Mana | 150 | 1 | Restores all of your mana |
| Potion of Rejuvenation<sup>[^45]</sup> | 120 | 3 | Restores some of your life and mana |
| Potion of Full Rejuvenation | 600 | 7 | Restores all of your life and mana |

[^45]: See below for information on how much **life/mana** is restored.

### Elixirs<sup>[^46]</sup>

| **Elixir** | **Cost** | **qlvl** | **Effect** |
|------------|--------:|--------:|------------------|
| Elixir of Strength | 5,000 | 15 | Increases Strength by 1 |
| Elixir of Magic | 5,000 | 15 | Increases Magic by 1<sup>[^48]</sup> |
| Elixir of Dexterity | 5,000 | 15 | Increases Dexterity by 1 |
| Elixir of Vitality | 5,000<sup>[^47]</sup> | 20 | Increases Vitality by 1<sup>[^49]</sup> |

[^46]: In **multiplayer**, elixirs can be **bought from Adria** once your character reaches **level 26**. In **single-player**, they can be **bought from both Adria and Pepin** once you have been to **dlvl 13, the Hive, or the Crypt (Hellfire)**.  
[^47]: **Elixirs of Vitality** cannot be bought, only **found in dungeons**.  
[^48]: In **Hellfire**, the **Elixir of Magic** **also restores all of your mana**.  
[^49]: In **Hellfire**, the **Elixir of Vitality** **also restores all of your life**.  

Potions of Healing and Mana restore life and mana as stated below. Potions of Rejuvenation are basically treated as one Potion of Mana and one Potion of Healing. For information on how scrolls of healing and the Healing spell work, see chapter 4.1.2.

### **Potion Restoration Values**

| **Potion Type** | **Restores** |
|---------------|----------------------|
| Potion of Healing | bonus × maxlife / 8 to bonus × 3 × maxlife / 8 |
| Potion of Mana | bonus × maxmana / 8 to bonus × 3 × maxmana / 8 |

- Any value in the range is equally probable.
- The bonus is summarized in the table below.
- maxlife and maxmana are the modified values. If they are negative, the amount added will also be negative and in fact subtract life or mana.


### **Potion Bonus Multipliers**

| **Type**  | **Warrior** | **Rogue** | **Sorcerer** | **Monk** | **Bard** | **Barbarian** |
|-----------|:----------:|:---------:|:------------:|:--------:|:--------:|:------------:|
| Healing   | 2.0        | 1.5       | 1.0          | 1.5<sup>[^50]</sup> | 1.5<sup>[^50]</sup> | 2.0          |
| Mana      | 1.0        | 1.5       | 2.0          | 1.5<sup>[^50]</sup> | 1.5<sup>[^50]</sup> | 1.0          |

[^50]: When using a Potion of Rejuvenation the bonus for a Monk and a Bard is 1.0 due to a bug in Hellfire.


### 3.2.3 Books, scrolls and staves with spells

Books, scrolls and staves with spells are found in the dungeons but can also be bought from Adria. Healing scrolls and scrolls of Resurrection (only in multi player) can also be bought from Pepin. Below is listed how much you have to pay for scrolls, books, and data for calculating the cost of staves with spells. For information on how to calculate staff prices, see chapter 3.6. You can also find information about qlvl; see chapters 3.8 and 3.9 for information about qlvl and how to use it. Note that for books and staves, the qlvl is of the actual spell on that base item. The base item, *staff* or *book of*, has its own qlvl as well. As with other items, you can sell any book, scroll, or staff for one fourth of* the price. Note that in Hellfire, staves without spells are bought and sold at Griswold. In Hellfire, Wirt will also sell staves both with and without spells.

## **Spell Costs and Attributes**

| **Spell**       | **Book Price** | **Book qlvl** | **Scroll Price** | **Scroll qlvl** | **Staff Multiplier (P)** | **Staff Charges** | **Staff qlvl** |
|----------------|--------------:|--------------:|-----------------:|----------------:|-------------------------:|------------------:|--------------:|
| Apocalypse<sup>[^51]</sup> | 30,000 | 19 | 2,000 | 22 | 400 | 8 – 12 | 15 |
| Blood Star      | 27,500        | 14            | -               | -              | 360                     | 20               | 60 |
| Bone Spirit    | 11,500        | 9             | -               | -              | 160                     | 20               | 60 |
| Chain Lightning | 11,000        | 8             | 750             | 10             | 150                     | 20               | 60 |
| Charged Bolt   | 1,000         | 1             | -               | -              | 10                      | 40               | 80 |
| Elemental      | 10,500        | 8             | -               | -              | 140                     | 20               | 60 |
| Fireball       | 8,000         | 8             | 300             | 8              | 60                      | 40               | 80 |
| Firebolt       | 1,000         | 1             | -               | -              | 10                      | 40               | 80 |
| Fire Wall      | 6,000         | 3             | 400             | 4              | 80                      | 8                | 16 |
| Flame Wave     | 10,000        | 9             | 650             | 10             | 130                     | 20               | 40 |
| Flash          | 7,500         | 5             | 500             | 6              | 100                     | 20               | 40 |
| Golem         | 18,000        | 11            | 1,100           | 10             | 220                     | 16               | 32 |
| Guardian       | 14,000        | 9             | 950             | 12             | 190                     | 16               | 32 |
| Healing        | 1,000         | 1             | 50              | 1              | 10                      | 20               | 40 |
| Heal Other     | 1,000         | 1             | -               | -              | 10                      | 20               | 40 |
| Holy Bolt      | 1,000         | 1             | -               | -              | 10                      | 40               | 80 |
| Identify       | -             | -             | 100             | 1              | -                       | -                | - |
| Inferno        | 2,000         | 3             | 100             | 1              | 20                      | 20               | 40 |
| Infravision    | -             | -             | 600             | 8              | -                       | -                | - |
| Lightning      | 3,000         | 4             | 150             | 4              | 30                      | 20               | 60 |
| Mana Shield    | 16,000        | 6             | 1,200           | 8              | 240                     | 4                | 10 |
| Nova           | 21,000        | 14            | 1,300           | 14             | 260                     | 16               | 32 |
| Phasing        | 3,500         | 7             | 200             | 6              | 40                      | 40               | 80 |
| Resurrect      | -             | -             | 250             | 1              | 50                      | 4                | 10 |
| Stone Curse    | 12,000        | 6             | 800             | 6              | 160                     | 8                | 16 |
| Telekinesis    | 2,500         | 2             | -               | -              | 40                      | 20               | 40 |
| Teleport       | 20,000        | 14            | 3,000           | 14             | 250                     | 16               | 32 |
| Town Portal    | 3,000         | 3             | 200             | 4              | 40                      | 8                | 12 |

[^51]: Available as a book in *Hellfire* only.


## **New Spells in Hellfire**

| **Spell**       | **Book Price** | **Book qlvl** | **Scroll Price** | **Scroll qlvl** | **Staff Multiplier (P)** | **Staff Charges** | **Staff qlvl** |
|----------------|--------------:|--------------:|-----------------:|----------------:|-------------------------:|------------------:|--------------:|
| Berserk        | 3,000         | 3             | -               | -              | 40                      | 8                | 12 |
| Immolation     | 21,000        | 14            | -               | -              | 260                     | 16               | 32 |
| Jester         | -             | -             | -               | -              | 40                      | 15               | 30 |
| Lightning Wall | 6,000         | 3             | -               | -              | 80                      | 8                | 16 |
| Magi           | -             | -             | -               | -              | 40                      | 15               | 30 |
| Mana           | -             | -             | -               | -              | 10                      | 12               | 24 |
| Reflect        | 3,000         | 3             | -               | -              | 40                      | 8                | 12 |
| Ring of Fire   | 6,000         | 5             | -               | -              | 80                      | 8                | 16 |
| Search        | 3,000         | 1             | 50              | 3              | 40                      | 8                | 12 |
| Warp           | 3,000         | 3             | -               | -              | 40                      | 8                | 12 |


## 3.3 Quest items

In the table below is listed all the various special items you will find in various quests (with the exception of the ear and the heart). They will only appear in single player and have no purposes outside the specific quest. As for the special reward items you get from various quests, they are all found in the chapter 3.5.


### **Quest Items in Diablo & Hellfire**

| **Item in Diablo**    | **Quest**                | **Item in Hellfire**<sup>[^52]</sup> | **Quest**                 |
|----------------------|------------------------|----------------------------------|--------------------------|
| Anvil of Fury       | Anvil of Fury          | Brown Suit                      | The Jersey’s Jersey      |
| Black Mushroom      | Black Mushroom         | Cathedral Map                    | Grave Matters           |
| Blood Stone<sup>[^53]</sup> | Valor                  | Grey Suit                        | The Jersey’s Jersey      |
| Brain              | Black Mushroom         | Reconstructed Note               | Torn Notes              |
| Ear<sup>[^54]</sup>         | n/a                    | Rune Bomb                        | Farmer’s Orchard        |
| Fungal Tome        | Black Mushroom         | Theodore                         | Little Girl             |
| Golden Elixir      | Lachdanan              | Torn Note 1                      | Torn Notes              |
| Heart<sup>[^54][^55]</sup> | n/a                    | Torn Note 2                      | Torn Notes              |
| Magic Rock        | The Magic Rock         | Torn Note 3                      | Torn Notes              |
| Spectral Elixir   | Black Mushroom         | -                                | -                        |
| Staff of Lazarus  | Archbishop Lazarus     | -                                | -                        |
| Tavern Sign       | Ogden’s Sign           | -                                | -                        |

[^52]: All quest items in *Diablo* are also present in *Hellfire*.  
[^53]: There are three *Blood Stones*.  
[^54]: Adria will buy ears and hearts. Their buying price is equal to the `clvl` of the character they belonged to.  
[^55]: An ear turns into a heart if you identify it. It will always return into an ear in the next game.  


## 3.4 Prefixes and suffixes

All equipable items can have a prefix and/or a suffix. In the tables below, you can see the effects of each prefix and suffix in the game. The tables also provide information about the qlvl of each prefix and suffix, as well as information for calculating the price of any magical item (steps, base-max, range and multiplier). See chapter 3.6 for formulas to calculate prices of items. The prefixes and suffixes are grouped according to what type of effect they have. Unless otherwise stated, prefixes and suffixes are cumulative with others of the same type and also with effects on unique items that are of the same type. For information on how items are assigned prefixes and suffixes, see chapter 3.8 and 3.9.

Not all prefixes and suffixes can occur on all types of items. The tables also list on which type of items you will find each prefix and suffix. The following abbreviations are used:

| **Code** | **Category** |
| :- | :- |
| A | Armor and Helms |
| S | Shields |
| W | Weapons (Axes, Clubs, and Swords) |
| T | Staves |
| t | Staves, but only in Hellfire |
| B | Bows |
| J | Jewelry |

### + Strength

| **Suffix**    | **Value**     | **Occurrence** | **qlvl** | **Steps** | **Base-Max**        | **Range**  | **Multiplier** |
|--------------|--------------|---------------|---------|----------|-------------------|---------|-------------|
| frailty      | -10 – -6     | ASW–BJ        | 3       | -        | -                 | -       | -3          |
| weakness     | -5 – -1      | ASWtBJ        | 1       | -        | -                 | -       | -2          |
| strength     | 1 – 5        | ASWtBJ        | 1       | 4        | 200 – 1,000       | 800     | 2           |
| might        | 6 – 10       | ASW–BJ        | 5       | 4        | 1,200 – 2,000     | 800     | 3           |
| power        | 11 – 15      | ASW–BJ        | 11      | 4        | 2,200 – 3,000     | 800     | 4           |
| giants       | 16 – 20      | A–W–BJ        | 17      | 4        | 3,200 – 5,000     | 1,800   | 7           |
| titans       | 21 – 30      | ––W––J        | 23      | 9        | 5,200 – 10,000    | 4,800   | 10          |


### + Magic

| **Suffix**   | **Value**    | **Occurrence** | **qlvl** | **Steps** | **Base-Max**    | **Range** | **Multiplier** |
|--------------|--------------|----------------|----------|-----------|-----------------|-----------|----------------|
| the fool     | -10 – -6     | ASWTBJ         | 3       | -          | -               | -         | -3             |
| dyslexia     | -5 – -1      | ASWTBJ         | 1       | -          | -               | -         | -2             |
| magic        | 1 – 5        | ASWTBJ         | 1       | 4          | 200 – 1,000     | 800       | 2              |
| the mind     | 6 – 10       | ASWTBJ         | 5       | 4          | 1,200 – 2,000   | 800       | 3              |
| brilliance   | 11 – 15      | ASWTBJ         | 11      | 4          | 2,200 – 3,000   | 800       | 4              |
| sorcery      | 16 – 20      | A–WTBJ         | 17      | 4          | 3,200 – 5,000   | 1,800     | 7              |
| wizardry     | 21 – 30      | –––T–J         | 23      | 9          | 5,200 – 10,000  | 4,800     | 10             |


### + Dexterity

| **Suffix**     | **Value**     | **Occurrence** | **qlvl** | **Steps** | **Base-Max**        | **Range**  | **Multiplier** |
|---------------|--------------|---------------|---------|----------|-------------------|---------|-------------|
| paralysis     | -10 – -6     | ASW–BJ        | 3       | -        | -                 | -       | -3          |
| atrophy       | -5 – -1      | ASWtBJ        | 1       | -        | -                 | -       | -2          |
| dexterity     | 1 – 5        | ASWtBJ        | 1       | 4        | 200 – 1,000       | 800     | 2           |
| skill         | 6 – 10       | ASW–BJ        | 5       | 4        | 1,200 – 2,000     | 800     | 3           |
| accuracy      | 11 – 15      | ASW–BJ        | 11      | 4        | 2,200 – 3,000     | 800     | 4           |
| precision     | 16 – 20      | A–W–BJ        | 17      | 4        | 3,200 – 5,000     | 1,800   | 7           |
| perfection    | 21 – 30      | ––––BJ        | 23      | 9        | 5,200 – 10,000    | 4,800   | 10          |



### + Vitality

| **Suffix**  | **Value**     | **Occurrence** | **qlvl** | **Steps** | **Base-Max**        | **Range**  | **Multiplier** |
|------------|--------------|---------------|---------|----------|-------------------|---------|-------------|
| illness    | -10 – -6     | ASW–BJ        | 3       | -        | -                 | -       | -3          |
| disease    | -5 – -1      | ASWtBJ        | 1       | -        | -                 | -       | -2          |
| vitality   | 1 – 5        | ASWtBJ        | 1       | 4        | 200 – 1,000       | 800     | 2           |
| zest       | 6 – 10       | ASW–BJ        | 5       | 4        | 1,200 – 2,000     | 800     | 3           |
| vim        | 11 – 15      | ASW–BJ        | 11      | 4        | 2,200 – 3,000     | 800     | 4           |
| vigor      | 16 – 20      | A–W–BJ        | 17      | 4        | 3,200 – 5,000     | 1,800   | 7           |
| life       | 21 – 30      | ––-––J        | 23      | 9        | 5,200 – 10,000    | 4,800   | 10          |



### + All Attributes

| **Suffix**   | **Value**     | **Occurrence** | **qlvl** | **Steps** | **Base-Max**         | **Range**  | **Multiplier** |
|-------------|--------------|---------------|---------|----------|--------------------|---------|-------------|
| trouble     | -10 – -6     | ASWtBJ        | 12      | -        | -                  | -       | -10         |
| the pit     | -5 – -1      | ASWtBJ        | 5       | -        | -                  | -       | -5          |
| the sky     | 1 – 3        | ASWtBJ        | 5       | 2        | 800 – 4,000        | 3,200   | 5           |
| the moon    | 4 – 7        | ASWtBJ        | 11      | 3        | 4,800 – 8,000      | 3,200   | 10          |
| the stars   | 8 – 11       | A-W-BJ        | 17      | 3        | 8,800 – 12,000     | 3,200   | 15          |
| the heavens | 12 – 15      | ––W–BJ        | 25      | 3        | 12,800 – 20,000    | 7,200   | 20          |
| the zodiac  | 16 – 20      | ––-––J        | 30      | 4        | 20,800 – 40,000    | 19,200  | 30          |



### + Life

| **Suffix**     | **Value**     | **Occurrence** | **qlvl** | **Steps** | **Base-Max**         | **Range**  | **Multiplier** |
|---------------|--------------|---------------|---------|----------|--------------------|---------|-------------|
| the vulture  | -25 – -11     | AS---J        | 4       | -        | -                  | -       | -4          |
| the jackal   | -10 – -1      | AS---J        | 1       | -        | -                  | -       | -2          |
| the fox      | 10 – 15       | AS---J        | 1       | 5        | 100 – 1,000        | 900     | 2           |
| the jaguar   | 16 – 20       | AS---J        | 5       | 4        | 1,100 – 2,000      | 900     | 3           |
| the eagle    | 21 – 30       | AS---J        | 9       | 9        | 2,100 – 4,000      | 1,900   | 5           |
| the wolf     | 30 – 40       | AS---J        | 15      | 10       | 4,100 – 6,000      | 1,900   | 7           |
| the tiger    | 41 – 50       | AS---J        | 21      | 9        | 6,100 – 10,000     | 3,900   | 9           |
| the lion     | 51 – 60       | A----J        | 27      | 9        | 10,100 – 15,000    | 4,900   | 11          |
| the mammoth  | 61 – 80       | A-----        | 35      | 19       | 15,100 – 19,000    | 3,900   | 12          |
| the whale    | 81 – 100      | A-----        | 60      | 19       | 19,100 – 30,000    | 10,900  | 13          |



### + Mana

| **Prefix**    | **Value**    | **Occurrence** | **qlvl** | **Steps** | **Base-Max**         | **Range**  | **Multiplier** |
|--------------|-------------|---------------|---------|----------|--------------------|---------|-------------|
| corruption<sup>[^56]</sup> | -            | all          | ASW---  | 5        | -1,000              | -       | 2           |
| hyena’s      | -25 – -11   | ---T-J       | 4       | 14       | 100 – 1,000       | 900     | -2          |
| frog’s       | -10 – -1    | ---T-J       | 1       | -        | -                  | -       | -2          |
| spider’s     | 10 – 15     | ---T-J       | 1       | 5        | 500 – 1,000       | 500     | 2           |
| raven’s      | 16 – 20     | ---T-J       | 5       | 5        | 1,100 – 2,000     | 900     | 3           |
| snake’s      | 21 – 30     | ---T-J       | 9       | 9        | 2,100 – 4,000     | 1,900   | 5           |
| serpent’s    | 31 – 40     | ---T-J       | 15      | 10       | 4,100 – 6,000     | 1,900   | 7           |
| drake’s      | 41 – 50     | ---T-J       | 21      | 9        | 6,100 – 10,000    | 3,900   | 9           |
| dragon’s     | 51 – 60     | ---T-J       | 27      | 9        | 10,100 – 15,000   | 4,900   | 11          |
| wyrm’s<sup>[^57]</sup>     | 61 – 80     | ---t--       | 35      | 19       | 15,100 – 19,000   | 3,900   | 12          |
| hydra’s<sup>[^57]</sup>    | 81 – 100    | ---t--       | 60      | 19       | 19,100 – 30,000   | 10,900  | 13          |

[^56]: A suffix.  
[^57]: Only available in *Hellfire*.  


### +% Armor Class<sup>[^58]</sup>

| **Prefix**   | **Value**      | **Occurrence** | **qlvl** | **Steps** | **Base-Max**       | **Range**  | **Multiplier** |
|-------------|---------------|---------------|---------|----------|------------------|---------|-------------|
| vulnerable  | -100 – -51     | AS––––        | 3       | -        | -                | -       | -3          |
| rusted      | -50 – -25      | AS––––        | 1       | -        | -                | -       | -2          |
| fine        | 20 – 30        | AS––––        | 1       | 10       | 20 – 100         | 80      | 2           |
| strong      | 31 – 40        | AS––––        | 3       | 9        | 120 – 200        | 80      | 3           |
| grand       | 41 – 55        | AS––––        | 6       | 14       | 220 – 300        | 80      | 5           |
| valiant     | 56 – 70        | AS––––        | 10      | 14       | 320 – 400        | 80      | 7           |
| glorious    | 71 – 90        | AS––––        | 14      | 19       | 420 – 600        | 180     | 9           |
| blessed     | 91 – 110       | AS––––        | 19      | 19       | 620 – 800        | 180     | 11          |
| saintly     | 111 – 130      | AS––––        | 24      | 19       | 820 – 1,200      | 380     | 13          |
| awesome     | 131 – 150      | AS––––        | 28      | 19       | 1,220 – 2,000    | 780     | 15          |
| holy        | 151 – 170      | AS––––        | 35      | 19       | 5,200 – 6,000    | 800     | 17          |
| godly       | 171 – 200      | AS––––        | 60      | 29       | 6,200 – 7,000    | 800     | 20          |

[^58]: There is a minimum increase of 1 in AC. Even if the percentage results in an increase of less than one, AC will still increase by at least one. Due to a bug, any decrease in AC less than 1 will be transformed into a positive increase by 1.


### +% To Hit<sup>[^59]</sup>

| **Prefix**  | **Value**         | **Occurrence** | **qlvl** | **Steps** | **Base-Max**       | **Range**  | **Multiplier** |
|------------|------------------|---------------|---------|----------|------------------|---------|-------------|
| tin        | -10 – -6         | ––W–BJ       | 3       | -        | -                | -       | -3          |
| brass      | -5 – -1          | ––W–BJ       | 1       | -        | -                | -       | -2          |
| bronze     | 1 – 5            | ––W–BJ       | 1       | 4        | 100 – 500        | 400     | 2           |
| iron       | 6 – 10           | ––W–BJ       | 4       | 4        | 600 – 1,000      | 400     | 3           |
| steel      | 11 – 15          | ––W–BJ       | 6       | 4        | 1,100 – 1,500    | 400     | 5           |
| silver     | 16 – 20          | ––W–BJ       | 9       | 4        | 1,600 – 2,000    | 400     | 7           |
| gold       | 21 – 30          | ––W–BJ       | 12      | 9        | 2,100 – 3,000    | 900     | 9           |
| platinum   | 31 – 40          | ––W–B–       | 16      | 9        | 3,100 – 4,000    | 900     | 11          |
| mithril    | 41 – 60          | ––W–B–       | 20      | 19       | 4,100 – 6,000    | 1,900   | 13          |
| meteoric   | 61 – 80          | ––W–B–       | 23      | 19       | 6,100 – 10,000   | 3,900   | 15          |
| weird      | 81 – 100         | ––W–B–       | 35      | 19       | 10,100 – 14,000  | 3,900   | 17          |
| strange    | 101 – 150        | ––W–B–       | 60      | 49       | 14,100 – 20,000  | 5,900   | 20          |

[^59]: Determines the percentage bonus or penalty applied to a character's chance to hit enemies in melee or ranged combat.


### +% To Hit, +% Damage Done<sup>[^60]</sup>

| **Prefix**         | **To Hit**      | **Damage**        | **Occurrence** | **qlvl** | **Steps** | **Base-Max**         | **Range**      | **Multiplier** |
|-------------------|---------------|----------------|--------------|---------|----------|--------------------|------------|-------------|
| clumsy           | -10 – -6       | -75 – -50      | ––WTB–       | 5       | -        | -                  | -          | -7          |
| dull             | -5 – -1        | -45 – -25      | ––WTB–       | 1       | -        | -                  | -          | -5          |
| sharp<sup>[^61]</sup>         | 1 – 5          | 20 – 35       | ––WTB–       | 1       | 15       | 350 – 950          | 600        | 5           |
| fine             | 6 – 10         | 36 – 50        | ––WTB–       | 6       | 14       | 1,100 – 1,700      | 600        | 7           |
| Warrior’s        | 11 – 15        | 51 – 65        | ––WTB–       | 10      | 14       | 1,850 – 2,450      | 600        | 13          |
| soldier’s        | 16 – 20        | 66 – 80        | ––WT––       | 15      | 14       | 2,600 – 3,950      | 1,350      | 17          |
| lord’s           | 21 – 30        | 81 – 95        | ––WT––       | 19      | 14       | 4,100 – 5,950      | 1,850      | 21          |
| knight’s         | 31 – 40        | 96 – 110       | ––WT––       | 23      | 14       | 6,100 – 8,450      | 2,350      | 26          |
| master’s         | 41 – 50        | 111 – 125      | ––WT––       | 28      | 14       | 8,600 – 13,000     | 4,400      | 30          |
| champion’s       | 51 – 75        | 126 – 150      | ––WT––       | 40      | 24       | 15,200 – 24,000    | 8,800      | 33          |
| king’s           | 76 – 100       | 151 – 175      | ––WT––       | 28      | 24       | 24,100 – 35,000    | 10,900     | 38          |
| doppelganger’s<sup>[^62]</sup> | 21 – 30        | 81 – 95        | ––Wt––       | 11      | 14       | 2,000 – 2,400      | 400        | 10          |

[^60]: The damage value is used for price calculations.  
[^61]: This is treated as a cursed item during item creation, meaning it will not be available for purchase in town.  
[^62]: Only available in *Hellfire*. Has a 10% chance of duplicating any monster hit, except for *Diablo* and unique monsters.


### +% Damage Done<sup>[^63]</sup>

| **Prefix**         | **Value**        | **Occurrence** | **qlvl** | **Steps** | **Base-Max**        | **Range**     | **Multiplier** |
|-------------------|----------------|--------------|---------|----------|-------------------|------------|-------------|
| useless          | -100            | ––WtB–       | 5       | -        | -                 | -          | -8          |
| bent            | -75 – -50       | ––WtB–       | 3       | -        | -                 | -          | -4          |
| weak            | -45 – -25       | ––WtB–       | 1       | -        | -                 | -          | -3          |
| jagged          | 20 – 35         | ––WtB–       | 4       | 15       | 250 – 450         | 200        | 3           |
| deadly          | 36 – 50         | ––WtB–       | 6       | 14       | 500 – 700         | 200        | 4           |
| heavy           | 51 – 65         | ––WtB–       | 9       | 14       | 750 – 950         | 200        | 5           |
| vicious         | 66 – 80         | ––WtB–       | 12      | 14       | 1,000 – 1,450     | 450        | 8           |
| brutal          | 81 – 95         | ––WtB–       | 16      | 14       | 1,500 – 1,950     | 450        | 10          |
| massive         | 96 – 110        | ––WtB–       | 20      | 14       | 2,000 – 2,450     | 450        | 13          |
| savage         | 111 – 125        | ––W–B–       | 23      | 14       | 2,500 – 3,000     | 500        | 15          |
| ruthless       | 126 – 150        | ––W–B–       | 35      | 24       | 10,100 – 15,000   | 4,900      | 17          |
| merciless      | 151 – 175        | ––W–B–       | 60      | 24       | 15,000 – 20,000   | 5,000      | 20          |
| decay<sup>[^64][^65]</sup>        | 150 – 250      | ––WtB–       | 1       | -        | 200 – 200         | 0          | 2           |
| crystalline<sup>[^64][^66]</sup>  | 200 – 280      | ––W–––       | 5       | 79       | 1,000 – 3,000     | 2,000      | 3           |

[^63]: Damage bonus applies to total damage, not just weapon damage.  
[^64]: Only available in *Hellfire*.  
[^65]: Bonus decreases by 5% per hit. When reaching -100%, the item is destroyed.  
[^66]: Also has **-30% to -70% lower durability**.  


### + Damage Done<sup>[^67]</sup>

| **Suffix**  | **Value**    | **Occurrence** | **qlvl** | **Steps** | **Base-Max**       | **Range**  | **Multiplier** |
|------------|------------|--------------|---------|----------|-----------------|------------|-------------|
| quality    | 1          | ––WtB–       | 2       | 1        | 100 – 200       | 100        | 2           |
| maiming    | 3 – 5      | ––WtB–       | 7       | 2        | 1,300 – 1,500   | 200        | 3           |
| slaying    | 6 – 8      | ––W–––       | 15      | 2        | 2,600 – 3,000   | 400        | 5           |
| gore       | 9 – 12     | ––W–––       | 25      | 3        | 4,100 – 5,000   | 900        | 8           |
| carnage    | 13 – 16    | ––W–––       | 35      | 3        | 5,100 – 10,000  | 4,900      | 10          |
| slaughter  | 17 – 20    | ––W–––       | 60      | 3        | 10,100 – 15,000 | 4,900      | 13          |

[^67]: These suffixes increase the flat damage done by weapons.  


### - Damage Taken<sup>[^68]</sup>

| **Suffix**   | **Value**   | **Occurrence** | **qlvl** | **Steps** | **Base-Max**       | **Range**  | **Multiplier** |
|-------------|------------|--------------|---------|----------|-----------------|------------|-------------|
| pain        | +2 – +4    | AS–––J       | 4       | -        | -               | -4         | -           |
| tears       | +1         | AS–––J       | 2       | -        | -               | -2         | -           |
| health      | 1          | AS–––J       | 2       | -        | 200             | -          | 2           |
| protection  | 2          | AS––––       | 6       | -        | 400             | -          | 4           |
| absorption  | 3          | AS––––       | 12      | -        | 1,001           | -          | 10          |
| deflection  | 4          | A–––––       | 20      | -        | 2,500           | -          | 15          |
| osmosis     | 5 – 6      | A–––––       | 50      | 1        | 7,500 – 10,000  | 2,500      | 20          |

[^68]: Works for all types of damage, including spells, but does not work against other players. The damage reduction is applied **before** resistances but **after** the *Thieves' Effect*. Damage will never be reduced below **1**.


### + Fire Damage<sup>[^69]</sup>

| **Suffix**  | **Value**  | **Occurrence** | **qlvl** | **Steps** | **Base-Max** | **Range** | **Multiplier** |
|------------|-----------|--------------|---------|----------|------------|----------|-------------|
| flame      | 1 – 3     | ––––B–       | 1       | -        | 2,000      | -        | 2           |
| fire       | 1 – 6     | ––––B–       | 11      | -        | 4,000      | -        | 4           |
| burning    | 1 – 16    | ––––B–       | 35      | -        | 6,000      | -        | 6           |
| flaming<sup>[^70]</sup>  | 1 – 10    | ––WT––       | 7       | -        | 5,000      | -        | 2           |

[^69]: There are several **bugs** associated with fire and lightning arrows, causing them to sometimes deal **erroneous damage** (either too high or no additional damage at all).  
[^70]: *Flaming* is a **prefix**, not a suffix.


### + Lightning Damage<sup>[^71]</sup>

| **Suffix**     | **Value**  | **Occurrence** | **qlvl** | **Steps** | **Base-Max** | **Range** | **Multiplier** |
|---------------|-----------|--------------|---------|----------|------------|----------|-------------|
| shock        | 1 – 6     | ––––B–       | 13      | -        | 6,000      | -        | 2           |
| lightning    | 1 – 10    | ––––B–       | 21      | -        | 8,000      | -        | 4           |
| thunder      | 1 – 20    | ––––B–       | 60      | -        | 12,000     | -        | 6           |
| lightning<sup>[^72]</sup> | 2 – 20    | ––WT––       | 18      | -        | 10,000     | -        | 2           |

[^71]: There are several **bugs** associated with fire and lightning arrows, causing them to sometimes deal **erroneous damage** (either too high or no additional damage at all).  
[^72]: *Lightning* is a **prefix**, not a suffix.


### % Steal Life<sup>[^73]</sup>

| **Suffix**    | **Value** | **Occurrence** | **qlvl** | **Steps** | **Base-Max** | **Range** | **Multiplier** |
|--------------|---------|--------------|---------|----------|------------|----------|-------------|
| the leech   | 3%     | ––W–––       | 8       | -        | 7,500      | -        | 3           |
| blood       | 5%     | ––W–––       | 19      | -        | 15,000     | -        | 3           |

[^73]: The amount of **life stolen** is based on **damage dealt**, even if the monster has **less HP remaining**.  
- **Not cumulative** if multiple items have this effect (e.g., an *item of blood* takes precedence over *an item of the leech*).  
- **Exception:** *The Undead Crown* stacks with both *leech* and *blood*, allowing **up to 3% – 15.5%** or **5% – 17.5%** life steal.  
- **Items treated as "blood"**: *The Helm of Sprits*, *Shadowhawk*, *The Eater of Souls*.  
- **Does not work against players.**  
- See **Chapter 6.1.4** for more details.


### % Steal Mana<sup>[^74]</sup>

| **Suffix**   | **Value** | **Occurrence** | **qlvl** | **Steps** | **Base-Max** | **Range** | **Multiplier** |
|-------------|---------|--------------|---------|----------|------------|----------|-------------|
| the bat    | 3%     | ––W–––       | 8       | -        | 7,500      | -        | 3           |
| vampires   | 5%     | ––W–––       | 19      | -        | 15,000     | -        | 3           |

[^74]: The amount of **mana stolen** is based on **damage dealt**, even if the monster has **less mana remaining**.  
- **Not cumulative** if multiple items have this effect (*e.g., an item of vampires takes precedence over an item of the bat*).  
- **Exception:** *The Eater of Souls* is treated as an *item of vampires*.  
- **Does not work against players.**  
- See **Chapter 6.1.4** for more details.


### +% Resist Magic<sup>[^75]</sup>

| **Prefix**  | **Value**  | **Occurrence** | **qlvl** | **Steps** | **Base-Max** | **Range**  | **Multiplier** |
|------------|-----------|--------------|---------|----------|------------|-----------|-------------|
| white      | 10% - 20% | ASWTBJ       | 4       | 10       | 500 - 1,500  | 1,000     | 2           |
| pearl      | 21% - 30% | ASWTBJ       | 10      | 9        | 2,100 - 3,000 | 900       | 2           |
| ivory      | 31% - 40% | ASWTBJ       | 16      | 9        | 3,100 - 4,000 | 900       | 2           |
| crystal    | 41% - 50% | ASWTBJ       | 20      | 9        | 8,200 - 12,000 | 3,800     | 3           |
| diamond    | 51% - 60% | ASWTBJ       | 26      | 9        | 17,100 - 20,000 | 2,900     | 5           |

[^75]: **Resistance applies after** other damage reductions (*thieves & -damage effects*).  
- It **can reduce damage below 1** in some cases.


### +% Resist Fire<sup>[^76]</sup>

| **Prefix**  | **Value**   | **Occurrence** | **qlvl** | **Steps** | **Base-Max**  | **Range**    | **Multiplier** |
|------------|------------|--------------|---------|----------|--------------|-------------|-------------|
| red        | 10% - 20%  | ASWTBJ       | 4       | 10       | 500 - 1,500   | 1,000       | 2           |
| crimson    | 21% - 30%  | ASWTBJ       | 10      | 9        | 2,100 - 3,000  | 900         | 2           |
| crimson    | 31% - 40%  | ASWTBJ       | 16      | 9        | 3,100 - 4,000  | 900         | 2           |
| garnet     | 41% - 50%  | ASWTBJ       | 20      | 9        | 8,200 - 12,000 | 3,800       | 3           |
| ruby       | 51% - 60%  | ASWTBJ       | 26      | 9        | 17,100 - 20,000 | 2,900       | 5           |

[^76]: **Resistance applies after** other damage reductions (*thieves & -damage effects*).  
- It **can reduce damage below 1** in some cases.


### +% Resist Lightning<sup>[^77]</sup>

| **Prefix**  | **Value**   | **Occurrence** | **qlvl** | **Steps** | **Base-Max**  | **Range**    | **Multiplier** |
|------------|------------|--------------|---------|----------|--------------|-------------|-------------|
| blue       | 10% - 20%  | ASWTBJ       | 4       | 10       | 500 - 1,500   | 1,000       | 2           |
| azure      | 21% - 30%  | ASWTBJ       | 10      | 9        | 2,100 - 3,000  | 900         | 2           |
| lapis      | 31% - 40%  | ASWTBJ       | 16      | 9        | 3,100 - 4,000  | 900         | 2           |
| cobalt     | 41% - 50%  | ASWTBJ       | 20      | 9        | 8,200 - 12,000 | 3,800       | 3           |
| sapphire   | 51% - 60%  | ASWTBJ       | 26      | 9        | 17,100 - 20,000 | 2,900       | 5           |

[^77]: **Resistance applies after** other damage reductions (*thieves & -damage effects*).  
- It **can reduce damage below 1** in some cases.


### +% Resist All<sup>[^78]</sup>

| **Prefix**  | **Value**   | **Occurrence** | **qlvl** | **Steps** | **Base-Max**   | **Range**     | **Multiplier** |
|------------|------------|--------------|---------|----------|---------------|--------------|-------------|
| topaz      | 10% - 15%  | ASWTBJ       | 8       | 5        | 2,000 - 5,000  | 3,000        | 3           |
| amber      | 16% - 20%  | ASWTBJ       | 12      | 4        | 7,400 - 10,000 | 2,600        | 3           |
| jade       | 21% - 30%  | ASWTBJ       | 18      | 9        | 11,000 - 15,000 | 4,000       | 3           |
| obsidian   | 31% - 40%  | ASWTBJ       | 24      | 9        | 24,000 - 40,000 | 16,000      | 4           |
| emerald    | 41% - 50%  | –SWTB–       | 31      | 9        | 61,000 - 75,000 | 14,000      | 7           |

[^78]: **Resistance applies after** other damage reductions (*thieves & -damage effects*).  
- It **can reduce damage below 1** in some cases.


### + Spell Levels

| **Prefix**       | **Value** | **Occurrence** | **qlvl** | **Steps** | **Base-Max** | **Range** | **Multiplier** |
|-----------------|----------|--------------|---------|----------|-------------|--------|-------------|
| angel’s        | +1       | –––T––      | 15      | -        | 25,000       | -      | 2           |
| arch-angel’s   | +2       | –––T––      | 25      | -        | 50,000       | -      | 3           |


### × Charges

| **Prefix**      | **Value** | **Occurrence** | **qlvl** | **Steps** | **Base-Max** | **Range** | **Multiplier** |
|----------------|----------|--------------|---------|----------|-------------|--------|-------------|
| plentiful     | ×2       | –––T––      | 4       | -        | 2,000       | -      | 2           |
| bountiful     | ×3       | –––T––      | 9       | -        | 3,000       | -      | 3           |


### Damage / Penetrate Armor<sup>[^79]</sup>

| **Suffix**    | **Value (Diablo)**<sup>[^80]</sup> | **Value (Hellfire)**<sup>[^81]</sup> | **Occurrence** | **qlvl** | **Steps** | **Base-Max** | **Range** | **Multiplier** |
|--------------|----------------------------------|------------------------------------|--------------|---------|----------|-------------|--------|-------------|
| Piercing     | 2 - 6                            | 25%<sup>[^82]</sup>                 | ––W–B–       | 1       | -        | 1,000       | -      | 3           |
| Puncturing   | 4 - 12                           | 50%<sup>[^82]</sup>                 | ––W–B–       | 9       | -        | 2,000       | -      | 6           |
| Bashing      | 8 - 24                           | 75%<sup>[^82]</sup>                 | ––W–––       | 17      | -        | 4,000       | -      | 12          |

[^79]: In *Diablo*, these suffixes lower the **AC** of the target by a specific **random amount** in the table.  
      In *Hellfire*, they reduce the **AC** of the target by the percentage shown.  
      **Does not work against players.**  
      The exact value (in *Diablo*) is determined at item creation, and the extra *To Hit* is never displayed on the character screen.

[^80]: **Diablo version** - Flat AC reduction range.  
[^81]: **Hellfire version** - Percentage-based AC reduction.  
[^82]: **Bonus when used by a Barbarian:** Add **12.5%** to the listed effect.


### +% Light Radius<sup>[^83]</sup>

| **Suffix**   | **Value** | **Occurrence** | **qlvl** | **Steps** | **Base-Max** | **Range** | **Multiplier** |
|-------------|---------:|--------------|---------:|----------|-------------|--------:|-------------:|
| The Dark    | -40%    | A–W—J       | 6       | -        | -           | -3      | -            |
| The Night   | -20%    | A–W—J       | 3       | -        | -           | -2      | -            |
| Light       | 20%     | A–W—J       | 4       | -        | 750         | 2       | -            |
| Radiance    | 40%     | A–W—J       | 8       | -        | 1,500       | 3       | -            |

[^83]: **Light radius also affects monster activation distance.**  
- A higher value **increases** the distance at which you **activate** monsters.  
- **Maximum effective range:** +50%. **Minimum effective range:** -80%.  
- Light radius is **always reduced by one** in the *Catacombs*.  
- The **highest light radius** achieved on a level persists, even if later lowered.


### Weapon Speed<sup>[^84]</sup>

| **Suffix**       | **Value**   | **Occurrence** | **qlvl** | **Steps** | **Base-Max** | **Range** | **Multiplier** |
|-----------------|------------|---------------|---------:|----------|-------------|--------:|-------------:|
| Readiness<sup>[^85][^3]</sup>   | Quick    | ––WTB–   | 1        | -        | 2,000       | 2       | -            |
| Swiftness<sup>[^86]</sup>       | Fast     | ––WTB–   | 10       | -        | 4,000       | 4       | -            |
| Speed         | Faster   | ––WT––   | 19       | -        | 8,000       | 8       | -            |
| Haste<sup>[^87]</sup>         | Fastest  | ––WT––   | 27       | -        | 16,000      | 16      | -            |

[^84]: **Weapon speed affects attack rate and animation speed.**  
[^85]: Has **no effect in Diablo**.  
[^86]: In *Hellfire*, **increases arrow travel speed** for bows instead of swing speed.  
[^87]: *Despite patch 1.07 notes, "Haste" functions identically to "Speed"*.  


### Hit Recovery<sup>[^88]</sup>

| **Suffix**     | **Value** | **Occurrence** | **qlvl** | **Steps** | **Base-Max** | **Range** | **Multiplier** |
|---------------|:---------:|:-------------:|:--------:|:---------:|:------------:|:---------:|:--------------:|
| balance<sup>[^88]</sup>  | fast    | A––––J  | 1  |  -  | 2 000  | -  | 2  |
| stability<sup>[^88]</sup> | faster  | A––––J  | 10 |  -  | 4 000  | -  | 4  |
| harmony<sup>[^88]</sup>   | fastest | A––––J  | 20 |  -  | 8 000  | -  | 8  |

[^88]: A character only benefits from the fastest one, as they are not cumulative.  
The exception is if you have one of each, in which case, in *Diablo* only, you will receive a further reduction in hit recovery time.  
See chapter **2.2.1** for more information.


### +% Durability

| **Suffix**         | **Value**  | **Occurrence** | **qlvl** | **Steps** | **Base-Max** | **Range** | **Multiplier** |
|-------------------|:---------:|:-------------:|:--------:|:---------:|:------------:|:---------:|:--------------:|
| fragility        | -         | =1            | ASW–––   | 3         | -            | -         | -4             |
| brittleness      | -75       | -26           | ASW–––   | 1         | -            | -         | -2             |
| sturdiness       | 26 - 75   | -             | ASWt––   | 1         | 100          | -         | 2              |
| craftsmanship    | 51 - 100  | -             | ASWt––   | 6         | 200          | -         | 2              |
| structure       | 101 - 200  | -             | ASWt––   | 12        | 300          | -         | 2              |
| many            | -         | 100           | ––––B–   | 3         | 750          | -         | 2              |
| plenty          | -         | 200           | ––––B–   | 7         | 1 500        | -         | 3              |
| the ages        | indestruct.| -             | ASWt––   | 25        | 600          | -         | 5              |

### Other Effects<sup>[^89]</sup>

| **Suffix**                   | **Effect**                                    | **Occurrence** | **qlvl** | **Base-Max** | **Multiplier** |
|------------------------------|----------------------------------------------|---------------|---------:|-------------|--------------:|
| The Bear<sup>[^90]</sup>     | Knocks target back                           | ––WTB–        | 5        | 750         | 2            |
| Blocking<sup>[^90]</sup>     | Fast block                                  | -S----        | 5        | 4,000       | 4            |
| Thieves<sup>[^89][^90][^91]</sup>   | Absorbs half trap damage                    | AS–––J        | 11       | 1,500       | 2            |
| Thorns<sup>[^89][^90]</sup>   | Attacker takes 1-3 damage                    | AS––––        | 1        | 500         | 2            |
| Devastation<sup>[^89][^90][^92][^93][^94]</sup>  | 5% chance of doing ×3 damage                | ––WtB–        | 1        | 1,200       | 3            |
| Jester’s<sup>[^89][^90][^92][^93][^95]</sup>  | Each swing does ×0-6 damage<sup>[^97]</sup>  | ––W–––        | 7        | 1,200       | 3            |
| Peril<sup>[^89][^90][^92][^94][^96]</sup>  | ×2 damage to monster, ×1 to user            | ––WtB–        | 5        | 500         | 1            |

[^89]: **Does not work versus players.**  
[^90]: **These effects are not cumulative if applied more than once**, but they stack with other effects.  
[^91]: In *Hellfire*, **also absorbs half arrow and magical damage** (*magic, fire, lightning, and Apocalypse*) from monster attacks. Applied before `-damage` and resistances.  
[^92]: **Only available in Hellfire.**  
[^93]: **Damage bonus applies to total damage, not just weapon damage.**  
[^94]: **Does not work on bows.**  
[^95]: A **prefix**.  
[^96]: Affects **total damage versus monsters**, but only **weapon damage and character damage versus the user**. Modified by any `-damage` effects.  
[^97]: The game erroneously states damage as ×0-5. **Actual average value is ×2**. *Does not work against Diablo or unique monsters.*  


## 3.5 Unique items

Unique items differ from normal magical items in that they have a special name and can have up to six different magical properties. You can still find more than one of each, even in the same game (in single player the game keeps track of what unique items exist in the current game, and will not create the same a second time). Having a different picture than that of the normal base item it is based upon is considered as one of the six special properties. All non quest unique items are based on a normal base item, and unless otherwise changed by the unique properties, retain all the stats of that normal base item. Unique quest items are based on special quest base items. Those special quest base items can be found in chapter 3.3. Such items are also noted by having n/a in the qlvl column.

If you are playing the Playstation version you should know that when you restart a new game, any unique item is transformed into gold, which is quite annoying.


### 3.5.1 Properties of unique items

In the tables below are listed all unique items in the game that you can equip, both the ones randomly generated and the ones given as part of quests. For special quest items that are unequipable, see chapter 3.3. The prices shown are the buying prices. You can never buy unique items however. The stated qlvl is used in item generation, see chapter 3.8. Please note that all items *below* a thick line are only available in Hellfire. The *Pic* column indicates whether the item has a unique picture or not.

### Armor

| **Name**                        | **Base Item**         | **Price**  | **qlvl** | **Pic** | **Magical Effects** |
|---------------------------------|----------------------|----------:|--------:|:------:|---------------------------------------------------------------|
| Arkaine’s Valor<sup>[^98]</sup>  | Arkaine’s Valor      | 42,000    | n/a     | ✅      | AC 25, +10 Vitality, -3 damage from enemies, fastest hit recovery |
| Demonspike Coat                 | Full Plate Mail      | 251,175   | 25      | ❌      | AC 100, +10 Strength, +50% Resist Fire, -6 damage from enemies, Indestructible |
| The Gladiator’s Bane            | Studded Leather      | 3,450     | 6       | ❌      | AC 25, -3 All Attributes, -2 damage from enemies, High durability (135) |
| Leather of Aut                  | Leather Armor        | 10,550    | 4       | ❌      | AC 15, +5 Strength, -5 Magic, +5 Dexterity, Indestructible |
| Naj’s Light Plate               | Plate Mail           | 78,700    | 19      | ✅      | +5 Magic, +20 Mana, +20% Resist All, +1 Spell Level, No Strength Requirements |
| Nightscape                      | Cape                 | 11,600    | 16      | ✅<sup>[^99]</sup> | AC 15, +3 Dexterity, +20% Resist All, Faster Hit Recovery, -40% Light Radius |
| The Rainbow Cloak               | Cloak                | 4,900     | 2       | ✅<sup>[^99]</sup> | AC 10, +1 All Attributes, +5 Life, +10% Resist All, High durability (27) |
| Scavenger Carapace              | Breast Plate         | 14,000    | 13      | ❌      | AC -6 to -10, +5 Dexterity, +40% Resist Lightning, -15 damage from enemies |
| Sparking Mail                   | Chain Mail           | 15,750    | 9       | ❌      | AC 30, 1-10 Lightning Damage |
| Torn Flesh of Souls             | Rags                 | 4,825     | 2       | ✅      | AC 8, +10 Vitality, -1 damage from enemies, Indestructible |
| Wisdom’s Wrap                   | Robe                 | 6,200     | 5       | ✅<sup>[^99]</sup> | AC 15, +5 Magic, +10 Mana, +25% Resist Lightning, -1 damage from enemies |
| Armor of Gloom                  | Full Plate Mail      | 200,000   | 25      | ✅      | AC 225, All Resistances = 0%, -20% Light Radius, No Strength Requirements |
| Bone Chain Armor                | Chain Mail           | 36,000    | 13      | ✅      | AC 40, AC 60 vs. Undead |
| Bovine Plate<sup>[^100]</sup>    | Bovine Plate         | 400       | n/a     | ✅      | AC 150, -50 Mana, +30% Resist All, -2 Spell Levels, +50% Light Radius, Indestructible |
| Demon Plate Armor               | Full Plate Mail      | 80,000    | 25      | ✅      | AC 80, AC 120 vs. Demons |

[^98]: **A quest item only available in single player.**  
[^99]: **These items share the same picture.**  
[^100]: **A quest item.**  


### Axes

| **Name**                           | **Base Item**  | **Price** | **qlvl** | **Pic** | **Magical Effects** |
|------------------------------------|--------------|----------:|--------:|:------:|------------------------------------------------------------|
| Aguinara’s Hatchet                 | Small Axe    | 24,800    | 12      | ❌      | +10 Magic, +75% Resist Magic, +1 Spell Level |
| Bloodslayer                        | Broad Axe    | 2,500     | 3       | ✅<sup>[^101]</sup> | -5 All Attributes, +100% Damage, +200% Damage versus Demons<sup>[^102]</sup>, -1 Spell Level |
| The Butcher’s Cleaver<sup>[^103]</sup> | Cleaver      | 3,650     | n/a     | ✅      | +10 Strength, Unusual Damage (4-24), Altered Durability (10) |
| The Celestial Axe                  | Battle Axe   | 14,100    | 4       | ❌      | -15 Strength, +15 Life, +15% To Hit, No Strength Requirements |
| Hellslayer                         | Battle Axe   | 26,200    | 15      | ❌      | +8 Strength, +8 Vitality, +25 Life, -25 Mana, +100% Damage |
| The Mangler                        | Large Axe    | 2,850     | 2       | ✅<sup>[^101]</sup> | -5 Magic, -5 Dexterity, -10 Mana, +200% Damage |
| Messerschmidt’s Reaver              | Great Axe    | 58,000    | 25      | ✅      | +5 All Attributes, -50 Life, +15 Damage, +200% Damage, 2-12 Fire Damage |
| Sharp Beak                         | Large Axe    | 2,850     | 2       | ✅<sup>[^104]</sup> | -10 Magic, +20 Life, -10 Mana |
| Stonecleaver                       | Broad Axe    | 23,900    | 7       | ✅      | +30 Life, +20% To Hit, +50% Damage, +40% Resist Lightning |
| Wicked Axe                         | Large Axe    | 31,150    | 5       | ✅<sup>[^104]</sup> | +10 Dexterity, -10 Vitality, +30% To Hit, -1 to -6 Damage from Enemies, Indestructible |

[^101]: **These items share the same picture, which is that of a normal axe.**  
[^102]: **Applies to the total damage.**  
[^103]: **A quest item only available in single player.**  
[^104]: **These items share the same picture, which is that of a normal great axe.**  


### Bows

| **Name**            | **Base Item**    | **Price** | **qlvl** | **Pic** | **Magical Effects** |
|--------------------|----------------|----------:|--------:|:------:|------------------------------------------------------------|
| The Blackoak Bow  | Long Bow       | 2,500     | 5       | ❌      | +10 Dexterity, -10 Vitality, +50% Damage, -10% Light Radius |
| Bow of the Dead   | Composite Bow  | 2,500     | 5       | ✅<sup>[^105]</sup> | -3 Vitality, +4 Dexterity, +10% To Hit, -20% Light Radius, Altered Durability (30) |
| The Celestial Bow | Long Bow       | 1,200     | 2       | ✅      | AC 5, +2 Damage, No Strength Requirement |
| Deadly Hunter     | Composite Bow  | 8,750     | 3       | ✅<sup>[^105]</sup> | -5 Magic, +20% To Hit, +200% Damage versus Demons |
| Eaglehorn        | Long Battle Bow | 42,500    | 26      | ✅<sup>[^105]</sup> | +20 Dexterity, +50% To Hit, +100% Damage, Indestructible |
| Flamedart        | Hunter’s Bow    | 14,250    | 10      | ❌      | +20% To Hit, +40% Resist Fire, 1-6 Fire Arrows<sup>[^106]</sup> |
| Fleshstinger     | Long Bow        | 16,500    | 13      | ❌      | +15 Dexterity, +40% To Hit, +80% Damage, High Durability (37) |
| The Needler      | Short/Cross Bow | 8,900     | 2       | ✅      | +50% To Hit, Unusual Item Damage (1-3), Fast Attack |
| The Rift Bow     | Short Bow       | 1,800     | 1       | ❌      | -3 Dexterity, +2 Damage, Random Speed Arrows |
| Windforce       | Long War Bow    | 37,750    | 17      | ✅      | +5 Strength, +200% Damage, Knocks Target Back |
| Blitzen         | Composite Bow   | 30,000    | 13      | ✅      | Lightning Damage 10-15<sup>[^107]</sup>, Unusual Item Damage (0), Indestructible |
| Flambeau        | Composite Bow   | 30,000    | 11      | ✅      | Fireball Damage 15-20<sup>[^108]</sup>, Unusual Item Damage (0), Indestructible |
| Gnat Sting      | Hunter’s Bow    | 30,000    | 15      | ✅      | Multiple Arrows, Unusual Item Damage (1-2), Quick Attack, Indestructible |

[^105]: **These items share the same picture.**  
[^106]: **The fire arrow damage is listed twice, but the real fire damage is only applied once and is in the range of 1-6.**  
[^107]: **Will cast a Lightning spell when fired.**  
[^108]: **Will cast a Fireball when fired.**  


### Clubs

| **Name**             | **Base Item**         | **Price**  | **qlvl** | **Pic** | **Magical Effects** |
|---------------------|---------------------|-----------:|---------:|:------:|------------------------------------------------------------|
| Baranar’s Star     | Morning Star        | 6,850      | 5        | ❌      | -4 Dexterity, +4 Vitality, +12% To Hit, +80% Damage, Quick Attack, Altered Durability (60) |
| The Celestial Star | Flail               | 7,810      | 2        | ✅<sup>[^109]</sup> | AC -8, +10 Damage, +20% Light Radius, No Strength Requirement |
| Civerb’s Cudgel    | Mace                | 2,000      | 1        | ❌      | -2 Magic, -5 Dexterity, +200% Damage versus Demons<sup>[^110]</sup> |
| Crackrust         | Mace                | 11,375     | 1        | ❌      | +2 All Attributes, +15% Resist All, +50% Damage, -1 Spell Level, Indestructible |
| The Cranium Basher | Maul                | 36,500     | 12       | ✅<sup>[^109]</sup> | +15 Strength, -150 Mana, +20 Damage, +5% Resist All, Indestructible |
| Dreamflange       | Mace                | 26,450     | 26       | ❌      | +30 Magic, +50 Mana, +50% Resist Magic, +1 Spell Levels, +20% Light Radius |
| Gnarled Root      | Club/Spiked Club    | 9,820      | 9        | ❌      | AC -10, +5 Magic, +10 Dexterity, +20% To Hit, +10% Resist All, +300% Damage |
| Hammer of Jholm   | Maul                | 8,700      | 1        | ❌      | +3 Strength, +4-10% Damage, +15% To Hit, Indestructible |
| Lightforge<sup>[^111]</sup> | Mace       | 26,675     | 1        | ❌      | +8 All Attributes, +25% To Hit, +150% Damage, +10-20 Fire Damage, +40% Light Radius, Indestructible |
| Schaefer’s Hammer | War Hammer          | 56,125     | 16       | ❌      | +50 Life, +75% Resist Lightning, +30% To Hit, -100% Damage, 1-50 Lightning Damage, +10% Light Radius |
| Thunderclap       | War Hammer          | 30,000     | 13       | ✅      | +20 Strength, +30% Resist Lightning, Charged Bolt (3-6 Damage), +20% Light Radius, Indestructible |

[^109]: **These items actually have the unique picture of the same item they are based on, so for all practical reasons, they don’t really have a unique picture.**  
[^110]: **Applies to total damage.**  
[^111]: **Does not exist in *Hellfire* and is not possible to find in *multiplayer* in *Diablo*, only in *single-player*. Still very rare in single-player (see chapter 3.5.2 for more information). It also seems that although findable in single-player, it will morph as soon as a new game is started or loaded.**  


### Helms

| **Name**             | **Base Item**       | **Price**  | **qlvl** | **Pic** | **Magical Effects** |
|---------------------|------------------|-----------:|---------:|:------:|------------------------------------------------------------|
| Fool’s Crest      | Helm             | 10,150     | 12       | ✅      | -4 All Attributes, +100 Life, +1-6 Damage from Enemies, 1-3 Damage to Attacker |
| Gotterdamerung<sup>[^112]</sup> | Great Helm      | 54,900     | 21       | ✅<sup>[^113]</sup> | AC 60, +20 All Attributes, All Resistances = 0%<sup>[^114]</sup>, -4 Damage from Enemies, -40% Light Radius |
| Harlequin Crest<sup>[^115]</sup> | Harlequin Crest | 4,000      | n/a      | ✅ | AC -3, +2 All Attributes, +7 Mana, +7 Life, -1 Damage from Enemies |
| Helm of Sprits    | Helm             | 7,525      | 1        | ✅<sup>[^116]</sup> | 5% Steal Life |
| Overlord’s Helm   | Helm             | 12,500     | 7        | ✅      | +20 Strength, -20 Magic, +15 Dexterity, +5 Vitality, Altered Durability (15) |
| Royal Circlet     | Crown            | 24,875     | 27       | ✅      | AC 40, +10 All Attributes, +40 Mana, +10% Light Radius |
| Thinking Cap      | Skull Cap        | 2,020      | 6        | ✅      | +30 Mana, +20% Resist All, +2 Spell Levels, Altered Durability (1) |
| The Undead Crown<sup>[^115]</sup> | Undead Crown   | 16,650     | n/a      | ✅<sup>[^116]</sup> | AC 8, 0-12.5% Steal Life |
| Veil of Steel<sup>[^115]</sup> | Veil of Steel   | 63,800     | n/a      | ✅<sup>[^113]</sup> | +15 Strength, +15 Vitality, -30 Mana, +60% Armor, +50% Resist All, -20% Light Radius |

[^112]: **These items have the same picture.**  
[^113]: **If you wear both a *Gotterdamerung* and a *Constricting Ring*, your resistance would still be 0%.**  
[^114]: **A quest item only available in *single-player*.**  
[^115]: **A quest item only available in *single-player*.**  
[^116]: **These items have the same picture. The *Helm of Sprits* looks like a crown when on the ground.**  


### Jewelry

| **Name**              | **Base Item** | **Price**  | **qlvl** | **Pic** | **Magical Effects** |
|----------------------|-------------|-----------:|---------:|:------:|---------------------------------------------------------------|
| The Bleeder        | Ring        | 8,500      | 2        | ✅      | +30 Mana, -10 Life, +20% Resist Magic |
| Bramble           | Ring        | 1,000      | 1        | ✅      | -2 All Attributes, +10 Mana, +3 Damage |
| Constricting Ring | Ring        | 62,000     | 5        | ✅      | +75% Resist All<sup>[^117]</sup>, Causes Continuous Damage (1.25 Life/sec)<sup>[^118]</sup> |
| Empyrean Band<sup>[^119]</sup> | Ring        | 8,000      | n/a      | ✅      | +2 All Attributes, Fast Hit Recovery, Absorbs Half of Trap Damage, +20% Light Radius |
| Optic Amulet<sup>[^119]</sup> | Amulet      | 9,750      | n/a      | ✅      | +5 Magic, +20% Resist Lightning, -1 Damage from Enemies, +20% Light Radius |
| Ring of Engagement | Ring        | 12,476     | 11       | ✅      | AC 5, -1 or -2 Damage from Enemies, 1-3 Damage to Attacker, Damages Target’s Armor<sup>[^120]</sup> |
| Ring of Regha     | Ring        | 4,175      | 1        | ✅      | -3 Strength, +10 Magic, -3 Dexterity, +10% Resist Magic, +10% Light Radius |
| Ring of Truth<sup>[^119]</sup>  | Ring        | 9,100      | n/a      | ✅      | +10 Life, +10% Resist All, -1 Damage from Enemies |
| Amulet of Warding | Amulet      | 30,000     | 12       | ✅      | -100 Life, +40% Resist All |
| Acolyte’s Amulet  | Amulet      | 10,000     | 10       | ✅      | 50% of Base Mana Moved to Life |
| Auric Amulet<sup>[^121]</sup>  | Amulet      | 100       | n/a      | ✅      | Allows You to Carry Piles of 10,000 Gold |
| Giant’s Knuckle  | Ring        | 8,000      | 8        | ✅      | +60 Strength, -30 Dexterity |
| Gladiator’s Ring | Ring        | 10,000     | 10       | ✅      | 40% of Base Life Moved to Mana |
| Karik’s Ring     | Ring        | 8,000      | 8        | ✅      | -30 Magic, +60 Vitality |
| Mercurial Ring   | Ring        | 8,000      | 8        | ✅      | -30 Strength, +60 Dexterity |
| Ring of Magma    | Ring        | 8,000      | 8        | ✅      | -30% Resist Magic, +60% Resist Fire, -30% Resist Lightning |
| Ring of the Mystics | Ring     | 8,000      | 8        | ✅      | +60% Resist Magic, -30% Resist Fire, -30% Resist Lightning |
| Ring of Thunder  | Ring        | 8,000      | 8        | ✅      | -30% Resist Magic, -30% Resist Fire, +60% Resist Lightning |
| Xorine’s Ring    | Ring        | 8,000      | 8        | ✅      | -30 Strength, +60 Magic |

[^117]: **The effect is +75%, *not* max resistance.** If you wear both a *Gotterdamerung* and a *Constricting Ring*, your resistance would still be 0%. Similarly, if you use an item that decreases any resistance, the final value may not be 75%.  
[^118]: **If you are using Mana Shield, the damage will be taken from your mana instead.** Due to rounding errors, the actual value may not be correctly reduced. See chapter 6.1.1 for more information.  
[^119]: **A quest item only available in *single-player*.**  
[^120]: **Has an effect equivalent to "of Puncturing".** In *Diablo*, adds +4-12 To Hit. In *Hellfire*, it reduces AC by 87.5% (or 12.5% if Barbarian, making any monster’s AC = 0), making it more effective than other suffixes with similar properties.  
[^121]: **A quest item, not truly a unique item.**  


### Shields

| **Name**             | **Base Item**          | **Price**  | **qlvl** | **Pic** | **Magical Effects** |
|----------------------|----------------------|-----------:|---------:|:------:|---------------------------------------------------------------|
| Blackoak Shield     | Small Shield         | 5,725      | 4        | ✅[^122]   | AC 18, +10 Dexterity, -10 Vitality, -10% Light Radius, High Durability (60) |
| The Deflector      | Buckler              | 1,500      | 1        | ✅[^123]   | AC 7, +10% Resist All, -20% Damage, -5% To Hit |
| Dragon’s Breach    | Kite Shield          | 19,200     | 2        | ✅      | AC 20, +5 Strength, -5 Magic, +25% Resist Fire, Indestructible |
| Holy Defender      | Large Shield         | 13,800     | 10       | ✅[122]   | AC 15, -2 Damage from Enemies, +20% Resist Fire, Fast Block, High Durability (96) |
| Split Skull Shield | Buckler              | 2,025      | 1        | ✅      | AC 10, +10 Life, +2 Strength, -10% Light Radius, Altered Durability (15) |
| Stormshield       | Gothic Shield / Tower Shield<sup>[^122]</sup> | 49,000     | 24       | ✅[^124]   | AC 40, +4 Damage from Enemies, +10 Strength, Fast Block, Indestructible |

[^122]: **These items share the same picture.**  
[^123]: **The Deflector has a normal Buckler’s sprite.**  
[^124]: **Both versions of Stormshield use the normal Gothic Shield sprite.**  


### Staves

| **Name**         | **Base Item**     | **Price**  | **qlvl** | **Pic** | **Magical Effects** |
|-----------------|----------------|-----------:|---------:|:------:|-----------------------------------------------------------|
| Gleamsong      | Short Staff    | 6,520      | 8        | ✅      | +25 Mana, -3 Strength, -3 Vitality, 76 Phasing Charges |
| Immolator      | Long Staff     | 3,900      | 4        | ✅      | +10 Mana, -5 Vitality, +20% Resist Fire, 4 Fire Damage |
| Mindcry        | Quarter Staff  | 41,500     | 20       | ✅      | +15 Magic, +15% Resist All, +1 Spell Level, 69 Guardian Charges |
| Naj’s Puzzler  | Long Staff     | 34,000     | 18       | ✅      | +20 Magic, +10 Dexterity, +20% Resist All, -25 Life, 57 Teleport Charges |
| The Protector  | Short Staff    | 17,240     | 16       | ✅[^125] | AC 40, +5 Vitality, -5 Damage from Enemies, 1-3 Damage to Attacker, 86 Healing Charges |
| Rod of Onan    | War Staff      | 44,167     | 22       | ✅      | +5 All Attributes, +100% Damage, 50 Golem Charges |
| Staff of Shadows | Long Staff  | 1,250      | 2        | ✅      | -10 Magic, +10% To Hit, +60% Damage, -20% Light Radius, Quick Attack |
| Storm Spire    | War Staff      | 22,500     | 8        | ✅      | +10 Strength, -10 Magic, +50% Resist Lightning, 2-8 Lightning Damage |
| Thundercall    | Composite Staff | 22,250     | 14       | ✅      | +35% To Hit, 1-10 Lightning Damage, +30% Resist Lightning, +20% Light Radius, 76 Lightning Charges |

[^125]: **The Protector looks like a club when on the ground.**


### Swords

| **Name**              | **Base Item**       | **Price**  | **qlvl** | **Pic** | **Magical Effects** |
|----------------------|------------------|-----------:|---------:|:------:|-----------------------------------------------------------|
| Black Razor        | Dagger           | 2,000      | 1        | ✅      | +2 Vitality, +150% Damage, Altered Durability (5) |
| The Bonesaw        | Claymore         | 4,400      | 6        | ✅      | +10 Strength, -5 Dexterity, -5 Magic, +10 Life, -10 Mana, +10 Damage |
| The Defender       | Sabre            | 2,000      | 1        | ✅      | AC 5, +5 Vitality, -5% To Hit |
| Doombringer        | Bastard Sword    | 18,250     | 19       | ✅      | -5 All Attributes, -25 Life, +25% To Hit, +250% Damage, -20% Light Radius |
| The Executioner’s Blade | Falchion   | 7,080      | 3        | ✅      | -10 Life, +150% Damage, -10% Light Radius, High Durability (60) |
| The Falcon’s Talon | Scimitar         | 7,867      | 15       | ✅[^126] | +10 Dexterity, +20% To Hit, -33% Damage, Fastest Attack |
| Gibbous Moon       | Broad Sword      | 6,660      | 2        | ✅      | +2 All Attributes, +15 Mana, +25% Damage, -30% Light Radius |
| Gonnagal’s Dirk    | Dagger           | 7,040      | 1        | ✅      | -5 Dexterity, +4 Damage, +25% Resist Fire, Fast Attack |
| The Grandfather    | Great Sword      | 119,800    | 27       | ✅      | +5 All Attributes, +20 Life, +20% To Hit, +70% Damage, Only Requires One Hand |
| Griswold’s Edge    | Griswold’s Edge  | 42,000     | n/a      | ✅[^127] | -20 Life, +20 Mana, +25% To Hit, 1-10 Fire Damage, Fast Attack, Knocks Target Back |
| The Grizzly        | Two-Handed Sword | 50,000     | 23       | ✅      | +20 Strength, -5 Vitality, +200% Damage, Knocks Target Back, High Durability (150) |
| Gryphon’s Claw     | Falchion         | 1,000      | 1        | ✅[^126] | -2 Magic, -5 Dexterity, +100% Damage |
| Ice Shank          | Long Sword       | 5,250      | 3        | ✅      | +5-10 Strength, +40% Resist Fire, Altered Durability (15) |
| Inferno            | Long Sword       | 34,600     | 17       | ✅      | +20 Mana, +75% Resist Fire, 2-12 Fire Damage, +30% Light Radius |
| Lightsabre         | Sabre            | 19,150     | 13       | ✅      | +20% To Hit, +50% Resist Lightning, 1-10 Lightning Damage, +20% Light Radius |
| Shadowhawk        | Broad Sword      | 13,750     | 8        | ✅      | +15% To Hit, +5% Resist All, 5% Steal Life, -20% Light Radius |
| Wizardspike        | Dagger           | 12,920     | 11       | ✅      | +15 Magic, +35 Mana, +25% To Hit, +15% Resist All |
| Diamondedge        | Long Sword       | 42,000     | 17       | ✅      | AC 10, +50% Resist Lightning, +50% To Hit, +100% Damage, Altered Durability (10) |
| Eater of Souls     | Two-Handed Sword | 42,000     | 23       | ✅      | +50 Life, 5% Steal Life, 5% Steal Mana, Causes Continuous Damage When Worn, Indestructible |
| Shirotachi         | Great Sword      | 36,000     | 21       | ✅      | +6 Lightning Damage, Penetrates Target’s Armor (Half AC), Fastest Attack, One-Handed |

[^126]: **These items have the same picture.**  
[^127]: **A quest item only available in single player.**  
[^128]: **This item actually has the unique picture of the same item it is based on, so for all practical reasons it doesn’t really have a unique picture.**  



### 3.5.2 Unfindable unique items in multi player

Due to the way the game generates unique items (see chapter 3.8), some unique items will never be found in *multi player*. The same items are findable in single player but only if you find another unique item of the same base item and* qlvl first in the same game session. This phenomenon occurs when there are multiple items of the same base item and qlvl. The table below lists those items. Note that the list for Diablo is also applicable to Hellfire.

### Diablo vs. Hellfire Unique Items<sup>[^129]</sup>

| **Diablo**              | **Hellfire** |
|------------------------|----------------------------|
| Bramble (Ring)         | Armor of Gloom (Full Plate Mail) |
| Crackrust (Mace)       | Demonspike Coat (Full Plate Mail) |
| The Deflector (Buckler) | Giant’s Knuckle (Ring) |
| Gonnagal’s Dirk (Dagger) | The Grizzly (Two-Handed Sword) |
| Lightforge<sup>[^130]</sup> (Mace) | Inferno (Long Sword) |
| The Mangler (Large Axe) | Karik’s Ring (Ring) |
|                        | Mercurial Ring (Ring) |
|                        | Ring of Magma (Ring) |
|                        | Ring of the Mystics (Ring) |
|                        | Xorine’s Ring (Ring) |

[^129]: **In addition to the ones from Diablo.**  
[^130]: **It seems that although findable in single player, it will morph as soon as a new game is started or loaded.**  


The table below lists the order for those cases where more than two unique items have the same qlvl. All other cases only have two items with the same qlvl and it should be obvious that the unique item *not* in the table above is dropped first (and always dropped in multi player).

### Unique Item Order by Base Item<sup>[^131]</sup>

| **Base Item**      | **qlvl** | **Order, from First to Last** |
|-------------------|--------:|----------------------------------|
| Full Plate Mail  | 25     | Demon Plate Armor, Armor of Gloom, and Demonspike Coat |
| Mace            | 1      | Civerb’s Cudgel, Crackrust, and Lightforge |
| Ring            | 8      | Ring of Thunder, Ring of the Mystics, Ring of Magma, Karik’s Ring, Xorine’s Ring, Mercurial Ring, and Giant’s Knuckle |

[^131]: **In multiplayer, only the first unique item of each base type is findable.**  


## 3.6 Prices of magical items

This chapter will describe how the price of magical items is calculated. Please note that much of the information in this chapter was initially compiled and collected by Ironbeard. I have rewritten it quite a bit to better fit with the rest of the guide and newer findings.


### 3.6.1 Formulas

The price of a magical item is affected by three elements: the base effect of a prefix/suffix, the quality effect of a prefix/suffix, and the item’s base cost multiplied by the prefix/suffix intrinsic multiplier. On staves with spells there is an additional factor added to the item’s base cost which depends on the spell type and number of charges. The formulas for calculating the price of all magical items are given below.

### Magic Item Cost Formula

| **All magical items except staves with spells:** | **Condition** |
|--------------------------------|------------------|
| `C = Bp + Bs + Qp + Qs + I × (Mp + Ms)` | `If Mp + Ms ≥ 0` |
| `C = Bp + Bs + Qp + Qs + I / (Mp + Ms)` | `If Mp + Ms < 0` |

| **Staves with spells:** | **Condition** |
|------------------------|--------------|
| `C = Bp + Qp + (I + H × P) × Mp` | `If Mp ≥ 0` |
| `C = Bp + Qp + (I + H × P) / Mp` | `If Mp < 0` |


### **Definitions for Magic Item Cost Formula**

| **Variable** | **Meaning** |
|------------|------------|
| C  | Total cost |
| Bp | Base prefix effect |
| Bs | Base suffix effect |
| Qp | Quality effect of the prefix |
| Qs | Quality effect of the suffix |
| I  | Cost of base item |
| H  | Number of charges on staff |
| P  | Spell multiplier |
| Mp | Prefix intrinsic multiplier |
| Ms | Suffix intrinsic multiplier |


- On plentiful and bountiful staves, one should take the *base* amount of charges. That is, divide the number of charges shown by 2 for plentiful and 3 for bountiful staves.

Some prefixes/suffixes, like *speed* or *the ages,* do not have the Q to affect the price, and in such cases the price formulas would be simplified to:

### Magic Item Cost Formula

| **All magical items except staves with spells:** | **Condition** |
|------------|--------------|
| `C = Bp + Bs + I × (Mp + Ms)` | `if Mp + Ms ≥ 0` |
| `C = Bp + Bs + I / (Mp + Ms)` | `if Mp + Ms < 0` |

| **Staves with spells:** | **Condition** |
|------------|--------------|
| `C = Bp + (I + H×P) × Mp` | `if Mp ≥ 0` |
| `C = Bp + (I + H×P) / Mp` | `if Mp < 0` |

**Cursed and semi-cursed items**

The lower formulas (if Mp + Ms <0 or Mp < 0) only come into play when you have a prefix/suffix with a negative multiplier. Only cursed prefixes and suffixes have that. However, one suffix, *of corruption*, although being a cursed one, has a positive multiplier. On the other hand, it has a negative base suffix effect. For items that are all cursed, the sum is always negative. For semi cursed items, that is, those that have one cursed and one non cursed prefix and suffix, one has to first calculate the sum of the two multipliers to see which formula to use.


**The quality effect, Q**

Let’s look into the somewhat trickier part, the Q thing. Some prefixes/suffixes have different levels of quality. For example, the suffix *vigor* can have an attribute boost on vitality ranging from 16 to 20 points. Or, the prefix *massive* can boost a weapon’s damage from 96% to 110%. This has an effect on the cost.

Let’s use the prefix *massive* as an example here. The lowest level of quality of that prefix is when it gives a weapon a damage boost of 96%. At that point, the prefix has the base effect B of 2000 and what is more, at that base level of quality, the prefix has no quality effect Q on the item’s price. If we take the highest quality (110%), we will have a quality effect Q of 450 on the price. Putting it together we can see that the B + Q can range from 2000 (the base B value) to 2450 (the max value). Subtracting 2000 from 2450 we get 450, which is the quality range of the prefix, we shall call it R (range).

Now, how about the different quality levels in between the base and the max values? Starting from the base at 96% we go on to 97%, 98%,… until we reach the max Q value at 110%. And we took 14 steps to get there (110 - 96 = 14). The quality level on the first step (97%) is 1/14 or 0.071428. On the second step it is 2/14 or 0.142857 and so on until on the last step (at 110%) it is 14/14 or 1. The Q can now be counted with the values we have:

`Q=L/S×R`

### Variable Definitions

| **Symbol** | **Meaning** |
|-----------|------------|
| L | Location or quality level |
| S | Total number of steps in the prefix/suffix |
| R | Range of the quality effect (Max - Base) |

One important note here: When counting the value of L/S and you get something like 0.071428 or 0.777777 (7/9) you take into account only two digits after the decimal, meaning that in the first case we would have the L/S to yield 0.07 and in the second case 0.77. Alternatively one can use the formula below in which case the rounding is done automatically:

`Q = [ { [ (100×(Stat - MinStat)) / (MaxStat - MinStat) ] × (Max - Base) } / 100 ]`


**Unidentified magical item**

An unidentified magical item has a price as given below.

All magical items except staves with spells:

`C = I`

Staves with spells:

`C=I+H×P`


### 3.6.2 Additional notes on the prices

On any armor or helm, the actual armor class has no effect on the price, i.e. full plate (AC 74) of ages has the same price as full plate (AC 69) of ages. In the prefixes like *Warrior’s* and *king’s* which give weapons a boost both to the To Hit and damage, the To Hit does not affect the price, only the damage quality level has an effect on the price.

For items that are not cursed or semi cursed (or rather Mp + Ms > 0), one can calculate the price of an item having both a prefix and a suffix as two separate items, one having the prefix and one having the suffix, and simply add the prices together.

You can sell items to Griswold and Adria for one fourth of the item’s price. Wirt’s price is 150% times Griswold’s price in Diablo and 75% times Griswold’s price in Hellfire. Some items can be sold by both Griswold and Wirt and identical items can thus have different prices depending on where you bought it. Items found in dungeons always have Griswold prices. Any item bought at Wirt will have its price reset to the normal one, 100% of Griswold’s price, as soon as you start a new game, give it away, or leave it on the ground and go to another dungeon level or town.

You can’t sell an item at Griswold if you will be given more gold for it than can fit in your inventory. At Adria, however, any excess gold will simply be discarded.


### 3.6.3 Recharge cost

Staves can be recharged at Adria (or by a Sorcerer, see chapter 2.4). The cost to recharge a staff can be calculated using the formula below:

`RcC = FRcC × (1 - CurCha/MaxCha)`

### Variable Definitions for Recharge Cost Calculations

| **Symbol** | **Meaning** |
|-----------|------------|
| RcC | Recharge Cost |
| FRcC | Full Recharge Cost (see below) |
| MaxDur | Maximum charges on item |
| CurDur | Current charges on item |


The Full Recharge Cost in the formula above can be calculated with:

`FRcC = 0.50 × (I + 5×P)`	if unique or starting staff of the Sorcerer

`FRcC = 0.50 × (I + H×P + 5×P)`	if *not* unique and *not* starting staff of the Sorcerer

### Variable Definitions for Recharge Cost Calculations

| **Symbol** | **Meaning** |
|-----------|------------|
| FRcC | Full Recharge Cost |
| I | Cost of base item (always a staff) |
| H | Number of charges on staff |
| P | The spell multiplier |


- The base cost of the starting staff for Sorcerers can be found in chapter 2.5. For other staves, see chapter 3.1.
- On plentiful and bountiful staves, one should take the *base* amount of charges. That is divide the number of charges shown by 2 for plentiful and 3 for bountiful staves.
- As the recharge cost is not influenced by the prefix of the staff, there is no difference to the recharge cost between an identified and an unidentified staff.
- If a Sorcerer uses his recharge skill on a staff, one should still use the initial number of charges in the formula.

If the recharge cost is less than 1 gold (can happen if the ratio CurDur/MaxDur is less than 1%), Adria will actually recharge the staff for free, that is 0 gold.

Just as with the price of magical items, when counting the value of CurCha/MaxCha you take into account only two digits after the decimal. Alternatively one can use the formula below in which case the rounding is done automatically:

`RcC = [ [ { [ (100×(MaxCha - CurCha)) / MaxCha ] × (I + H×P + 5×P) } / 100 ] / 2 ]`

- Of course, for unique staves and the starting staff of the Sorcerer, skip H×P in the formula above.

## 3.7 Durability of items

All unique items and staves with spells found in the dungeon have full durability. So do all items bought in town, of course. All other items found in the dungeon only have partial durability in the range below:

Durability of items found in dungeon:	`(1 + maxdur/4) to 3×maxdur/4`


### 3.7.1 Losing durability

All items (except those that are indestructible) have a durability, which will, over time, decrease as you fight. The table below explains under what circumstances and with what chance the durability will go down. It will never go down by more than 1 at a time.

### **Durability Loss Conditions**

| **Item Type**  | **When Durability May Decrease** | **Chance of Decreasing** |
|---------------|---------------------------------|--------------------------|
| Armor<sup>[^132]</sup>  | Character is stunned      | 3/4 × 2/3 = 1/2<sup>[^133]</sup> (50.0%) |
| Helm<sup>[^132]</sup>   | Character is stunned      | 3/4 × 1/3 = 1/4<sup>[^133]</sup> (25.0%) |
| Shield       | Character blocks an attack      | 1/10 (10.0%)  |
| Melee Weapon | Character hits                 | 1/30 (3.3%)  |
| Bow         | Character fires                 | 1/40 (2.5%)  |

[^132]: If you don’t wear both armor and helm but only one of them, the chance is 3/4 that its durability will be decreased.  
[^133]: You will never lose durability on both the armor and the helm in the same hit.



### 3.7.2 Repair cost

Repairs are done at Griswold (or by a Warrior, see chapter 2.4). Griswold uses the following formulas to calculate the cost:

### **Repair Cost Formulas**

| **Formula** | **Applies To** | |
|------------|--------------|--|
| RpC = 0.15 × Price × (1 - CurDur/MaxDur) | For magical and unique items | |
| RpC = 0.50 × Price × (1 - CurDur/MaxDur) | For non-magical and unidentified items | |

### Variable Definitions for Repair Cost Calculations

| **Variable** | **Definition** |
|-------------|--------------|
| RpC | Repair Cost |
| Price | Buying price of the item |
| MaxDur | Maximum durability of the item |
| CurDur | Current durability of the item |


If the repair cost is less than 1 gold Griswold won’t repair it. That makes many of the cursed items irreparable. There also seems to be a bug so that when the ratio CurDur/MaxDur is greater than 99%, the repair cost is rounded down to 0 along the way and is thus not repairable until it takes more damage.

Just as with the price of magical items, when counting the value of CurDur/MaxDur you take into account only two digits after the decimal. Alternatively one can use the formulas below (plus the step by step list following) in which case the rounding is done automatically:

For magical and unique items first calculate:

`RpC = [ { [ (100×(MaxDur - CurDur)) / MaxDur] × (30 × Price) } / 100 ]`

For non magical and unidentified items first calculate:

`RpC = [ { [ (100×(MaxDur - CurDur)) / MaxDur] × Price } / 100 ]`

Then, do the following:

1. **If** `RpC = 1`, **then exit**.
2. **If** `RpC > 1`, **then** `RpC = [RpC / 2]` (divide the repair cost by 2), **then exit**.
3. **If** the item is a **non-magical and non-unique** item, **set** `RpC = 1`, **then exit**.
4. **If** the item is **not identified**, **set** `RpC = 1`, **then exit**.
5. At this point, the item is an **identified magical or unique item** and `RpC` is `0` or below `0`;  
   - The item is **not repairable** (this applies to identified **cursed** and some **semi-cursed** items).

## 3.8 Item creation in dungeon

This chapter tries to explain how the game creates items and what factors affect the creation. Only items generated in the dungeon are discussed. Some of it applies to items created in town as well, but for more details about items created in town, see chapter 3.9. Most of this chapter will not refer specifically to the Hive or the Crypt, but as with much else, they should be equivalent to Caves and Hell. Some quests will give you special items (not counting the special quest items). For information about them, see each individual quest in chapter 8.

In most of the situations below the game has to pick a certain item, prefix/suffix, unique, spell, or other property of an item out of several possible ones or within a range. Unless otherwise noted the probability should be equal for all possible choices in that situation.

Base item in this chapter not only refers to the various equipable items, but also includes scrolls, potions, elixirs, runes, books of and oils of; see chapters 3.1 - 3.2.3 for information about them.

An item can come from many different sources in the dungeon, and depending on the source, the creation routine is a bit different. To facilitate the explanation below let us first define a new term, *ilvl.* It is defined for various sources in the table below. For information about a monsters mlvl or mlvlitem, see chapters 5.2 and 5.4.

### Source of Item and Item Level (ilvl) Definitions

| **Source of Item** | **Definition of ilvl** |
|--------------------|-----------------------|
| Normal monster | `mlvl`<sup>[^134]</sup> |
| Unique monster and special monster<sup>[^135]</sup> | `mlvl`<sub>`item`</sub><sup>[^136]</sup> |
| Decapitated body, sarcophagus, on the ground<sup>[^137]</sup>, bookcase, skeleton | `2 × dlvl`<sup>[^138]</sup> |
| Tome, library book, and racks | - |
| Chest, barrel, pod, urn | `2 × dlvl` or `dlvl`<sup>[^138][^139]</sup> |

[^134]: Use the `mlvl` for normal difficulty regardless of what difficulty you are playing on.  
[^135]: Note that for the purpose of dropping items, Diablo is neither a special nor a unique monster but a normal one.  
[^136]: The +4 bonus will be found in the appropriate steps below.  
[^137]: You will often find potions of various sorts on the ground; they are specially placed there and are not generated according to normal rules.  
[^138]: The Hive levels are numbered 9-12, and the Crypt levels are numbered 13-16.  
[^139]: Most chests, barrels, pods, and urns have an `ilvl` equal to `2 × dlvl`, although some have it equal to dlvl. Those that have `ilvl` equal to `dlvl` will only generate potions and scrolls (and oils in *Hellfire*). See chapter 3.8.1 for more information. Items created with an `ilvl = dlvl` are referred to as *special items* in this chapter.  


**Special items**

Special items appear on those occasions where the item created will not follow normal procedures. Such special items will normally only generate potions and scrolls (in Hellfire it also includes oils). For more information about what base items are possible for special items, see chapter 3.8.3.


### 3.8.1 What is dropped?

First the game has do decide if an item is to be dropped at all, if it is going to be gold or an item. The exact probabilities for these are greatly affected by the source of the item. Each source is explained below.

### Monsters

#### Normal Monster Drop Chances

| **Drop Type** | **Chance** |
|--------------|-----------|
| Gold        | 30.3%     |
| Item        | 10.7%     |
| Nothing     | 59.0%     |

- Some monster types (Winged Fiends and Hork Spawns) never drop items.

#### Unique Monster Drop Chances

| **Drop Type** | **Chance** |
|--------------|-----------|
| Item        | 100%     |

- Unique monsters always drop an item, and it can either be a book or an item that can take on a prefix and/or suffix (or be unique).

### Chests

Chests can have several possible amounts of items in them and the exact amount is also affected by the size of the chest. The number of *possible* items from a chest is explained in the table below.

#### Possible Number of Items in Chests

| **Number of Possible Items** | **Small Chest** | **Chest** | **Large Chest** |
|------------------------------:|:--------------:|:---------:|:--------------:|
| 0                              | 50%            | 33.3%     | 25%            |
| 1                              | 50%            | 33.3%     | 25%            |
| 2                              | -              | 33.3%     | 25%            |
| 3                              | -              | -         | 25%            |


For each chest the probability of the items in them being created with varying ilvl is:

#### Probability of Type of Items in Chests

| **Item Type**                    | **Chance** |
|----------------------------------:|----------:|
| Special item (`ilvl = dlvl`)      | 12.5%     |
| Non-special item (`ilvl = 2 × dlvl`) | 87.5%     |


All items in a chest will thus either be all special items or all non special items. For each *possible* item in a chest without special items, the probability is then as follows:

#### Probability of Gold in Chests

| **Type**  | **Chance** |
|---------:|----------:|
| Gold     | 75%       |
| Item     | 25%       |

If the chest is determined to have special items, all possible items will drop as special items. For information about items created by different ilvl, see chapter 3.8.2.

Chests only exist in church, catacombs, caves and hell.


### Other Objects

Pods and Urns are, for item creation, treated as barrels, so anything said about barrels below applies equally to pods and urns.

Barrels can be of two different types, exploding and non exploding. For information about exploding barrels, see chapter 4.3. Approximately 20% of all barrels are exploding ones. The information below will only apply to *non* exploding barrels. Exploding barrels will never have items in them.

#### Drop Rates for Barrels

| **Drop Type**    | **Chance** |
|-----------------:|----------:|
| Skeleton        | 20%       |
| Gold           | 10%       |
| Special item   | 6.7%      |
| Item           | 3.3%      |
| Nothing        | 60%       |

- Barrels can only exist in church, catacombs, caves and hell.
- Pods can only exist in the Hive.
- Urns can only exists in the Crypt.


#### Drop Rates for Sarcophagi

| **Drop Type**   | **Chance** |
|---------------:|----------:|
| Skeleton      | 20%       |
| Gold         | 22.5%     |
| Item         | 7.5%      |
| Nothing      | 50%       |

- Sarcophagi can only exist in church and in the crypt.


#### Drop Rates for Decapitated Bodies

| **Drop Type** | **Chance** |
|-------------:|----------:|
| Gold        | 75%       |
| Item        | 25%       |

- Decapitated bodies can only exist in catacombs, caves and hell.


#### Drop Rates for Weapon Racks

| **Drop Type** | **Chance** |
|-------------:|----------:|
| Axe         | 25%       |
| Bow         | 25%       |
| Club        | 25%       |
| Sword       | 25%       |


- Weapon racks can never exist in church.


#### Armor Rack Armor Types

| **Dungeon Level (`dlvl`)** | **Armor Type**  |
|--------------------------:|----------------|
| `5`                      | Light Armor    |
| `6 - 9`                  | Medium Armor   |
| `10 - 15`                | Heavy Armor    |


- See chapter 3.1 for a definition of light, medium and heavy armor.
- Armor racks can never exist in church.


#### Drop Rates for Bookcases

| **Drop Type** | **Chance** |
|-------------:|----------:|
| Book         | 100%       |

- Bookcases can only exist in church and catacombs.

#### **Library Book and Skeleton Tome Drop Rates**

| **Drop Type** | **Chance** |
|--------------|----------:|
| Book        | 20%       |
| Scroll      | 80%       |


- Only scrolls of Apocalypse, Healing, Identify, Infravision, Nova, Mana Shield, Phasing, Teleport, and Town Portal are possible.
- Library books and Skeleton Tomes can only exist in church and catacombs.

### 3.8.2 Item type

Next, the item type that is to be generated is determined, and the procedure is as follows (this step is skipped for gold and special items).


**Determination of base item**

First, it has to be determined what the base item should be. For information about base items, see chapters 3.1 and 3.2. Each base item has a qlvl, and those within the ranges below can be dropped. Depending on the source of the item some base items are, of course, excluded (see chapter 3.8.1).

| **Source**              | **Range**        |
|-------------------------|----------------:|
| Normal and special monster | `1` to `mlvl` |
| Unique monster           | `1` to `mlvl`<sub>`battle`</sub> |
| Other                   | `1` to `ilvl`   |


- Note that the mlvl is the one modified for difficulty level when the item comes from a monster.

Of all the possible base items, one is chosen at random with an equal probability for all items. Bows, however, are actually counted twice if the item is dropped by a normal (non unique or special) monster, and thus have a double chance of being created. Note that some base items like rings, amulets, and books have several different base items with different qlvl. You will never notice any difference when playing other than them being more common as the ilvl and mlvl go up (as more of each type is possible at higher ilvl and mlvl). See chapter 3.13.1. for a list of base items in the order of their qlvl.


**Is it magical?**

Now it is time to determine if the item is magical or not. Only items that can have a prefix/suffix (or be unique) can be magical. For other items this test is not done. The probability of being magical is as follows depending on the source of the item:

| **Source**                           | **Chance** |
|--------------------------------------|------------:|
| Unique monster                        | 100% |
| On the ground                         | 100% |
| Weapon rack                           | 100% |
| Armor rack on `dlvl 5` and `dlvl 13-15` | 100% |
| Armor rack on `dlvl 6-9`              | `(55.5 + 0.445 × (ilvl + 1))%` |
| Armor rack on `dlvl 10-12`            | `(11 + 0.89 × (ilvl + 1))%` |
| Monster                               | `(11 + 0.89 × (ilvl + 1))%` |
| Other                                 | `(11 + 0.89 × (ilvl + 1))%` |


- Only equipable items can be magical; for other base items this step is not performed.
- Rings and amulets are always magical.
- Staves are always magical if they have no spell, see chapter 3.8.3 under *Staff* for more information.
- On the ground only refers to equipable items found, often in special rooms, in the dungeon. It is quite possible that the probability of those items being magical is less than 100% outside of Hell.

**Is it unique?**

If the item was determined to be magical it is next checked for to see if it is unique. The probability of being unique is listed below depending on source. Note that the probability to be unique is applied for this step only. The total probability of an item to be unique is of course less as not all items are magical or even could be magical.

| **Source**         | **Chance** |
|-------------------|------------:|
| Unique monster   | 16% |
| Other           | 2%  |


### 3.8.3 Item properties

Once the base item has been determined, the properties of the item are to be decided. In many cases the item can’t have additional properties. That is the case for scrolls, potions, non magical items (as determined by the step above), runes, and some oils (see chapter 3.2.1). If so, this step is not performed. Otherwise, the properties have to be determined, and the procedure depends a bit on what type of item it is. Thus, each item type will be dealt with separately.


**Gold**

The amount of gold dropped or found on the dungeon floor is determined by the formulas below:

| **Difficulty**          | **Gold Drop Range** |
|------------------------|------------------|
| Normal Difficulty     | `5 × dlvl` to `15 × dlvl - 1` |
| Nightmare Difficulty  | `5 × (16 + dlvl)` to `15 × (16 + dlvl) - 1` |
| Hell Difficulty       | `5 × (32 + dlvl)` to `15 × (32 + dlvl) - 1` |

- The Hive levels are numbered 9-12 and the Crypt levels are numbered 13-16.

Furthermore, on any hell dungeon level (dlvl 13-16) or Crypt dungeon level (dlvl 13-16) the amount of gold is increased by:

Hell or Crypt dungeon level:	`amount × 1.125`

- The amount is taken from the appropriate formula above depending on the difficulty level.

**Unique item**

If the item is determined to be unique, the game will drop the unique item that is of the correct base item (determined above) and that has a qlvl according to below:

| **Source**                 | **Quality Level Range** |
|---------------------------|---------------------|
| Unique and Special Monster | `1 to ilvl + 4` |
| All Other Sources          | `1 to ilvl` |


If several unique items are possible, the one with the highest qlvl will be dropped. If several unique items that are possible have the same qlvl, the one that happens to be first in the list will be dropped. This is the reason that some unique items will never be dropped as there is always another unique item with the same qlvl (and being of the same base item) that will be dropped instead. See chapter 3.5.2 for a list of such unique items.

In single player (but not in multi player) the game keeps track of what unique items have been dropped (or recreated at game start in a characters inventory) and if the same item is determined to be dropped again (or regenerated at game start), the next one with the same qlvl or the one with the next lower qlvl will instead be dropped. Thus in single player you can actually find those ”unfindable” unique items but you must find at last one other unique item of the same base item first. The game will forget the list of found unique items when you restart a new game however. The list is saved when you save the game in single player but not restored upon load except for those items you have equipped.

A unique item has up to 6 special properties, which are described in more detail in chapter 3.5. If for any reason the game fails to select a unique item (for example if there is no unique item with a low enough qlvl), the game will then proceed to create the item as a normal magical item instead.


**Magical item**

A magical item has a prefix and/or a suffix (it can of course also be unique but that is covered above). Below are the probabilities for an item having a prefix, a suffix, or both of them.

| **Modifier Type**     | **Chance**  |
|----------------------|------------:|
| Prefix only         | 20.8%       |
| Suffix only         | 62.5%       |
| Prefix and Suffix   | 16.7%       |

The qlvl of the prefix and/or suffix must be within the range given below:

| **Source**                 | **Quality Level Range (`qlvl`)** |
|----------------------------|----------------------------:|
| Unique and Special Monster | `[(ilvl + 4) / 2]` to `ilvl + 4` |
| All Other Sources          | `[ilvl / 2]` to `ilvl` |

- Round down the minimum level. If it is higher than 25, it is set to 25.
- The actual value of the prefix or suffix is chosen randomly within its range.
- Some prefixes has a double chance of being picked, see below.

The range above means that unless the lower limit is set to 25, the highest qlvl of an item with both a prefix and a suffix can’t be more than twice the level of the lower one. This rule is good to know when you want to see if a prefix and a suffix can coexist on an item. It is also worth noticing that as the range above is based on the mlvl, *not* modified for difficulty level (or 2×dlvl), so the prefix and suffix with the highest qlvl you will ever find in the dungeon has qlvl 34. There is no prefix or suffix in the range of 32-34, so qlvl 31 is the highest one you will find, and only emerald has that qlvl. In Hellfire (but not Diablo), Diablo is level 45, so he can drop items with prefixes and suffixes of qlvl up to 45. Similarly, Na-Krul can drop items with prefixes and suffixes of qlvl up to 44 as he is level 40, and the +4 bonus for being a unique monster applies to him. If for any reason the game fails to select a prefix and/or a suffix, the game will then proceed to create the item as a normal non magical item instead. See chapter 3.13.3 for a list of prefixes and suffixes in the order of their qlvl.

Some prefixes actually has a double chance of being chosen. The table below list all prefixes that has a double chance of being chosen.

| **+% Armor Class**  | **+% To Hit**  | **+% To Hit / +% Damage Done** | **+% Damage Done**  |
|---------------------|---------------|--------------------------------|---------------------|
| Vulnerable<sup>[^1]</sup>  | Tin<sup>[^1]</sup>    | Clumsy<sup>[^1]</sup>    | Useless<sup>[^1]</sup>   |
| Rusted<sup>[^1]</sup>      | Brass<sup>[^1]</sup>  | Dull<sup>[^1]</sup>      | Bent<sup>[^1]</sup>      |
| Fine             | Bronze        | Sharp<sup>[^1]</sup>      | Weak               |
| Strong          | Iron          | Fine                      | Jagged             |
| Grand           | Steel         | Warrior’s                 | Deadly             |
| Valiant         | Silver        | Soldier’s                 | Heavy              |
| Glorious        | Gold          | Lord’s                    | Vicious            |
| Blessed         | Platinum      | Knight’s                  | Brutal             |
| Saintly        | Mithril       | Master’s                  | Massive            |
| Awesome         | Meteoric      | Champion’s                | Savage             |
| Holy           | Weird         | King’s                     | Ruthless           |
| Godly          | Strange       |                             | Merciless          |

[^1]: A **cursed prefix**. See below for more information when possible.


Despite what has been said above, there are some combinations of prefixes and suffixes that can-not exist on the same item. The table below list all combinations that are. As the game always picks the prefix first, it is always the suffix that will be discarded; this can be important to know if one wants to figure out exactly what items are possible and the probabilities of them.

#### Incompatible Affix Combinations

| **Prefix 1**      | **Prefix 2**      |
|------------------|------------------|
| Angel’s         | Trouble          |
| Arch-Angel’s    | Trouble          |
| Blessed         | Trouble          |
| Frog’s          | Vitality         |
| Glorious        | Trouble          |
| Gold            | Pit              |
| Gold            | The Vulture      |
| Gold            | Corruption       |
| Vicious         | Vim              |
| Vicious         | Radiance         |
| Spider’s        | Vitality         |
| Gold            | Pain             |
| Gold            | The Dark         |
| Gold            | The Bear         |
| Mithril         | Trouble          |
| Platinum        | Trouble          |
| Saintly         | Trouble          |
| Silver         | Pit              |
| Silver         | The Vulture      |
| Silver         | The Bear         |
| Silver         | The Dark         |
| Vicious         | Vigor            |

Cursed prefixes and suffixes are those who give some sort of drawback to your character when you wear them. It is quite obvious for most prefixes and suffixes. For the ones affecting the light radius, the ones decreasing it are considered as cursed ones. The prefix *sharp* is also treated as cursed, most likely due to a bug. Cursed items are not allowed to appear when the item comes from certain sources. Below is listed if a source can give out cursed items, and if it can, how large the chance is compared to non cursed prefixes and suffixes.

| **Source**                                | **Cursed Chance** |
|-------------------------------------------|------------------------:|
| Unique Monsters                           | 0%                     |
| Weapon Rack                               | 0%                     |
| Armor Rack on `dlvl 5` and `dlvl 13-15`   | 0%                     |
| Armor Rack on `dlvl 6-9`                  | 16.5%                  |
| Armor Rack on `dlvl 10-12`                | 33.0%                  |
| Adria, Griswold, Pepin, and Wirt          | 0%                     |
| On the Ground                             | 0%                     |
| Other                                     | 33.0%                  |


- Sources that will not produce equipable items can never produce cursed items.
- If possible, a cursed prefix will, if it is found in the table above with prefixes with a double chance of being chosen, have a double chance compared to other cursed prefixes.

**Staff**

Staves can either have a spell or be normal magical items (of course, they can also be plain staves but that is very rare). The chances for what type the staff will be is as follows:

| **Condition**                                      | **Chance** |
|----------------------------------------------------|-----------:|
| Chance for having a spell                         | 75%        |
| Chance for having a prefix if it has a spell      | 10%        |

- Staves from a location that has a 100% chance of being magical will, if they have a spell, always have a prefix. as staves with spells without a prefix will not be considered as magical by the game.

Staves that do not have a spell, are treated the same way as any other magical item; see above. However, if they have a spell, they are created a bit differently. For the spell and the prefix they follow the ranges below:

| **Condition** | **Range of `qlvl`** |
|--------------|--------------------:|
| Spell on staves from unique and special monsters | `1` to `[(ilvl + 4) / 2]` |
| Spell on staves from all other sources | `1` to `ilvl / 2` |
| Prefix on staff with spell from unique and special monsters | `1` to `ilvl + 4` |
| Prefix on staff with spell from all other sources | `1` to `ilvl` |

- Note that the qlvl of a spell is different depending on whether it appears on a staff or on a book.

When found in the dungeon, all non unique staves with spells have full charges. Unique staves has a specific number of current charges according to the table below. All staves bought in town have full charges, of course.

#### **Number of Charges on Unique Staves When Found**<sup>[^1]</sup>

| **Unique Staff**   | **Number of Charges** |
|--------------------|---------------------:|
| Gleamsong         | 10  |
| Mindcry           | 13  |
| Naj’s Puzzler     | 23  |
| The Protector     | 2   |
| Rod of Onan       | 21  |
| Thundercall       | 3   |

[^1]: This is likely a bug. The intended behavior may have been for unique staves to have full charges when found. As it stands, the number of charges corresponds to the slot number in which the spell appears in the internal spell table.


Due to the way the game picks a random spell, some spells have a higher chance to be selected than others at a given situation. As the probabilities are different for different ilvl, it is hard to give exact numbers. The general procedure is as follows:

1. Calculate `x = Rnd[37] + 1` (in *Hellfire*, calculate `x = Rnd[52] + 1`).
2. Start with the first spell in the internal list of spells.
3. Step forward until a spell that exists on staves (or books, if selecting for a book) and has a sufficiently low `ilvl` is found.  
   - If the end of the list is reached, restart from the beginning.
4. Decrease `x` by one.
5. If `x` is not `0`, return to step **3**.
6. The last spell found in step **3** is the one chosen to appear on the staff (or book).


- In single player, the spells Heal Other and Resurrect are automatically skipped and do not count even if their ilvl is high enough.
- Spells at the start of the list will have a higher probability than those later in the list. The exact cut off depends on the ilvl. This means that there will be two different levels of probabilities for the spells, a higher one for spells at the start of the list and a lower one for spells at the end of the list. At rare occasions all spells will have the same probability.
- The order of the spells is *not* the same as in your spell book or any of the other lists in this Guide. The table below lists the order of the spells for the purpose of selecting a spell for a staff or a book.

| **Position<sup>[^1]</sup>** | **Spell**        | **Book** | **Staff** |
|------------:|----------------|:-------:|:-------:|
| 1  | Firebolt        | Yes | Yes |
| 2  | Healing        | Yes | Yes |
| 3  | Lightning      | Yes | Yes |
| 4  | Flash          | Yes | Yes |
| 5  | Fire Wall      | Yes | Yes |
| 6  | Town Portal    | Yes | Yes |
| 7  | Stone Curse    | Yes | Yes |
| 8  | Phasing        | Yes | Yes |
| 9  | Mana Shield    | Yes | Yes |
| 10 | Fireball       | Yes | Yes |
| 11 | Guardian       | Yes | Yes |
| 12 | Chain Lightning | Yes | Yes |
| 13 | Flame Wave     | Yes | Yes |
| 14 | Nova          | Yes<sup>[^2]</sup> | Yes |
| 15 | Golem         | Yes | Yes |
| 16 | Teleport      | Yes | Yes |
| 17 | Apocalypse    | Yes<sup>[^2]</sup> | Yes |
| 18 | Elemental     | Yes | Yes |
| 19 | Charged Bolt     | Yes | Yes |
| 20 | Holy Bolt       | Yes | Yes |
| 21 | Resurrection<sup>[^3]</sup> | - | Yes |
| 22 | Telekinesis     | Yes | Yes |
| 23 | Heal Other<sup>[^3]</sup> | Yes | Yes |
| 24 | Blood Star      | Yes | Yes |
| 25 | Bone Spirit     | Yes | Yes |
| 26 | Mana            | - | Yes |
| 27 | Magi            | - | Yes |
| 28 | Jester          | - | Yes |
| 29 | Lightning Wall  | Yes | Yes |
| 30 | Immolation      | Yes | Yes |
| 31 | Warp            | Yes | Yes |
| 32 | Reflect         | Yes | Yes |
| 33 | Berserk         | Yes | Yes |
| 34 | Ring of Fire    | Yes | Yes |
| 35 | Search          | Yes | Yes |

[^1]: **Positions 26 to 35 only exist in *Hellfire*.**  
[^2]: **Only exists as books in *Hellfire*.**  
[^3]: **In *single player*, "Heal Other" and "Resurrect" are automatically skipped and do not count, even if the `ilvl` is high enough.**  


**Book**

If the item type is a *book of,* the game then attaches a spell to the book. The qlvl of the spell can be in the range given below. For a list of qlvl of spells on books see chapter 3.2.3.

Range of qlvl for spell on books:	`1 to ilvl/2`

- Note that the qlvl of a spell is different depending on whether it appears on a book or on a staff. For information about how the spell is chosen, see above under Staff.

**Oil**

Oils can, as noted in chapter 3.2.1, be of two types; either the oil together with its type is treated as a base item, just like a potion and thus no further processing of the oil is needed, or it can be created as the base item *oil of*, to which an oil type is then attached. See chapter 3.2.1 for more information on which oils can be created in which way. If the case is the latter one, the oil type attached to the oil follows the range below:

Range of qlvl for oil type:	`1 to ilvl`


### **Special Item Probabilities**

A *special item* can only be one of a limited set of base items. In *Diablo*, the table below lists the possible base items and their probabilities.

#### **Diablo Special Item Probabilities**
| **Item**               | **Probability** |
|-----------------------|---------------:|
| Scroll of Town Portal | 33.3% |
| Potion of Healing    | 33.3% |
| Potion of Mana       | 33.3% |

---

#### **Hellfire Special Item Probabilities**
In *Hellfire*, the probabilities vary based on dungeon level (`dlvl`).

##### **For `dlvl = 1`**
| **Item**          | **Probability** |
|------------------|---------------:|
| Potion of Healing | 42.9% |
| Potion of Mana    | 42.9% |
| Blacksmith Oil    | 14.3% |

##### **For `dlvl > 1`**
| **Item**               | **Probability** |
|-----------------------|---------------:|
| Scroll of Town Portal | 28.6% |
| Potion of Healing    | 28.6% |
| Potion of Mana       | 28.6% |
| Blacksmith Oil       | 14.3% |


## 3.9 Item creation in town

For many parts, the creation of items in town is the same as that in the dungeon, but there are several differences and they are explained in this chapter. In the table below are listed what type of items you can buy from each person in town.

### **NPC Vendors and Items Sold**<sup>[^1]</sup>

| **Person**  | **Items Sold** |
|------------|---------------------------------------------------------------|
| **Adria**  | Staves<sup>[^2]</sup>, books, scrolls, mana potions, rejuvenation potions, and elixirs<sup>[^3]</sup> |
| **Griswold** | Weapons (excluding staves<sup>[^4]</sup>), armor, helms, shields, and jewelry<sup>[^5]</sup> |
| **Pepin** | Healing potions, rejuvenation potions, Scroll of Resurrect, Scroll of Healing, and elixirs<sup>[^3][^5]</sup> |
| **Wirt**<sup>[^6]</sup> | Weapons (excluding staves<sup>[^4]</sup>), armor, helms, shields, and jewelry<sup>[^5]</sup> |

---

[^1]: Only *Griswold* and *Adria* will buy items.  
[^2]: In *Hellfire*, only staves *with spells* are sold.  
[^3]: Available once you reach level 26 in *multiplayer*, or after visiting *Hell*, *Crypt*, or *Hive* in *single player*.  
[^4]: In *Hellfire*, *Griswold* does sell staves.  
[^5]: Only available in *single player*.  
[^6]: For *special exceptions* regarding *Wirt*, see **chapter 3.9.4**.  

Just as for item creation in the dungeon we start by defining the ilvl for each person that you can shop from in town.

It is done in the table below.

| **Source of Item**        | **Definition of `ilvl`** |
|--------------------------|-------------------------|
| **Adria**                | `special`<sup>[^1]</sup> |
| **Griswold (basic items)**  | `special`<sup>[^1]</sup> |
| **Griswold (premium items)** | Varies from `clvl - 1` to `clvl + 2`<sup>[^2]</sup> |
| **Pepin**                | `special`<sup>[^1]</sup> |
| **Wirt**                 | `clvl` |

[^1]: See the table below for how `clvl` is converted to `ilvl` in *special cases*.  
[^2]: Maximum `ilvl` is **30** in all cases. In *Hellfire*, it varies from `clvl - 1` to `clvl + 3`. See the table below for exact variation.  


As noted in the table above, ilvl is in many cases derived in a special way; the table below explains how it is derived for Adria’s, Pepin’s and Griswold’s basic items. In multi player it depends on your character level. In single player it depends on what dungeon level you have been to in the current game. Difficulty does not affect it in any way.

**Definition of ilvl at Adria, Pepin and for Griswold’s basic items**

| **Single Player** | **Multi Player** |          |
|------------------|-----------------|------------|
| **`dlvl`**      | **`clvl`**       | **`ilvl`** |
| 1 - 4          | 1 - 9            | 6          |
| 5              | 10 - 11          | 7          |
| 6              | 12 - 13          | 8          |
| 7              | 14 - 15          | 9          |
| 8              | 16 - 17          | 10         |
| 9              | 18 - 19          | 11         |
| 10             | 20 - 21          | 12         |
| 11             | 22 - 23          | 13         |
| 12             | 24 - 25          | 14         |
| 13             | 26 - 27          | 15         |
| 14 - 16        | 28 - 50          | 16         |
| **Hive / Crypt**<sup>[^1]</sup> |                     | 16         |

[^1]: **Only available in *Hellfire*.**

For Griswold’s premium items the ilvl varies depending on what slot the items is created in (in his list of items). The table below explains exactly how.

#### Definition of `ilvl` for Griswold’s Premium Items

|                 | **Diablo** | **Hellfire** |
|---------------|------------|-------------|
| **Slot**<sup>[^1]</sup>  | **`ilvl`**   | **`ilvl`**  |
| 1             | `clvl - 1`  | `clvl - 1`  |
| 2             | `clvl - 1`  | `clvl - 1`  |
| 3             | `clvl`      | `clvl - 1`  |
| 4             | `clvl`      | `clvl`      |
| 5             | `clvl + 1`  | `clvl`      |
| 6             | `clvl + 2`  | `clvl`      |
| 7             | -           | `clvl`      |
| 8             | -           | `clvl + 1`  |
| 9             | -           | `clvl + 1`  |
| 10            | -           | `clvl + 1`  |
| 11            | -           | `clvl + 1`  |
| 12            | -           | `clvl + 2`  |
| 13            | -           | `clvl + 2`  |
| 14            | -           | `clvl + 3`  |
| 15            | -           | `clvl + 3`  |

[^1]: **There are only six slots in *Diablo*.**

When you gain a level, the items in slot 1 and 2 (and 3 in Hellfire) are removed and items are pushed upwards so that slot 4 and 6 becomes empty (slot 11, 13 and 15 in Hellfire). Those empty slots are then refilled with new items of the appropriate ilvl matching the slot.

It is worth noticing that even if two characters are the same level they will be offered different items in town even if they are in the same game. Thus, it can be rewarding to ask others to check for any item you might want if you are playing multi player.


### 3.9.1 Adria

Adria has an unlimited supply of Potions of Mana, Potions of Full Mana and scrolls of Town Portal. In addition to those, Adria offers 7 to 14 random base items with a qlvl in the range below. She will renew her inventory each time you come back up from the dungeons or reload the game in single player.

Range of qlvl for base item:	1 to ilvl

The prefix, suffix and spell on the appropriate item is then chosen according to the ranges below:

Range of qlvl for spell (staff or book):	1 to ilvl

Range of qlvl for prefix on staff with spell:	1 to 2×ilvl

Range of qlvl for prefix and suffix on staff without spell:	ilvl to 2×ilvl

As the ilvl at Adria can never be higher than 16 (see table in chapter 3.9), there is a cap at qlvl 32 for prefixes and suffixes at Adria. For spells and base items the cap is at 16.


### 3.9.2 Griswold

Griswold has two types of items: basic ones that are not magical, and premier ones that are always magic.


**Basic items**

For the basic items he offers 10 to 19 random items with a qlvl in the range below.

Range of qlvl for base item:	1 to ilvl

As with items from normal monsters, bows has a double chance of being selected. He will renew his inventory of basic items each time you come back up from the dungeons or reload the game in single player.


**Premier items**

For the premier items, Griswold sells base items with a qlvl that follow the range listed below. He will offer 6 items in Diablo and 15 items in Hellfire. The qlvl of the prefix and suffix of magical items also follows the same range.

Range of qlvl for base item:	ilvl/4 to ilvl

Range of qlvl for prefixes and suffixes:	ilvl/2 to ilvl

- Maximum level of prefixes and suffixes at Griswold is 30.

- As already described, the ilvl varies a bit from item to item.

- Griswold will add a new item to his inventory as soon as you buy one of them. He will not change his inventory when you come back up from the dungeons but will change some of them when you gain a level.

- The exact procedure of choosing item type and prefixes and suffixes are the same as for magical items in the dungeon. See chapter 3.8 for more information.

In Hellfire there is an additional factor to consider. If possible he will try to sell items that are better (more expensive than 80% of your most expensive item) than the ones you are already carrying (both equipped ones and not equipped ones). The test is done separately for each item type group (amulet, armor, axe, bow, club, helm, ring, shield, staff and sword). If you don’t have any item of a type, any other item of that type is considered to be better. Thus to get progressively better items you should keep the most expensive item of each item type in your inventory. This check for better items is also done for items that are created to fill up a slot after you have leveled or bought one of his items. Also note that this works in Hellfire only. Sometimes you will see an item ”violating” this rule in Hellfire, as the game only tries a specific number of times, and if it has not found an item that matches in those tries it sticks with whatever item it generates next.


### 3.9.3 Pepin

Pepin has unlimited supply of Potions of Healing, Potions of Full Healing and scrolls of Resurrect (in multi player only). In addition to those, Pepin offers 7 to 14 random base items with a qlvl in the range below. He will renew his inventory each time you come back up from the dungeons or reload the game in single player.

Range of qlvl for base item:	1 to ilvl


### 3.9.4 Wirt

Wirt will only offer one item for sale and you have to pay 50 gold just to see it. The maximum qlvl of prefixes and suffixes is 60, which means he could theoretically sell any type of item otherwise possible in the game (of the types listed in the table in chapter 3.9) if it were not for the price limit (see chapter 3.10). He offers items whose base item has a qlvl in the range below.

Range of qlvl for base item:	1 to ilvl

The prefixes and suffixes are then chosen with a qlvl in the following range:

Range of qlvl for prefixes and suffixes:	ilvl to 2×ilvl

- If lower limit is higher than 25, it is set to 25.

- He seems to love items *of ages*. The reason for this is that there are not many suffixes of level 25 or above and most of them can exist on a very limited number of items or would make items too expensive.

He will renew the item only if you have bought the previous one and then gone into the dungeons or when you gain a new character level that is even.

In Hellfire, Wirt will only sell certain item types to you depending on your character class. The table below summarizes what items he will sell to each character class. Wirt will, in Hellfire, also try to offer you better (more expensive than 80% of your most expensive item) items than what you already have (both equipped ones and not equipped ones).

### Items Never Sold at Wirt in *Hellfire* by Class

| **Class**    | **Items Never Sold** |
|-------------|----------------------|
| **Warrior**  | Bows, Staves         |
| **Rogue**    | Axes, Clubs, Swords, Staves, Shields |
| **Sorcerer** | Axes, Clubs, Bows, Staves |
| **Monk**     | Clubs, Bows, Shields, Medium Armor<sup>[^1]</sup> |
| **Bard**     | Axes, Clubs, Staves  |
| **Barbarian**| Bows, Staves         |

[^1]: See **Chapter 3.1** for the definition of *Medium Armor*.


## 3.10 General remarks on possible items

As can be seen in the wealth of information about items, finding out what items are really possible can be hard. In this chapter I will try to explain some simple ways of finding out if that particular item you are looking for can really be found or bought. Let’s go through what affects what items can really be found or bought in the game. Mostly the discussion will be about prefixes and suffixes.


**Occurrence of prefix and suffix**

Most prefixes and suffixes can only exist on certain base items. This information can be found in chapter 3.3 and in summary in chapter 3.13.6. A quick look can rule out the possibility of an item like an emerald ring. As the base item is determined by the modified for difficulty mlvl, there should be no restrictions on what base item a prefix or suffix can occur on within a certain item type. That is, if it can occur on a dagger, it can also occur on a bastard sword. An exception to this is Griswold’s premium items that have a lower limit of ilvl/4 for the qlvl on base items.


**qlvl of prefix and suffix**

Just because both a prefix and a suffix can exist on a base item does not mean you can find them both on the same item. As explained in chapter 3.8, the qlvl of a prefix and a suffix must be in the range of:

ilvl/2 - ilvl:	for non Wirt and Adria items, including items form the dungeons

ilvl - 2×ilvl:	for Wirt and Adria items

Items from Adria only follow Wirt if they are staves without spells. From this it follows that the prefix or suffix with the lowest qlvl on an item can never be higher than half (rounded down except for Wirt and some Adria items) the qlvl of the higher one (the other way around the higher level can never be higher than 2 times the lower one, plus one if odd, (except for Wirt and some Adria items) the plus one due to rounding effects if the item does not come from Wirt or Adria). As noted in the same chapter the exception for this is that if the highest limit of the qlvl is higher than 50 the lower limit is always 25. This rule can quickly rule out an item like obsidian shield of brilliance as impossible as the qlvl of the prefix and suffix is 24 and 11. This only has importance if an item has both a prefix and a suffix.

There are no restrictions on the relationship between the qlvl of the base item and the qlvl of any additional attributes of the item such as prefixes, suffixes, spells and uniques. Thus, a godly cap of the whale is a completely valid item (you will only be able to buy it at Wirt though).


**Restrictions in the dungeon**

As explained in chapter 3.8, prefixes and suffixes are assigned to items based on a monsters unmodified mlvl. This means that no prefix or suffix with a qlvl higher than 30 (34 when a unique monster drops it as they have a +4 bonus) can be found in the dungeons, except from Diablo and Na-Krul in Hellfire, which have a maximum limit of 45 and 44. This rules out quite a few of the best prefixes and suffixes such as a godly plate of whale, even if they would be possible according to what was said above under occurrences and level differences. Similarly, items from non monsters have a limit of 30 in Diablo and 34 in Hellfire (2×dlvl). Note, this is true for any version of Diablo, even 1.00. Wirt (but not Griswold) can still sell those prefixes and suffixes impossible to find in the dungeons.


**Restrictions at Griswold and Adria**

The same restriction mentioned above for the dungeon also applies to Griswold and Adria. They will never sell you any item with a prefix or suffix with a qlvl higher than 30 (32 at Adria). This again rules out the best prefixes and suffixes even if they would be possible according to what was said above under occurrences and qlvl differences.


**Restrictions on the price**

Even if an item would be possible according to anything that has been said above, when the item is sold in town it cannot be more expensive than the price maximum. This maximum is 140 000 (90 000 at Wirt) gold in Diablo and 200 000 gold in Hellfire (150 000 gold in version 1.00 of Hellfire). Any item more expensive than that will never be sold. This will also rule out several items such as a merciless long war bow of heavens or an awesome full plate of the lion, especially at Wirt who could otherwise have sold any item that met the occurrence and level requirements explained above. Note that the price of items at Wirt is capped *before* they are modified by 150% in Diablo and 75% in Hellfire. This makes the effective cap at Wirt to be 135 000 in Diablo and 150 000 in Hellfire (112 500 in version 1.00 of Hellfire). This makes some items that are not available in Diablo available in Hellfire. On rare occasions it seems that the price, at least in Hellfire, can be slightly higher than the cap.


**Other restrictions**

Just a few other words on what is possible and not. A unique item can only be of the base item listed in chapter 3.5.

A Dreamflange can, for example, only be a mace and, nothing else.

The difficulty you play on only affects the base item, but as a consequence of this some unique items are only findable on specific difficulties as both the qlvl of the base item and the qlvl of the unique item have to be fulfilled for a monster to drop it. An example of this is the Helm of Sprits, which can only be found in nightmare and hell difficulty. I leave it as an exercise to the reader to figure out why!

As the highest qlvl of a base item is 25, any monster with an mlvl equal to that or above can drop the same items regardless of difficulty. This is true for almost all monsters in hell and the Crypt. Thus item drops in hell and the Crypt should be the same regardless of difficulty. For other dungeons you will find better base items in harder difficulty levels, but it should not affect what prefixes and suffixes you find.


**What affects item creation**

As can be seen from the information in chapter 3, the only things that affect what items one can find in the dungeon and can buy in town are the mlvl and dlvl in dungeons and the clvl (or dlvl visited in single player) in town. Thus, item creation is not affected by anything else. There is *no* influence caused by what you are carrying (except in Hellfire for Griswold’s and Wirt’s items), your character class, what items you use, who created the game, or other similar things. The only thing that will affect the creation is the initial seed used by the game in generating random numbers, and in both Diablo and Hellfire, the initial seed is generated out of the time when the game is created (and for items in town, the time when you shop; this is to avoid the chance that all players in the game see the same items, as they would then be treated by the game as duplicates).



## 3.11 Probabilities of finding unique items

As with all other items in the game with the exception of quest related items, which only exists in single player, unique items are created randomly by the game. In the table below are shown the rarity of all the unique items. The values have been calculated taking into account all the relevant information and formulas found in this Guide as well as all of the following:

- You would have to kill all monsters, break all barrels, open all chests and so on.

- Each monster is modeled with the probabilities found in chapter 5.3.2.

- There are assumed to exist 185 monsters on all levels with the exception of level 1 and 2 that are a bit smaller and thus has a somewhat less monsters.

- On appropriate levels, the following number of item sources have been assumed (usually the average number of them on each level): 7 small chests, 4 chests, 2.5 large chests, 5 patches of 6 barrels, 14.5 sarcophagus and 3.5 decapitated bodies. For the calculations it does not matter if the numbers are decimals instead of integers.

- For various reasons, mostly due to the difficulties in making good estimates of the frequencies, no considerations have been made to those items sometimes appearing directly on the ground or appearing on weapon or armor racks. This should not affect the final probabilities much though. If anyone has any more information on the frequencies of them, please feel free to tell me.

- The values are only valid for multi player. In single player some quest monsters will drop a quest item instead of a random magical item. Also, dungeon levels normally has less monsters than in single player. Finally, unique items are picked slightly different in single player than multi player meaning some of the unique items marked as Impossible ones, actually has a very small chance of appearing in a single player game (but very small, typically square the number for the uniques being second in the order and raise it to the power of three for the third one in the list. For the drop order of such unique items, see chapter 3.5.2. It is my belief that the values should be more or less accurate for single player as well though.

The value given is an estimate of how many games it takes on average to find a specific unique. To find the probability of a specific unique to exist in a game, simply divide 1 by the number given. Given are also numbers telling on what dlvl the unique item has the highest overall chance (includes all sources) to be found. It is very important to realize that the number given here are necessarily *not* the same as the typical player will find. A typical player will for example not play in all areas equally much. Also, even though the chances are over all greater for monsters than for unique monsters, you need to kill a lot more of them. So if you are hunting for specific unique items, it is normally a much faster method to kill, say only bosses on level 13-15 than killing all monsters on the same levels. Never the less, the numbers below should give a rough estimate on how rare or common a specific unique item is. If an item is impossible to generate for some reason, it will say ”impossible”.

## 3.12 Probabilities of finding magical items

It would of course be possible to do similar tables for magical items, as for unique items. However, due to the almost infinite number of possible magical items as well as severe problems to do any probabilities for such items that are sold in town (especially in Hellfire), it is my decision to not have any such information in this guide.


## 3.13 Summary of various item properties

This chapter summarizes various properties of items and lets you review them without being confused by other non related properties. All data below can of course be found in the complete tables in chapter 3.1 - 3.5. To make it as convenient as possible, I have tried to have each summary on its own page or opening.


### 3.13.1 Levels of base items

Below is a list of all the base items in the game. It has been divided into two different tables: equipable items (excluding jewelry) and other items. The items are sorted by their qlvl.

**Armor and Weapons**

||**Item**|**qlvl**|**Item**|**qlvl**|**Item**|**qlvl**||
| :- | :- | :-: | :- | :- | :- | :-: | :- |
||Buckler|1|Spiked Club|4|Ring Mail|11||
||Cap|1|Claymore|5|Full Helm|12||
||Cape|1|Long Bow|5|Great Axe|12||
||Club|1|Small Shield|5|War Staff|12||
||Dagger|1|War Hammer|5|Chain Mail|13||
||Rags|1|Composite Staff|6|Kite Shield|14||
||Sable|1|Large Axe|6|Two-Handed Sword|14||
||Short Bow|1|Leather Armor|6|Scale Mail|15||
||Short Staff|1|Long Sword|6|Short War Bow|15||
||Short Sword|1|Composite Bow|7|Breast Plate|16||
||Cloak|2|Flail|7|Crown|16||
||Falchion|2|Hard Leather Armor|7|Great Sword|17||
||Mace|2|Broad Axe|8|Splint Mail|17||
||Small Axe|2|Broad Sword|8|Long War Bow|19||
||Hunter’s Bow|3|Helm|8|Plate Mail|19||
||Morning Star|3|Large Shield|9|Great Helm|20||
||Robe|3|Quarter Staff|9|Tower Shield|20||
||Axe|4|Short Battle Bow|9|Field Plate|21||
||Blade|4|Studded Leather Armor|9|Gothic Plate|23||
||Long Staff|4|Bastard Sword|10|Gothic Shield|23||
||Quilted Armor|4|Battle Axe|10|Full Plate Mail|25||
||Scimitar|4|Maul|10||||
||Skull Cap|4|Long Battle Bow|11||||
|||||||||
||**Other base items**|||||||
||**Item**|**qlvl**|**Item**|**qlvl**|**Item**|**qlvl**||
||Blacksmith Oil1|1|Rune if Lightning1|4|Scroll of Golem|10||
||Oil of Accuracy1|1|Scroll of Town Portal|4|Scroll of Chain Lightning|10||
||Oil of Sharpness1|1|Ring|5|Scroll of Flame Wave|10||
||Potion of Full Healing|1|Scroll of Flash|6|Scroll of Guardian|12||
||Potion if Full Mana|1|Scroll of Stone Curse|6|Book of|14||
||Potion of Healing|1|Scroll of Phasing|6|Scroll of Nova|14||
||Potion of Mana|1|Greater Rune of Fire1|7|Scroll of Teleport|14||
||Rune of Fire1|1|Greater Rune of Lightning1|7|Elixir of Dexterity|15||
||Scroll of Healing|1|Potion of Full Rejuvenation|7|Elixir of Magic|15||
||Scroll of Identify|1|Rune of Stone1|7|Elixir of Strength|15||
||Scroll of Inferno|1|Amulet|8|Ring|15||
||Scroll of Resurrect|1|Book of|8|Amulet|16||
||Book of|2|Scroll of Fireball|8|Book of|20||
||Potion of Rejuvenation|3|Scroll of Infravision|8|Elixir of Vitality|20||
||Scroll of Lightning|3|Scroll of Mana Shield|8|Scroll of Apocalypse|22||
||Scroll of Search1|3|Oil of1|10||||
||Scroll of Fire Wall|4|Ring|10||||
1	Only available in Hellfire.


### 3.13.2 Levels of spells on books and staves

When spells are attached to books and staves (they never exist on scrolls as each scroll is a separate base item), they also have a qlvl, and that differs between books and staves. Below are listed the qlvl for both types sorted in qlvl order.

|**On books**||**On books**||**On staves**||**On staves**||
| :- | :- | :- | :- | :- | :- | :- | :- |
|**Spell**|**qlvl**|**Spell**|**qlvl**|**Spell**|**qlvl**|**Spell**|**qlvl**|
|Charged Bolt|1|Ring of Fire1|5|Charged Bolt|1|Mana Shield|5|
|Fire Bolt|1|Mana Shield|6|Fire Bolt|1|Resurrect|5|
|Healing|1|Stone Curse|6|Healing|1|Ring of Fire1|5|
|Heal Other|1|Phasing|7|Heal Other|1|Stone Curse|5|
|Holy Bolt|1|Chain Lightning|8|Holy Bolt|1|Elemental|6|
|Search1|1|Elemental|8|Inferno|1|Phasing|6|
|Telekinesis|2|Fireball|8|Fire Wall|2|Chain Lightning|7|
|Fire Wall|3|Bone Spirit|9|Lightning Wall1|2|Fireball|7|
|Inferno|3|Flame Wave|9|Telekinesis|2|Bone Spirit|7|
|Town Portal|3|Guardian|9|Berserk1|3|Flame Wave|8|
|Berserk1|3|Golem|11|Reflect1|3|Guardian|8|
|Lightning Wall1|3|Blood Star|14|Warp1|3|Golem|9|
|Reflect1|3|Immolation1|14|Lightning|3|Immolation1|10|
|Warp1|3|Nova1|14|Search1|3|Nova|10|
|Lightning|4|Teleport|14|Town Portal|3|Teleport|12|
|Flash|5|Apocalypse1|19|Flash|4|Blood Star|13|
|||||Jester1|4|Apocalypse|15|
|||||Mana1|5|Magi1|20|

1	Only available in Hellfire.


### 3.13.3 Levels of prefixes and suffixes

The tables below list all prefixes and suffixes according to their qlvl. All the prefixes are found in one table while all the suffixes are found in another table.

||**Prefix**|**qlvl**|**Prefix**|**qlvl**|**Prefix**|**qlvl**|**Prefix**|**qlvl**|**Prefix**|**qlvl**|
| :- | :- | :-: | :- | :- | :- | :- | :- | :-: | :- | :-: |
||brass|1|red|4|crimson|10|lightning|18|dragon’s|27|
||bronze|1|white|4|pearl|10|blessed|19|awesome|28|
||dull|1|clumsy|5|valiant|10|lord’s|19|king’s|28|
||fine|1|crystalline1|5|Warrior’s|10|cobalt|20|master’s|28|
||frog’s|1|raven’s|5|doppelgang.1|11|crystal|20|emerald|31|
||rusted|1|useless|5|amber|12|garnet|20|holy|35|
||sharp|1|deadly|6|gold|12|massive|20|ruthless|35|
||spider’s|1|fine|6|vicious|12|mithril|20|weird|35|
||weak|1|grand|6|glorious|14|drake’s|21|wyrm’s1|35|
||bent|3|steel|6|angel’s|15|knight’s|23|champion’s|40|
||strong|3|flaming|7|serpent’s|15|meteoric|23|godly|60|
||tin|3|jester’s1|7|soldier’s|15|savage|23|hydra’s1|60|
||vulnerable|3|topaz|8|brutal|16|obsidian|24|merciless|60|
||blue|4|bountiful|9|crimson|16|saintly|24|strange|60|
||hyena’s|4|heavy|9|ivory|16|arch-angel’s|25|||
||iron|4|silver|9|lapis|16|diamond|26|||
||jagged|4|snake’s|9|platinum|16|ruby|26|||
||plentiful|4|azure|10|jade|18|sapphire|26|||
||1  Only available in Hellfire.||||||||||
||||||||||||
||**Suffix**|**qlvl**|**Suffix**|**qlvl**|**Suffix**|**qlvl**|**Suffix**|**qlvl**|**Suffix**|**qlvl**|
||atrophy|1|quality|2|skill|5|thieves|11|the tiger|21|
||balance|1|tears|2|zest|5|vim|11|life|23|
||brittleness|1|the fool|3|the sky|5|absorption|12|perfection|23|
||decay1|1|fragility|3|craftman.|6|structure|12|titans|23|
||dexterity|1|frailty|3|the dark|6|trouble|12|wizardry|23|
||devastation1|1|illness|3|protection|6|shock|13|the ages|25|
||disease|1|many|3|maiming|7|slaying|15|gore|25|
||dyslexia|1|the night|3|plenty|7|the wolf|15|the heavens|25|
||flame|1|paralysis|3|the bat|8|the stars|17|haste|27|
||the fox|1|light|4|the leech|8|vigor|17|the lion|27|
||the jackal|1|pain|4|radiance|8|bashing|17|the zodiac|30|
||magic|1|the vulture|4|the eagle|9|giants|17|burning|35|
||piercing|1|the bear|5|puncturing|9|precision|17|carnage|35|
||readiness|1|blocking|5|stability|10|sorcery|17|the mammoth|35|
||strength|1|corruption|5|swiftness|10|blood|19|osmosis|50|
||sturdiness|1|the jaguar|5|accuracy|11|speed|19|slaughter|60|
||thorns|1|might|5|brilliance|11|vampires|19|thunder|60|
||vitality|1|the mind|5|fire|11|deflection|20|the whale|60|
||weakness|1|peril1|5|the moon|11|harmony|20|||
||health|2|the pit|5|power|11|lightning|21|||
1	Only available in Hellfire.


### 3.13.4 Levels of unique items

The table below lists all unique items according to their qlvl. As quest items are only dropped in special occasions during the quests, they have no qlvl. I have listed them in a separate table below.

||**Unique Item**|**qlvl**|**Unique Item**|**qlvl**|**Unique Item**|**qlvl**|
| :- | :- | :-: | :- | :- | :- | :-: |
||Black Razor|1|The Blackoak Bow|5|Bone Chain Armor1|13|
||Bramble|1|Bow of the Dead|5|Fleshstinger|13|
||Civerb’s Cudgel|1|Constricting Ring|5|Lightsabre|13|
||Crackrust|1|Wicked Axe|5|Scavenger Carapace|13|
||The Defender|1|Wisdom’s Wrap|5|Thunderclap1|13|
||The Deflector|1|The Bonesaw|6|Thundercall|14|
||Gonnagal’s Dirk|1|Gladiator’s Bane|6|The Falcon’s Talon|15|
||Gryphons Claw|1|Thinking Cap|6|Gnat Sting1|15|
||Hammer of Jholm|1|Overlords Helm|7|Hellslayer|15|
||Helm of Sprits|1|Stonecleaver|7|Nightscape|16|
||Lightforge|1|Giant’s Knuckle1|8|The Protector|16|
||The Rift Bow|1|Gleamsong|8|Schaefer’s Hammer|16|
||Ring of Regha|1|Karik’s Ring1|8|Diamondedge1|17|
||Split Skull Shield|1|Mercurial Ring1|8|Inferno|17|
||The Bleeder|2|Ring of Magma1|8|Windforce|17|
||The Celestial Bow|2|Shadowhawk|8|Naj’s Puzzler|18|
||The Celestial Star|2|Storm Spire|8|Doombringer|19|
||Dragon’s Breach|2|Ring of the Mystics1|8|Naj’s Light Plate|19|
||Gibbous Moon|2|Ring of Thunder1|8|Mindcry|20|
||The Mangler|2|Xorine’s Ring1|8|Gotterdamerung|21|
||The Needler|2|Gnarled Root|9|Shirotachi1|21|
||The Rainbow Cloak|2|Sparkling Mail|9|Rod of Onan|22|
||Sharp Beak|2|Acolytes Amulet1|10|Eater of Souls1|23|
||Staff of Shadows|2|Flamedart|10|The Grizzly|23|
||Thorn Flesh of Souls|2|Gladiators Rings1|10|Stormshield|24|
||Bloodslayer|3|Holy Defender|10|Armor of Gloom1|25|
||Deadly Hunter|3|Ring of Engagement|11|Demon Plate Armor1|25|
||The Executioner’s Blade|3|Flambeau1|11|Demonspike Coat|25|
||Ice Shank|3|Wizardspike|11|Messerschmidt’s Reaver|25|
||Blackoak Shield|4|Aguinara’s Hatchet|12|Dreamflange|26|
||The Celestial Axe|4|Amulet of Warding1|12|Eaglehorn|26|
||Immolator|4|The Cranium Basher|12|The Grandfather|27|
||Leather of Aut|4|Fool’s Crest|12|Royal Circlet|27|
||Baranar’s Star|5|Blitzen1|13|||
||1  Only available in Hellfire.||||||
||||||||
||**Unique Item**|**qlvl**|**Unique Item**|**qlvl**|**Unique Item**|**qlvl**|
||Arkaine’s Valor|n/a|Empyrean Band|n/a|Ring of Truth|n/a|
||Auric Amulet1|n/a|Griswold’s Edge|n/a|The Undead Crown|n/a|
||Bovine Plate1|n/a|Harlequin Crest|n/a|Veil of Steel|n/a|
||The Butcher’s Cleaver|n/a|Optic Amulet|n/a|||
1	Only available in Hellfire.


### 3.13.5 Effects of prefixes and suffixes

The tables below are extracted from the more comprehensive ones above and summarize the effects of each prefix and suffix.

|**+ Strength**||**+ Magic**||**+ Dexterity**||**+ Vitality**||**+ All Attributes**||||||||||||
| :- | :- | :- | :- | :-: | :- | :-: | :- | :-: | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|frailty|-10 -|-6|the fool|-10 -|-6|paralysis|-10 -|-6|illness|-10 -|-6|trouble|-10 -|-6||||||
|weakness|-5- -1|dyslexia|-5- -1|atrophy|-5 -|-1|disease|-5- -1|the pit|-5- -1||||||||||
|strength|1 -|5|magic|1|-|5|dexterity|1 -|5|vitality|1|-|5|the sky|1 -|3||||
|might|6 -|10|the mind|6|-|10|skill|6 -|10|zest|6|-|10|the moon|4 -|7||||
|power|11 -|15|brilliance|11|-|15|accuracy|11 -|15|vim|11|-|15|the stars|8 -|11||||
|giants|16 -|20|sorcery|16|-|20|precision|16 -|20|vigor|16|-|20|the heavens 12 -|15|||||
|titans|21 -|30|wizardry|21|-|30|perfection|21 -|30|life|21|-|30|the zodiac|16 -|20||||
|||||||||||||||||||||
|**+ Life**|||**+ Mana**|||**+ Damage Done**|<b>- Damage Taken<sup>1</sup></b>|<b>% Steal Life<sup>2</sup></b>||||||||||||
|||||corruption||||-all|||||||||the leech|3||
|the vulture -25|- -11|hyena’s|-25|- -11|||||pain|+4- +2|blood|5||||||||
|the jackal|-10|-|-1|frog’s|-10|-|-1|||||tears|||+1|||||
|the fox|10|-|15|spider’s|10||-|15|quality|1|-|2|health|||1||||
|the jaguar|16|-|20|raven’s|15|-|20|maiming|3|-|5|protection|||2|||||
|the eagle|21|-|30|snake’s|21|-|30|slaying|6|-|8|absorption|||3|<b>% Steal Mana<sup>2</sup></b>||||
|the wolf|30|-|40|serpent’s|30||-|40|gore|9|-|12|deflection|||4|the bat|3||
|the tiger|41|-|50|drake’s|41|-|50|carnage|13|-|16|osmosis|5 -|6|vampires|5||||
|the lion|51|-|60|dragon’s|51|-|60|slaughter|17|-|20|||||||||
|the. mam.|61|-|80|wyrm’s3|61|-|80|||||||||||||
|the whale|81|- 100|hydra’s3|81|- 100|||||||||||||||
1. Works for all type of damage, even from spells, but does not work against other players. The damage is reduced before any resistance is applied but after the thieves effect. The damage will never be reduced below 1.

1. The amount is based on damage done even if the monster has less HP left. Note that two items of life stealing, or two items of mana stealing are not cumulative with each other. An item of blood/vampire will take precedence over an item one of the leech/the bat. ). An exception is The Undead Crown which is cumulative with both an item of blood or an item of the leech for a total of 3% to 15.5% or 5% to 17.5% life stealing. The Helm of Sprits, Shadowhawk, and The Eater of Souls are treated as items of blood. The Eater of Souls are treated as an item of vampire. Does not work against players. See chapter 6.1.4 for more information.

1. Only available in Hellfire.

|**+% To Hit / +% Damage Done**|**+% To Hit**||**+% Damage Done**|<b>+% Armor Class<sup>6</sup></b>||||||||||||||||
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|||||||||||||useless|-100|||||||
|clumsy|-10|-|-6 /|-75|- -50|tin|-10|-|-6|bent|-75 - -50|vulnerable-100 - -51||||||||
|dull|-5|-|-1 /|-45|- -25|brass|-5- -1|weak|-45 - -25|rusted|-50|- -25||||||||
|sharp1|1|-|5|/|20|-|35|bronze|1|-|5|jagged|20|-|35|fine|20|-|30|
|fine|6|- 10/|36|-|50|iron|6|-|10|deadly|36|-|50|strong|31|-|40|||
|Warrior’s|11|- 15/|51|-|65|steel|11|-|15|heavy|51|-|65|grand|41|-|55|||
|soldier’s|16|-|20|/|66|-|80|silver|16|-|20|vicious|66|-|80|valiant|56|-|70|
|lord’s|21|- 30/|81|-|95|gold|21|-|30|brutal|81|-|95|glorious|71|-|90|||
|knight’s|31|- 40/|96|- 110|platinum|31|-|40|massive|96|- 110|blessed|91|- 110||||||
|master’s|41|- 50|/|111|- 125|mithril|41|-|60|savage|111|- 125|saintly|111|- 130|||||
|champion’s|51|- 75/|126|- 150|meteoric|61|-|80|ruthless|126|- 150|awesome|131|- 150||||||
|king’s|76|-100 /|151|- 175|weird|81|- 100|merciless|151|- 175|holy|151|- 170|||||||
|doppelganger’s2,3|21|- 30|/|81|-|95|strange|101|- 150|decay2,4|150|- 250|godly|171|- 200|||||
|||||||||||||crystalline2,5|200|- 280||||||
1. Is treated by the game as a cursed item during item creation so you will, for example, not be able to buy it in town.
1. Only available in Hellfire.

1. Has a 5% chance of duplicating any monster hit except Diablo and unique monsters.

1. Bonus decreases by 5% each hit. When reaching -100%, the item is destroyed.

1. Also has from -30 to -70% lower durability.

1. There is a minimum increase of 1 in AC. That is, even if the percentage will give an increase to AC less than one, it will be increased by at least one. Due to a bug, any decrease in AC less than 1 will be transformed into a positive increase by 1.

|<a name="page66"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**|||||**Created by Pedro Faria**||||||||||
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
||||||||||||||||
|<b>+% Resist Magic<sup>1</sup></b>|<b>+% Resist Fire<sup>1</sup></b>|<b>+% Resist Light.<sup>1</sup></b>|<b>+% Resist All<sup>1</sup></b>|**+ Spell Levels**|||||||||||
|white|10 -|20|red|10 -|20|blue|10 -|20|topaz|10 -|15|angel’s|1 lvl||
|pearl|21 -|30|crimson|21 -|30|azure|21 -|30|amber|16 -|20|arch-angel’s|2 lvls||
|ivory|31 -|40|crimson|31 -|40|lapis|31 -|40|jade|21 -|30||||
|crystal|41 -|50|garnet|41 -|50|cobalt|41 -|50|obsidian|31 -|40||||
|diamond|51 -|60|ruby|51 -|60|sapphire|51 -|60|emerald|41 -|50||||
1	Is applied after any effects from thieves and -damage. It can reduce damage below 1.

|<b>+ Fire Damage<sup>1</sup></b>|<b>+ Lightning Damage<sup>1</sup></b>|<b>Damage / Penet. Armor<sup>2</sup></b>|**× Charges**||||||||||
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|flame|1 -|3|shock|1 -|6|piercing|2|- 6 /|254|%|plentiful|2|
|fire|1 -|6|lightning|1 -|10|puncturing|4|-12 /|504|%|bountiful|3|
|flaming3|1 -|10|lightning3|2 -|20|bashing|8|-24 /|754|%|||
|burning|1 -|16|thunder|1 -|20||||||||
1. There are quite a few bugs associated with fire and lightning arrows which make them often deal erroneous damage (way too high or no additional damage at all).

1. In Diablo these suffixes lower the AC of the target by a specific random amount in the range shown in the table. In Hellfire they reduce the AC of the target by a certain percentage shown in the table. It does not work against players. The exact value (in Diablo) is determined at the time of creation of the item and the extra To Hit is never shown on the character screen.

1. A prefix on non bow weapons. All others are suffixes on bows only.

1. Add 12.5 when used by a Barbarian.

|<b>+% Light Radius<sup>1</sup></b>|<b>Weapon Speed<sup>2</sup></b>|<b>Hit Recovery<sup>3</sup></b>|**+% Durability**|||||||
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|the dark|-40|||||fragility|||=1|
|the night|-20|||||brittleness|-26|-|-75|
|light|20|readiness4,5|quick|balance|fast|sturdiness|26|-|75|
|radiance|40|swiftness5|fast|stability|faster|craftsmanship  51|-|100||
|||speed|faster|harmony|fastest|structure|101|-|200|
|||haste6|fastest|||many7|||100|
|||||||plenty7|||200|
|||||||the ages|indestructible|||

1. Also affects the distance at which you activate monsters. A higher value means at a greater distance. There is no additional effect of wearing more than +50% or less than -80% light radius. As a curiosity, the light radius is always one square less in the catacombs and it is always the highest light radius you have had on a level that counts, even if you later lower it.
1. A Bard only benefits from the fastest weapon.

1. A character only benefits from the fastest one, as they are not cumulative. The exception is if you have one of each in which case you will, in Diablo only, receive a further reduction in hit recovery time. See chapter 2.2.1 for more information.

1. Has no effect in Diablo.

1. In Hellfire, it makes the arrows travel faster on bows instead of decreasing the ”swing” speed.

1. Has the same effect as speed despite what is said in the latest Diablo patch (1.07).

1. Suffix for bows only. All others are suffixes for non bow weapons.

|**Other Prefixes/Suffixes**|**Magical Effect**|
| :- | :- |
|the bear2|knocks target back|
|blocking2|fast block|
|thieves1,2,3|absorbs half of trap damage|
|thorns1,2|attacker takes 1-3 damage|
|devastation1,2,4,5,6|5% chance of doing ×3 damage|
|jester’s1,2,4,5,7|each swing do 0-×6 damage9|
|peril1,2,4,6,8|×2 damage to monster, ×1 damage to user|

1. Does not work versus players.
1. These effects are not cumulative if you have them more than once. They are cumulative with other effects though.

1. In Hellfire it also absorbs half arrow and magical damage (magic, fire, lightning and apocalypse) from monster attacks. It is applied before both -damage and resistance.

1. Only available in Hellfire.

1. Damage bonus applies to total damage, not just weapon damage.

1. Does not work on bows.

1. A prefix.

1. Affects total damage versus monsters but only weapon damage and character damage versus user. This damage is modified by any -damage from enemies, though.

1. The game erroneously states it does ×0-5. Average value is ×2. For more details, see chapter 6.2.1. Does not work against Diablo or unique monsters.


### 3.13.6 Occurrence of prefixes and suffixes

The tables below are extracted from the more comprehensive ones above and summarize the occurrences of prefixes and suffixes. The following abbreviations are used:

|A|Armor and Helms||||||t|Staves in Hellfire only|||||||||||
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|S|Shields||||||||B|Bows|||||||||
|W|Weapons (Axes, Clubs and Swords)||||J|Jewelry|||||||||||||
|T|Staves||||||||||||||||||
||||||||||||||||||||
||**+ Strength**|**+ Magic**||**+ Dexterity**|||**+ Vitality**|**+ All Attributes**|||||||||||
|frailty|ASW–BJ|the fool|ASWTBJ||paralysis|ASW–BJ||illness|ASW–BJ|trouble|ASWtBJ||||||||
|weakness|ASWtBJ|dyslexia|ASWTBJ||atrophy||ASWtBJ||disease|ASWtBJ|the pit|ASWtBJ|||||||
|strength|ASWtBJ|magic|ASWTBJ||dexterity|ASWtBJ||vitality|ASWtBJ|the sky|ASWtBJ||||||||
|might|ASW–BJ|the mind|ASWTBJ||skill||ASW–BJ||zest|ASW–BJ|the moon|ASWtBJ|||||||
|power|ASW–BJ|brilliance|ASWTBJ||accuracy|ASW–BJ||vim|ASW–BJ|the stars|A–WtBJ||||||||
|giants|A–W–BJ|sorcery|A–WTBJ||precision|A–W–BJ||vigor|A–W–BJ|the heav.|––W–BJ||||||||
|titans|––W––J|wizardry|–––T–J||perfection ––––BJ||life|–––––J|the zodiac –––––J||||||||||
||||||||||||||||||||
||**+ Life**|**+ Mana**||**+ Damage Done**||**- Damage Taken**|**% Steal Life**||||||||||||
||||corruption ASW–––||||||||||||the leech|––W–––|||
|the vult.|AS–––J|hyena’s|–––T–J|||||||||pain|AS–––J|blood|––W–––||||
|the jackal|AS–––J|frog’s|–––T–J|||||||||tears|AS–––J||||||
|the fox|AS–––J|spider’s|–––T–J||quality||––WtB–||health|AS–––J|||||||||
|the jaguar|AS–––J|raven’s|–––T–J||maiming|––WtB–||protection AS––––|||||||||||
|the eagle|AS–––J|snake’s|–––T–J||slaying||––W–––||absorption AS––––|**% Steal Mana**|||||||||
|the wolf|AS–––J|serpent’s|–––T–J||gore||––W–––||deflection  A–––––|the bat|––W–––||||||||
|the tiger|AS–––J|drake’s|–––T–J||carnage||––W–––||osmosis|A–––––|vampires|––W–––|||||||
|the lion|A––––J|dragon’s|–––T–J||slaughter|––W–––|||||||||||||
|the mam.|A–––––|wyrm’s1|–––t–J||||||||||||||||
|the whale|A–––––|hydra’s1|–––t–J||||||||||||||||
|1  Only available in Hellfire|||||||||||||||||||
||||||||||||||||||||
||**+% To Hit / +% Damage Done**|||**+% To Hit**||||**+% Damage Done**|**+% Armor**||||||||||
|||||||||||||useless|––WtB–||||||
|clumsy||––WTB–||tin|––W–BJ||bent|––WtB–|vulnerable|AS––––|||||||||
|dull||––WTB–||brass|––W–BJ||weak|––WtB–|rusted|AS––––|||||||||
|sharp||––WTB–||bronze|––W–BJ||jagged|––WtB–|fine|AS––––|||||||||
|fine||––WTB–||iron|––W–BJ||deadly|––WtB–|strong|AS––––|||||||||
|Warrior’s||––WTB–||steel|––W–BJ||heavy|––WtB–|grand|AS––––|||||||||
|soldier’s||––WT––||silver|––W–BJ||vicious|––WtB–|valiant|AS––––|||||||||
|lord’s||––WT––||gold|––W–BJ||brutal|––WtB–|glorious|AS––––|||||||||
|knight’s||––WT––||platinum|––W–B–||massive|––WtB–|blessed|AS––––|||||||||
|master’s||––WT––||mithril|––W–B–||savage|––WtB–|saintly|AS––––|||||||||
|champion’s|––WT––||meteoric|––W–B–||ruthless|––WtB–|awesome|AS––––||||||||||
|king’s||––WT––||weird|––W–B–||merciless|––WtB–|holy|AS––––|||||||||
|doppelganger’s1|--Wt--||strange|––W–B–||decay1|--WtB-|godly|AS––––||||||||||
|||||||||||||crystalline1|--W---||||||
|1  Only available in Hellfire|||||||||||||||||||
||||||||||||||||||||
|**+ % Resist Magic**|**+ % Resist Fire**|**+ % Resist Light.**|||**+ % Resist All**||**+ Spell Levels**||||||||||||
|white|ASWTBJ|red|ASWTBJ|blue||ASWTBJ||topaz|ASWTBJ|angel’s|–––T––||||||||
|pearl|ASWTBJ|crimson|ASWTBJ|azure||ASWTBJ||amber|ASWTBJ|arch-angel’s  –––T––|||||||||
|ivory|ASWTBJ|crimson|ASWTBJ|lapis||ASWTBJ||jade|ASWTBJ||||||||||
|crystal|ASWTBJ|garnet|ASWTBJ|cobalt||ASWTBJ||obsidian|ASWTBJ||||||||||
|diamond|ASWTBJ|ruby|ASWTBJ|sapphire||ASWTBJ||emerald|–SWTB–||||||||||

|<a name="page68"></a>**Jarulf’s Guide to Diablo and Hellfire, v1.62**||||||**Created by Pedro Faria**|||||||||
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
||||||||||||||||
|**+ Fire Damage**||**+ Lightning Damage**|**Damage / Penet. Armor**|**× Charges**|||||||||||
|flame|––––B–|shock|––––B–|piercing|––W–B–|plentiful|––––T––||||||||
|fire|––––B–|lightning|––––B–|puncturing|––W–B–|bountiful|––––T––||||||||
|flaming|––WT––|lightning|––WT––|bashing|––W–––||||||||||
|burning|––––B–|thunder|––––B–||||||||||||
||||||||||||||||
|**+% Light Radius**|**Weapon Speed**|||**Hit Recovery**||||**Durability**|||||||
|the dark|A–W––J||||||||||fragility|ASW–––|||
|the night|A–W––J||||||||||brittleness|ASW–––|||
|light|A–W––J|readiness|––WTB–||balance|A––––J||sturdiness|ASW–––||||||
|radiance|A–W––J|swiftness|––WTB–||stability|A––––J||craftsmanship|ASW–––||||||
|||speed||––WT––||harmony|A––––J||structure|ASW–––|||||
|||haste||––WT––|||||||many||––––B–||
||||||||||||plenty||––––B–||
||||||||||||the ages|ASWt––|||
||||||||||||||||
|**Other Prefixes/Suffixes in Diablo**|||**Other Prefixes/Suffixes in Hellfire**||||||||||||
|the bear|––WTB–|||||devastation||--WtB-|||||||
|blocking|–S––––|||||jester’s||--W---|||||||
|thieves|AS–––J|||||peril|||--WtB-||||||
|thorns|AS––––||||||||||||||


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