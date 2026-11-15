---
layout: default
title: Enemy Intents
parent: Features
nav_order: 3
---

# Enemy Intents

The genre's core combat decision: the enemy shows its next move, you read it, then you play.

- **Declared before your turn.** Attack, block, buff, debuff, summon — every enemy declares an intent before the player acts.
- **The declaration is the action.** Across the verification combat set, the declared intent matches the action actually taken, every time.
- **Correct after every state change.** Re-run the same combat with the same seed and the intent sequence reproduces exactly.
- **Patterns for elites and bosses.** Multi-phase and patterned intents (for example, a boss alternating attack and summon on a stated turn cycle) follow their documented definitions, asserted per boss and elite.
- **Behaviour is data.** Add a test enemy with a new intent pattern as a data file only, and it fights. Malformed enemy data — an intent with no action, a missing icon, a pattern referencing a phase that does not exist — is reported naming the enemy.
