# Bleed Research Notes

## 1. Bleed Is Based on the Physical Hit

The initial physical hit determines the Bleed's base magnitude. Once the Bleed has been applied, generic damage modifiers do not continue scaling it. Instead, Bleed damage is primarily increased by:

- Making the initial hit larger.
- Using modifiers that specifically affect Bleeding.
- Using modifiers that affect ailment magnitude.

**Key Takeaway:** Prioritize huge physical hits.

---

## 2. Bleed Does Not Stack

Consider the following sequence of hits:

```text
100
90
110
80
95
```

The strongest hit creates the strongest Bleed:

```text
110
```

While the game can track multiple Bleeds on a target, only the strongest Bleed deals damage at any given moment.

This has an important implication:

> Attack speed has diminishing returns if you are frequently replacing powerful Bleeds with weaker ones.

The goal is not necessarily to apply more Bleeds, but to consistently apply stronger Bleeds.

---

## 3. Aggravate Is Enormous

Aggravated Bleeding causes the target to be treated as though it is moving, effectively doubling Bleed damage even against stationary bosses.

This makes Aggravate one of the most important mechanics to investigate.

### Research Question

> Can Deadeye reliably Aggravate Bleeding?

If the answer is **yes**, then Aggravate may be a mandatory component of the build.

---

## 4. Critical Strikes May Be More Important Than Expected

Because Bleed is calculated from the damage of the hit that applied it, critical strikes naturally create stronger Bleeds by creating larger hits.

This raises an interesting question:

Instead of prioritizing:

- Attack Speed

Should we prioritize:

- Critical Strike Chance
- Critical Strike Multiplier
- High Physical Damage Bows

If larger hits produce significantly stronger Bleeds, crit-based scaling may outperform traditional attack-speed scaling.

This is something we can validate in Path of Building (PoB).

---

## 5. Chance to Bleed Is Mandatory

Bleed cannot be be applied without an explicit source of Chance to Bleed.

As a result, one of our first objectives should be reaching **100% Chance to Bleed**.

A massive hit that fails to apply Bleed is effectively wasted damage.

---

## Current Hypotheses

| ID    | Hypothesis                                                            | Confidence |
| ------- | ----------------------------------------------------------------------- | ---------- |
| H-001 | Larger hits provide more value than faster attacks.                    | ★★★★★ |
| H-002 | High-physical-damage bows outperform elemental bows for Bleed builds.  | ★★★★★ |
| H-003 | Critical strikes may be a major source of Bleed scaling.               | ★★★★☆ |
| H-004 | Aggravate is a core mechanic for boss damage.                          | ★★★★★ |
| H-005 | Attack speed only needs to be high enough to maintain Bleed uptime.    | ★★★★☆ |

## Preliminary Conclusions

Based on current understanding of Bleed mechanics:

1. Prioritize high physical damage over attack speed whenever possible.
2. Ensure 100% Chance to Bleed before investing heavily in scaling.
3. Investigate reliable sources of Aggravate, as it may represent the largest single damage multiplier available.
4. Test crit-based scaling against attack-speed scaling in PoB.
5. Focus on maximizing the strength of each Bleed rather than the number of Bleeds applied.

## Next Research Tasks

- [ ] Confirm how Aggravate can be applied consistently on Deadeye.
- [ ] Compare high-physical bows versus elemental bows in PoB.
- [ ] Compare Crit Chance and Crit Multiplier against Attack Speed scaling.
- [ ] Identify the most efficient sources of Chance to Bleed.
- [ ] Determine the minimum attack speed required for comfortable Bleed uptime.
