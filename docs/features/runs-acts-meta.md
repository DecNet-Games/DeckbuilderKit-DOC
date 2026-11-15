---
layout: default
title: Runs, Acts & Meta
parent: Features
nav_order: 2
---

# Runs, Acts & Meta

## The run

A run is a map of encounters across three acts: combat, elites, events, rest sites, shops and a boss at each act's end. Run state is your deck, health, gold and relics/upgrades.

## Maps that always work

Every generated map has at least one connected route from entry to boss — asserted across a generated-map set, not hoped for. Act definitions are data files: change one act's definition and you change that act's encounters only, never another act's.

## Save and resume exactly

Save mid-run and reload, and the run resumes at the exact same encounter with the exact same deck and state — state hash before save equals state hash after load, verified across a set of save points.

## Meta that persists

Unlocks earned in one run are present in the next. Meta state saves and loads alongside run state, so progression survives sessions, not just runs.
