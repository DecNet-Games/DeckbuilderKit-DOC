---
layout: default
title: API Reference
nav_order: 6
---

# API Reference

This page covers the kit's public contract: the data formats you author in, and the harness interface. The offline API reference inside the package documents every public method signature and matches this site's version.

## Data formats

- **Cards** — cost, effects (ordered), targeting, upgrade chain, keywords. Authored as data files; validated on load, with errors naming the card.
- **Enemies** — behaviour patterns as data: intent sequences, phases for elites and bosses, icon mapping. Validated on load, with errors naming the enemy.
- **Acts** — encounter composition per act as data files; each act's definition affects that act only.
- **Maps** — generated from seeds under the run's configuration; the route guarantee (at least one connected entry-to-boss path) holds for every generated map.

## The harness interface

- Runs automated batches over a seed set and writes **CSV + chart data**: win rates per act and per archetype.
- The player policy is documented in the package and is the same for every archetype in a run.
- Buyer content added as data joins the card and encounter pools automatically; per-card win-rate contribution is reported.

## Determinism contract

Given (deck order, seed, action sequence), combat resolution reproduces the same combat-state hash. Save/load round-trips preserve the run-state hash exactly.
