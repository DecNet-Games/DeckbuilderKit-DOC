---
layout: default
title: Presentation Layer
parent: Features
nav_order: 5
---

# Presentation Layer

The visible game surface, ready to reskin:

- **Hand of cards** — draw, play, discard. Playing a card moves it to the correct pile (discard or exhaust, per its definition); drawing refills to the documented hand size.
- **Combat interface** — health, block, energy, and the enemies' intent display.
- **Run-map screen** — shows the actual generated map; the displayed nodes match the map data exactly (asserted by a map-vs-UI comparison).
- **Deck viewer**, plus **event, shop and rest screens** — each completes its full flow: enter, choose, exit with the documented effect applied.

## Reskinning changes nothing underneath

Swap the sample game's card art and backgrounds for placeholders and no card, combat or run behaviour changes — asserted by re-running the engine test set against the reskinned scenes.
