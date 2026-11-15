---
layout: default
title: Home
nav_order: 1
---

# Stop rebuilding the machinery. Start designing cards.

![Single-Player Deckbuilder / Card Battler Complete Kit]({{ site.baseurl }}/assets/images/cover.png)

<video controls preload="metadata" style="max-width:100%" poster="{{ site.baseurl }}/assets/images/cover.png">
  <source src="{{ site.baseurl }}/assets/video/demo.mp4" type="video/mp4">
</video>


Every solo developer who attempts a deckbuilder rebuilds the same invisible machinery first — card data, effect resolution, enemy behaviour, run structure, save and meta-progression — before designing a single interesting card. The **Single-Player Deckbuilder / Card Battler Complete Kit** is that machinery, finished, with a complete playable game inside the box.

---

## What it does

- **Cards are data** — card definitions (cost, effects, targeting, upgrades, keywords) live as data files. Add a card with no code change; the resolution engine plays it, resolves effects in order and fires triggers across deck, discard and exhaust piles. Combat is deterministic: the same action sequence replays to the same combat state.
- **Intent-based enemies** — every enemy declares its next move before you act, and the declared intent is the action it takes. Elites and bosses run patterned, multi-phase intents. Enemy behaviour is data, not code.
- **A full run loop** — a map of encounters across three acts (combat, elites, events, rest, shops, bosses), with a guaranteed connected route from entry to boss, mid-run save/load that resumes exactly, and meta-progression that persists between runs.
- **A balance-simulation harness** — automated run-throughs that play the game without a human and output win-rate curves per act and per deck archetype, under one documented policy. Your own cards and enemies join the harness pools.
- **150+ cards and a complete game** — three acts of content with a boss at each act's end, and the full presentation layer: hand and combat interface, run map, deck viewer, event, shop and rest screens. Everything reskinnable.

![The run map journey]({{ site.baseurl }}/assets/images/hero-01.png)

---

## The honesty policy

The kit's depth claims are the harness's recorded output and the content counts in the verification record — not adjectives. Single-player is a deliberate scope, stated up front: there is no networking in this box, and [Limitations]({{ site.baseurl }}/docs/limitations/) says what else is not in it.

---

## Quick links

- [Getting Started]({{ site.baseurl }}/docs/getting-started/) — core concepts in five minutes
- [Installation]({{ site.baseurl }}/docs/installation/) — Asset Store purchase and setup
- [Quick Start]({{ site.baseurl }}/docs/quick-start/) — your first run, then your first card
- [Features]({{ site.baseurl }}/docs/features/) — deep dives on every system
- [API Reference]({{ site.baseurl }}/docs/api/) — data formats and the harness interface
- [The Game in the Box]({{ site.baseurl }}/docs/samples/) — cards, acts and content
- [FAQ]({{ site.baseurl }}/docs/faq/)
- [Limitations]({{ site.baseurl }}/docs/limitations/)

---

*Single-Player Deckbuilder / Card Battler Complete Kit is a commercial Unity product by DecNet Games. Built for Unity 2022.3 LTS and Unity 6. Support: support@decnetgames.com.*
