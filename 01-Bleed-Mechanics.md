
##1. Bleed is based on the physical hit

The initial physical hit determines the Bleed's base magnitude. Generic damage modifiers don't keep scaling the Bleed after it's has been applied—you primarily scale it by making that initial hit bigger or by using modifiers that specifically affect Bleeding or ailment magnitude

Meaning: Huge physical hits

##2. Bleed does NOT stack
If you attack like this:
100
90
110
80
95
Only this gets the bleed
110

That means attack speed has diminishing returns if you're constantly replacing powerful Bleeds with weaker ones. The game tracks multiple Bleeds, but only the strongest deals damage at any moment.

##3. Aggravate is enormous

Aggravated Bleeding makes the target count as moving, effectively doubling Bleed damage even against stationary bosses.

That means one of our research goals becomes:

Can Deadeye reliably Aggravate Bleeding?

If yes...

that's probably mandatory.

##4. Crit is more interesting than many people think

Since Bleed is calculated from the actual hit, a critical strike creates a larger hit, which in turn creates a stronger Bleed.

That raises an interesting question.

Instead of scaling

Attack Speed

should we scale

Critical Strike Chance

Critical Strike Multiplier

Huge Physical Bow
This is something we can test in PoB.

##5. Chance to Bleed

Bleed still requires an explicit source of Bleed chance. Our first objective will be reaching 100% chance to Bleed, because a massive hit that doesn't inflict Bleed is effectively wasted.

| ID    | Hypothesis                                                           | Confidence |
| ----- | -------------------------------------------------------------------- | ---------- |
| H-001 | Bigger hits are better than faster attacks                           | ★★★★★      |
| H-002 | High physical bows outperform elemental bows                         | ★★★★★      |
| H-003 | Crit may be a major Bleed scaler                                     | ★★★★☆      |
| H-004 | Aggravate is a core mechanic for boss damage                         | ★★★★★      |
| H-005 | Attack speed only needs to be "good enough" to maintain Bleed uptime | ★★★★☆      |

