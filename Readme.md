# Saladin Showdown

An event in the same spirit as the *Barbarossa Brawl*.
Players defend Acre against Crusader armies and compete to obtain high scores.
Everyone who achieves a score that crosses a certain threshold is entered into a drawing to win a prize.

## Sounds

The voice acting from the English version of the original game is used.

## Defeat

The player is defeated when the Wonder reaches 0 HP.
This condition triggers the, "The Wonder, the Wonder, the... no!" taunt 26.
When the Wonder is destroyed fully (using the)

## Timer

There are two main timers:

1. A 5:00 countdown until the attacks begin.
2. A 25:00 countdown until the player wins.

In total the scenario takes 30 in-game minutes.
This time is roughly 17:39 in IRL time at 1.7x speed.
When the time expires, the player's score increases by 10,000 points.

## Tribute Score

By using the Modify Resource effect to add to a player's score with Item ID 175, we give score to the player for completing secondary objectives.
Every 10 Tribute Score contribute's 1 point to the player's score.

The player get a constant trickle of 500 Tribute Score every 5 in-game seconds, matching that of the Barbarossa Brawl.

## Jerusalem

In the original campaign Jerusalem is the Byzantines.
In the Definitive Edition the player is the Franks.
I'll revert them to the Byzantines to increase civilization variety, since there already is a Franks player.

## Map Changes

TODO

Potential changes:

* More Wood, Gold, or Stone on the "island" to the east, just south of Jerusalem.
* Gate in the eastern wall, heading towards Jerusalem.
* More Wood at the bottom of the cliffs near the city.
* Remove rocks from the Gold island.
* Put 150 or 200 Wood on the trees near the city (increased from the standard 100 Wood).
* More Docks at the Persian Outpost.
* Visibility of the Persian player.
* Remove buildings and units from AI player starting bases.

## Persian Outpost

The Persian Outpost will provide fully upgraded Elite War Elephants and periodic "sling".
Each shipment of Elite War Elephants increases the player's maximum population limit by the number of elephants.

The elephants transports run at these times:

1. 10:00 - 5 Elephants
2. 15:00 - 10 Elephants
3. 23:00 - 20 Elephants

TODO handle cases where the Transport Ship is blocked and cannot unload.
Could be with triggers or with DUC in the AI script.

The slings run at these times:

1. 7:30 - 500 Food
2. 13:37 - 500 Food, 500 Gold
3. 19:00 - 500 Food, 500 Stone
4. 25:00 - 500 Food, 500 Wood, 500 Gold, 500 Stone

## Score Objectives

TODO

* Capture Relics (2,000 per Relic, extra 5,000 for capturing all 5)
* Explore the Gold island, Persian Outpost, north and south corners (1,000 each, with a 1,000 bonus for reaching all of them)
* Destroy the Hero Trebuchets (1,000 for the first, 1,000 for the second, and 1,000 for both---a total of 3,000)
* Defeat enemy players (20,000 per player, 50,000 for defeating all of them)
* Survive 30 minutes (20,000)

## Relics

Each computer player has one Relic that they keep in their Monastery.
All players build at least 1 Monastery and 1 Monk to reclaim the Relic if it's
lost and in their base.
The player gets 2,000 points for each Relic captured.
A bonus 5,000 for capturing all 5 Relics.

## AI Behavior

### Unit Compositions

TODO

### DUC Micro

* Franks: Castle drops, keep Bombard Cannons near Castles.
* Jerusalem: Monk micro vs siege.
* Genoese: Fish Trap Docks, transport to the Gold island.
* Templars: Teutonic Knights and Siege Towers.
* Richard: Longbowmen keep under Castles and attack move.

## Scenario Instructions and Objectives

TODO

## Stretch Goals

* Translations (other than just an English version).
* Individually increase the population limit per elephant as they disembark.
* More Epic ending: kill or explode all enemy units and buildings.
* Victory instead of defeat when Wonder goes down?

## Questions

* How should the Relic objective be displayed?
* Current Relics or Max Captured Relics?
* Only build Mining Camps when there is neither a camp nor a TC on the Gold?
* Build Mining Camps on Gold or Stone specifically?
* Make the Transport Repeatedly unload if it's blocked (probably through DUC)?
* Place Mills for Farms?
* Need to improve the behavior of AI units attacking the Wonder.
* Prevent TC placement while build-line is being used.
