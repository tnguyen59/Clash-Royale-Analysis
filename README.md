# cmsc320-final-project
Authors: Brendan Collins, Rennie Pearson, Yash Joon, Thien-An Nguyen

To do:
Add into data csv file
# Per unit
Cost
isFlying
isSplash
isRange
unit type ie unit, tower, spawner, spell can use 1 2 3 4?

cardlist columns:
id - card id
card - card name
cost - elixer cost
rarity - rarity (common, rare, epic, legendary, champion)
type - type of card (unit, defense, spawner, siege, building, spell)
isFlying - if card is a unit and is flying -> true else if card is a unit and not flying -> false else -> NaN
target - what the card itself targets (ground, air, all, units) 
troop_spawned - if the card spawns a troop -> card spawned else -> NaN

Important notes:
Mirror is noted as having cost of 0
Clone and target units
Mirror and Clone are marked as spawning "Any" since they can become any unit
Lava Pups, Golemites, Elixer Golemites, Elixer Blobs, Pigs, and Goblin Brawler are all spawned but do not have playable cards
  - their rarity matches the spawning card
  - they have no cost
The type of building has been split up into 4 categories
  - defense: buildings that have no offensive capability like cannon, inferno tower, etc.
  - spawner: buildings that spawn troops continously
  - siege: buildings used to attack enemy towers
  - builings: elixer collector and goblin cage
Target is only about what the card has listed as a target

# Per deck
avgCost
percentage of type of unit
win in arena?

# General
How many different type of decks can we make? total combinations 278818865325 combinations -> 105 choose 8
Based on type of cards # of combinations = 165 -> 4 choose 8
What hands can be made from each deck? we can have 4 cards at a time
What we classify deck as - 3 spawner 1 unit etc.
Find highest winrate amongst cards and put into a deck and find out if it has good winrate
Is an all tower deck better than all spawner etc.