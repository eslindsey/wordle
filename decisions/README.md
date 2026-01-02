# Decisions

These files indicate WordleBot's preferences on guess 2, based on the starting word in the name of the file. They can be great hints if you don't want spoilers. The Bot's current favorite is [SLATE](slate.md).

There are two [play modes](#play-modes)  and multiple [solution lists](#solution-lists), both of which affect the Bot's selection. Notes have been added to the files where appropriate.

The markdown tables are sorted by number of greens, location of greens, then by yellows.

## Play Modes

Play modes affect WordleBot the same way they affect the player, so playing on Hard Mode will (usually) result in a different second guess than playing on Easy Mode.

## Solution Lists

We are currently aware of three solution lists.

### Pre-NYT

This is the original allowed word list and solution list. It is publicly available.

### Post-NYT

After the New York Times bought Wordle, the solution list was no longer available from the JavaScript source code. WordleBot favored [CRANE](crane.md) as its starting word during this era.

### Post-LORIS

The bot had to be updated when the Times decided to run LORIS as a solution, because it wasn't in the original word lists. This changed the decision tree for the bot, and its new favorite is [SLATE](slate.md).
