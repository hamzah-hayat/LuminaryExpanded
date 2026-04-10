# Luminary Expanded

## Overview
Luminary Expanded is a mod for Stellaris that overhauls and expands the Galactic Paragons DLC's Luminary origin. This mod adds new events, situations, council agendas, and expanded player choices to make the Luminary origin feel more dynamic and reactive to your empire's achievements. It is designed to reward players who engage with the origin's narrative by providing more ways to grow (or lose) the Luminary trait through meaningful gameplay milestones.

## Features

### 40 Year plan
Choose the bonus from the 40 year plan, instead of getting one randomly, choices are vanilla, which are:
- Upgrade a starbase
- Discover living metal
- Find dark matter
- Prospect strategic resources

### Expanded Forgotten Situation Events
The three Forgotten situation escalation events now have additional options beyond the vanilla choices:
- **Event 1:** Pay Unity, pay Influence, or take a bad media coverage modifier.
- **Event 2:** Pay Energy, pay Trade, or take a bad media coverage modifier.
- **Event 3:** Pay Unity, pay Influence, or take a bad media coverage modifier.
These give you bonus cost options instead of relying on unity and energy to avoid losing Luminary points.
Each option scales, similar to vanilla, a stronger government tier lowers the scaling, as per vanilla.

### Dying Heir Situation
A fully-featured bidirectional situation that adds a major narrative event chain when the Luminary's heir falls ill.
This replaces your heir always dying, with a nice little situation that happens alongside the reformist one.

- **Three Approaches:**
    - **Palliative Care** — Accept the heir's death. Gives +10% unity, -25% egalitarian attraction. No healing progress.
    - **Medical Treatment** — Standard treatment. +10% doctor upkeep. Doctors workforce scaling applies.
    - **Radical Intervention** — All-out effort. +15% doctor and biologist upkeep. Both doctors and biologists workforce scaling apply.
- **Workforce Scaling:** Having more healthcare and biologist jobs in your empire directly improves your chances of curing the heir (every 100 workers provides +0.1 monthly situation progress).
- **Disease progress:** As time passes, the heirs sickness gets worse, upto a maximum level of negative progress.

- **Three Stages:**
    - **Dying (0–20):** Condition worsening. +15% unity, -5% pop happiness.
    - **Steady (20–80):** Condition stabilized. +5% unity.
    - **Recovering (80–100):** Condition improving. +5% unity, +5% pop happiness.

- **Random Events:** Medical setbacks, breakthroughs, and four duty dilemma events where you must balance the heir's health against governance needs (public speeches, council work, colony visits, navy inspections).

- **Two Outcomes:** Miraculous recovery (+1 Luminary, delusion decrease) or tragic death (-2 Luminary, delusion increase).

### Milestone Achievement Events
Six new narrative speech events triggered by major empire accomplishments. Each increases the Luminary trait by +1.

- **A Monument to Progress** — Triggered when you build a megastructure.
- **The Beast is Slain** — Triggered when you defeat a guardian or leviathan.
- **A Homeworld Claimed** — Triggered when you conquer the homeworld of another empire. (Repeatable)
- **The Pillars of Culture** — Triggered when all tradition slots are filled.
- **Echoes of the Ancients** — Triggered when you complete a precursor event chain.
- **The Crisis Averted** — Triggered when a mid-game or end-game crisis is defeated.

Winning a war or making another empire a vassal are now repeatable events, rewarding +1 Luminary point each.

### Luminary Trait Max Cap
- The Luminary trait can now be maxed out at 20 points, triggering **"The Legendary Luminary"** event.
- Grants a bonus skill level and gives the Luminary trait and Luminary ascension traits small bonus effects.

### Ethic-Specific Leader Trait Choices
The vanilla "Diligent Leader" and "Order Restored" events are expanded with 7 ethic-aligned response options (Militarist, Spiritualist, Authoritarian, Xenophile, Pacifist, Materialist, Xenophobe), each granting a corresponding legendary trait.
Lets you get the Luminary traits more closely aligned with your empires ethics, rather then a random one.

### Ascension Path Event
Reduced the time after an Ascension path is finished before the Luminary Ascension event fires.

### Luminary Trait Growth Summary
Events that **increase** the Luminary trait:

| Event | Description | Change |
|---|---|---|
| Colony Monument (Rich/Residential) | Built a monument on first colony | +1 |
| Become Imperial | Changed government to Imperial | +1 |
| Made a Federation | Joined or created a federation | +1 |
| Became Overlord | Became overlord of another empire | +1 | Repeatable
| Won a War | Won a war | +1 | Repeatable
| Built a Megastructure | Completed a megastructure | +1 |
| Became Custodian | Became galactic custodian | +1 |
| Became Emperor | Became galactic emperor | +2 |
| Defeated a Guardian | Killed a guardian/leviathan | +1 |
| Conquered a Homeworld | Conquered a rival homeworld | +1 | Repeatable
| All Traditions Filled | Completed all tradition trees | +1 |
| Precursor Completed | Obtained a precursor relic | +1 |
| Crisis Defeated | A crisis was defeated | +1 |
| Forgotten Crushed (No Rebels) | Forgotten situation ended with no rebels | +2 |
| Forgotten Crushed (Blood) | Purged the reformists by force | +8 |
| Heir Cured | Heir illness resolved positively | +1 |
| Ascension Path Trait | Gained an ascension luminary trait | +1 |

Events that **decrease** the Luminary trait:

| Event | Description | Change |
|---|---|---|
| Lost a War | Lost a war | -2 |
| Became a Vassal | Became subject of another empire | -3 |
| Forgotten Escalation (free option) | Chose to lose trait point during Forgotten events | -1 |
| Order Restored (fallback option) | Chose generic modifier after defeating Forgotten | -1 |
| Heir Died | Heir illness resolved negatively | -2 |

## Installation - Manual
1. Download or clone this repository into your Stellaris mods folder.
2. Ensure the folder structure is preserved (the `descriptor.mod` file should be in the root of the mod folder).
3. Enable "Luminary Expanded" in your Stellaris launcher.

Or install via the Steam workshop.

## Compatibility
- Designed for Stellaris version 4.3.1 and above.
- Requires the **Galactic Paragons** DLC.
- Compatible with most mods that do not alter the Luminary origin events.
- Vanilla file overwrites:
    - Overwrites `events/origin_events_paragon.txt` (the main Luminary origin events file)
    - Overwrites `common/traits/10_paragon_traits.txt` (paragon leader traits)

## Credits
- Mod Author: Hamzah Hayat
- Original Luminary Origin by Marek Kozlowski, Linus Dilen, and Haig Morrison (Paradox Interactive)
- Special thanks to the Stellaris modding community for resources and inspiration.
