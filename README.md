# Corpse Arithmetic

An encounter simulator for MÖRK BORG. Stat a creature, build an encounter, and run your party through thousands of fights to see how often they win, how often someone dies, and how much HP they lose.

**Use it:** https://klmix.github.io/corpse-arithmetic/

## What it does

- **Bestiary**: the 12 creatures from the Bare Bones edition, all editable, plus your own. Dice notation (`d4`, `2d6`, `d4+1`) for HP and damage; weighted attacks, extra attacks per round, fear, ambush, paralysis, drain and lingering afflictions.
- **Encounter**: any mix of creatures and counts, with an optional leader for Morale.
- **Party**: edit characters by hand or roll them by class from the book's tables.
- **Verdict**: win rate, chance of at least one death, total party kill, deaths per fight, average HP lost per survivor, afflictions carried out of the fight, and a full log of a sample fight.

## Rules modelled

Side initiative, melee (Strength) and ranged (Presence) attacks, Agility defence, crits and fumbles, armor tiers and their DR penalty, shields, Omens, the Broken table (0 HP is Broken, below 0 is dead), hemorrhage, and Morale. A toggle switches to the house rule where any drop to 0 or below is Broken.

Not modelled: Powers and scrolls, fleeing player characters, healing mid-fight, ammunition, and most class abilities beyond attack/defence DR modifiers.

## Running locally

It's a single `index.html` with no build step. Open it in a browser. Setups are saved in your browser's local storage and can be copied out as JSON from "Save or share this setup".

---

Corpse Arithmetic is an independent production and is not affiliated with Ockult Örtmästare Games or Stockholm Kartell. It is published under the MÖRK BORG Third Party License. MÖRK BORG is copyright Ockult Örtmästare Games and Stockholm Kartell.
