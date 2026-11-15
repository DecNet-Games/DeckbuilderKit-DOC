---
layout: default
title: Getting Started
nav_order: 2
---

# Getting Started

Three ideas explain the whole kit.

## 1. Content is data

Cards, enemies, acts and maps are data files. The engines that run them — resolution, intent, run structure — never change when your content does. Adding a card or an enemy is an act of design, not programming, and malformed data is reported with an error naming the entry.

## 2. Combat is readable and deterministic

Enemies show their intent before you act, so every turn is a decision with full information. And the resolution engine is deterministic: replay the same action sequence and you get the same combat state — which is what makes the balance harness meaningful.

## 3. Balance is measured, not felt

The harness plays the game in large automated batches under a documented policy and reports win-rate curves per act and per archetype. When you add content, it joins the pools and shows up in the numbers.

Next: [Installation]({{ site.baseurl }}/docs/installation/), then the [Quick Start]({{ site.baseurl }}/docs/quick-start/).
