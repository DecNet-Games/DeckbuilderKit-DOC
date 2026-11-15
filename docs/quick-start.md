---
layout: default
title: Quick Start
nav_order: 4
---

# Quick Start — your first run, then your first card

## Play a run (about five minutes)

1. **Open the sample game scene and press Play.** You are on the act map: a route of encounters from entry to boss.
2. **Pick a path and enter combat.** Draw your hand; the enemy's intent icon shows its next move before you play. Answer it.
3. **Win, take a card reward, move on.** Visit an event, a shop, a rest site. Reach the act boss.
4. **Save mid-run and quit. Reload.** You resume at the exact encounter with the exact deck and state.

## Add your first card (about five minutes more)

5. **Copy any existing card's data file** and change its name, cost and effects. No code anywhere.
6. **Start a new run.** Your card is in the pool — drawable and playable, resolved by the same engine.
7. **Break it on purpose:** point its upgrade at a card that does not exist. The kit reports an error naming your card instead of failing silently.
8. **Run the balance harness** with your card in the pool and read its win-rate contribution in the curves.

From here: [Cards & Effects]({{ site.baseurl }}/docs/features/cards-and-effects/) documents the data format, [Enemy Intents]({{ site.baseurl }}/docs/features/enemy-intents/) covers patterns, and [The Balance Harness]({{ site.baseurl }}/docs/features/balance-harness/) explains the curves.
