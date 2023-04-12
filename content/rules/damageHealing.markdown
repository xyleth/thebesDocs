---
layout: default
title: Damage and Healing
parent: Rules
nav_order: 3
---

# Damage and Healing

Damage is tracked on the [damage track](#damage-track). This represents the damage taken by your Morph.

## Damage Track

\[\] `+scuffed`
\[\] `+scuffed`
\[\] `+scuffed`
\[\] `+stunned`
\[\] `+wounded`
\[\] `Dead`

Each of these applies the respective [tag](/content/tags/damageTrauma.html) to your character. For ease of reference these tags are reproduced here:

- `+scuffed` – Minor damage, no game mechanical detriment
- `+stunned` – You are `+glitched` on all actions and will get worse unless stabilised
- `+wounded` – You are `+degraded` on all actions and will die quickly unless stabilised
- `Dead` – Not a tag, so much, as a state of being. If you don’t have a `+cortical stack`, you’re gone.

## Damage

### Damage Move

When you **_take physical damage_** from something, roll+Armor. On a 10+, you absorb or avoid the blow entirely. On a 7-9, the GM chooses 1:

- You lose your footing. `+glitched` ongoing until you can regain it.
- You lose your grip on, or otherwise damage whatever you’re holding. Lose an item of gear.
- You lose track of someone or something you’re attending to.
- It’s a glancing blow. Mark 1 off the **_damage track_**.

On a miss, you suffer the full brunt of the damage and the GM chooses 1:

- You're out of action: Unconscious, trapped, incoherent or panicked.
- It's worse than it seemed. Take and additional 1-harm.
- Choose 2 from the 7-9 choices.

## Healing

`scuffed` checks on the damage track will heal automatically with time due to standard transhuman physiology and biomods. It may be considered that these wounds will heal in-between scenes. Wounds do not heal if you have the `stunned` or `wounded` tags.

The `stunned` checkbox may be healed in the field by a character who has **medical supplies** and a move that allows them to use them, or by any player with a **nanobandage**.

Healing the `wounded` tag requires access to medical facilities and someone who can use them, for example with the [Medical Miracle Worker](/content/moves/tech#Medical) move. Stabilising a `wounded` character may be attempted with **medical supplies**.

### Medical supplies

Trained medical professionals, such as those with the **_[Battlefield Medic](/content/moves/combat#Medic)_** move, may use a medical kit in the following fashion:

Your kit has all kinds of stuff in it, like nanobandages and advanced biotech, represented by a “stock” score. A fresh, unopened medical kit as a stock score of 10. When you use it, spend its stock; you can spend 0–3 of its stock per use. You can resupply it with a **_procure something_** roll if your circumstances let you barter for medical supplies.

If the target has `medichines` you are `boosted` on the below rolls.

To use it to remove `+stunned`, roll+Stock spent. On a hit, they will stabilise and heal to their third `+scuffed` tag, and choose 2 (on a 10+) or 1 (on a 7–9):

- they fight you and you have to sedate them. How long will they be out?
- the pain and drugs make them babble the truth to you. Ask them what secret they spill.
- they respond very well to treatment. Recover 1 of the stock you spent, if you spent any.
- they’re at your complete mercy. What do you do to them?
- their course of recovery teaches you something about your craft. Mark experience.
- they owe you for your time, attention, and supplies, and you’re going to hold them to it.

To use it to stabilise a `wounded` patient roll+Stock spent. On a hit, they will stabilise and but not heal. Choose 2 (on a 10+) or 1 (on a 7-9) as above.

On a miss, they mark one more off the [damage track](#damage-track). This can kill them.

To use it to revive someone who’s on death’s door (`Dead`, but not beyond, and not for long - they died in the current scene): spend 2-stock. Choose 1 of the above, and they come back, but you get to choose how they come back:

- they come back in your deep, deep debt
- they come back with -1 Hard
- they come back with -1 Reflex
- they come back with -1 Willpower

### Nanobandages

These useful devices are one-use emergency hives of nanomachines that can rapidly repair damaged tissue. **_When applying a nanobandage in battle_** roll+Cognition. On a 10+, stabilise a `wounded` character or heal two checks off the **_damage track_**. On a 7-9, there is no effect on a `wounded` character, all others heal one check. On a failure, the bandage is wasted and you may have made things worse.

### Medichines

You have elaborate, custom built medical technology in your body. You gain the `close wounds` move as below and automatically stabilise if `stunned` or `wounded` :

#### Close Wounds

At the end of a scene in which you have either the `stunned` or `wounded` damage track boxes ticked, roll. If you have taken no damage in the scene you are `boosted` for this roll.

- On a 10+ you heal one point from your damage track.
- On a 7-9 the medichines staunch the wound but the healing is incomplete or sub-optimal in some way. Heal one point from your damage track, but you are `glitched` ongoing until you can resolve the situation[^1].
- On a 6- the damage is too great for the medichines to heal. You heal no damage and are `glitched` ongoing due to the drain of your medichines struggles to heal you. Outside medical attention or a significant period of rest is required to resolve this situation.

[^1]: Taking the **_Close Wounds_** move at the end of the following scene counts for this purpose
