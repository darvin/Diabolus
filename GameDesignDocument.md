# Preamble

*Deabolus* is the online coop rogue-like game with allowed (and encoraged) bot gameplay, heavily inspired by gameplay of *Diablo 3*

## Description

Gamer controls a character of one of the available classes. Character has stats and talents. In 2d randomly generated worlds gamer uses a different talents, specific to class to kill monsters. Killing monsters grants expirience and loot. Leveling for expirience points grants new talents. Loot includes wearable equipment which grant stats and some unique talents. Purpose of gameplay is to advance characters and improve equipment. There is no cap on advancement.

Player can have multiple characters on one account. Equipment and game currency is shared between characters.

There is in-game shops and ways of crafting and modification of equipment.

Gameplay is realtime. Most of the talents of the characters do some damage to the monsters, some can have special affects, some have area of damage.

Coop mode is multiplayer mode of the game. In coop mode players are clear the dungeons - the same way they do in one-player mode. Drop is not shared, no friendly fire. There are bonuses for participation jn coop party and limit - 4 people per party.

The biggest difference between Diabolus and other games of the genre (most noticable one Diablo 3) is that advancing through levels of character continues while player is offline. One of the player's characters (designated by player), called _spirit_ is being added randomly to the online coop parties with less than 4 players. It is controlled by the  bot script. It fights alongside with players, collects expirience and 1/10 of gold, but no other loot. Personal  bot script is editable by player.

There is a system of Seasons - once per 4 month, players are able to create a fresh, seasonal characters (which has no access to regular's players shared equipment and game currency) and compete with each other in speed of leveling them. After end of the Season, rollover happens: all seasonal characters become regular ones, equipment and game currency of seasonal characters adds to regular ones.






## Engine Specs

### RPG system

#### Characters

##### Stats 

##### Player characters

###### Leveling rules

###### Talents

##### Monsters

###### Affixes




### Level Generation

Procedural generation of levels. 

 - Randomly choose biotop
 - According to biotop, select appropriate archetype
 - Generate level, using assets of biotop, and randomly inserting handmade level pieces of biotop
 - Populate with monsters of appropriate to current character's level
 - Place characters onto designited entrance of the level
 - Create exit from the level in the most far point of the level.


#### Biotop

Biotop is a theme of level. It consists of set of assets of the level, kinds of monsters player can encounter on that level, set of handmade level pieces and link onto archetype. Good examples of biotops could be:
 
 * Magical forest
 * Techno city
 * Dungeons of Hell

#### Archetype

Archetype is a algorithm (or parameters for algoritm) of procedural generation of level.

 * Plain - non man-made looking plain with island-looking obstacles
 * Dungeon - man-made looking dungeon with straight lines of walls

#### Handmade level pieces

Those are level pieces, handcrafted and associated with biotops. Good examples of such pieces could be:

 * DMV room with lines of people, DMV workers, bars
 * Throne room with throne, long red carpet, shields on the walls, guards.

#### Set of assets

Every asset have a parameters:

 * Name
 * Obstacle or passable
 * Rarity
 * Family (such as "Wall", or "Water" - walls assets should not be in the middle of the water, and vice versa)

### Exploration/Combat


## Game Spec

### Functional Spec


### Visual Spec


### Asset catalogue
