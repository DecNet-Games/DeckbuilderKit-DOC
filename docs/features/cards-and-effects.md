---
layout: default
title: Cards & Effects
parent: Features
nav_order: 1
---

# Cards & Effects

## Card definitions are data

A card is a data file: cost, effects, targeting, upgrades, keywords. Adding a test card as data only — no code change — produces a card that can be drawn and played. That is the kit's core promise, and it is asserted by a data-only-add test.

## The resolution engine

Playing a card runs an effect-resolution pipeline: effects resolve in order, and triggers fire on play, on draw, on damage, and on turn start/end. The engine manages the deck, discard and exhaust piles throughout.

**Deterministic by design.** Given the same deck order, seed and action sequence, resolution reproduces the same combat-state hash — the property the balance harness and the test suite are built on.

## Keywords and statuses are documents, not folklore

Every keyword and status has a documented definition with exact amounts: a status that blocks damage blocks exactly its stated amount; a keyword that draws cards draws exactly its stated count. A fixed test set asserts each one.

## Bad data fails loudly

A missing effect reference, an invalid target, a negative cost, an upgrade pointing nowhere — each is reported with a clear error naming the card. Never a silent no-op, never a crash.
