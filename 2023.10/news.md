# Galactic Dispatch 2023.10

The focus this month was on getting out of deep freeze and focused on some kind
of playable prototype. 

## Interplanetary Navigation

Systems with only one planetary body are, to put it bluntly, boring! Manually
navigating to e.g. the moon was a massive hassle and would make playing within
any non-trivial system a tedious chore.

![interplanetary](interplanetary.webm)

This took a lot of cycles; it turns out interplanetary navigation is not
trivial! I'm super happy with the results.

## Major UI Overhaul

The maneuver UI for fleets now is a singleton (only one can be open at a time)
and it occupies a panel on the bottom of the screen instead of a floating
window.

![bottom ui](bottom-ui.webm)

The window just got in the way, and didn't provide enough space for important
stuff (like the new Fleet pane). It also didn't play well with "fatter" screen
formats like my Framework's 4:3.

## Trade Improvements

Markets can now hawk:

- Ships (well, full fleets really). "Buy" side only (you can't sell ships back
  to other factions yet). This opens the way for deals on missiles, strike
  packages, new ships, and more.
- Modules. Again, "buy" only (you can't sell modules back yet).

## Looking Forward

I'll probably have a lot less free time next month, but here's the rough
priorities of what I want to work on:

- System definitions (in progress). RON-defined bodies to remove the last
  hardcoded spawning steps. This has been a PAIN.
- More trade improvements:
  - Ability to set target modules for trades.
  - Purchase repairs.
  - Sell modules.
  - Contracts (bounties to destroy e.g. pirate ships will be the first iteration
    of these)
- Probably will start seriously looking at "transit": changing systems. In other
  words, forward progress in any serious roguelike spin on this game.