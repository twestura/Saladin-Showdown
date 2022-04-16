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

## Jerusalem

In the original campaign Jerusalem is the Byzantines.
In the Definitive Edition the player is the Franks.
I'll revert them to the Byzantines to increase civilization variety, since there already is a Franks player.

## Map Changes

TODO

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

## AI Behavior

TODO

## Stretch Goals

* Translations (other than just an English version).
