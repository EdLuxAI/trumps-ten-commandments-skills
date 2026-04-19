# Skills distilled from *Trump's Ten Commandments*

This folder contains **nine Claude agent skills** distilled from Jeffrey Sonnenfeld and Steven
Tian's *Trump's Ten Commandments: Strategic Lessons from the Trump Leadership Toolbox* (2025),
produced using the `distill-to-skill` framework (v0.2).

## What this is

Each skill is a self-contained folder with runtime-loadable instructions for a Claude agent. The
skills are **problem-centric, not person-centric** — they are named for the user's situation, not
for Trump. They generalize to any dominance-seeking leader deploying similar tactics.

Each skill pairs **identification** (what the tactic is, where it comes from, how to recognize
it) with **counter-moves** (what to do about it). The book's argument is that Trump's tactics
are not random chaos but a limited, repeated playbook; these skills make that playbook legible
and suggest defenses.

## The nine skills

| # | Skill | When it fires |
|---|---|---|
| 1 | [`dealing-with-a-centralizing-boss`](dealing-with-a-centralizing-boss/) | You're working for, advising, or evaluating an org where one person is the hub, lieutenants are interchangeable, and real authority doesn't live anywhere else |
| 2 | [`when-a-negotiation-opens-with-a-punch`](when-a-negotiation-opens-with-a-punch/) | Your counterparty's first move is shock-and-awe — maximalist demand, threat, or ambush |
| 3 | [`spotting-deals-where-youre-the-bag-holder`](spotting-deals-where-youre-the-bag-holder/) | A deal is on the table that may be structured so the other side keeps the upside while you inherit the downside |
| 4 | [`standing-together-against-divide-and-conquer`](standing-together-against-divide-and-conquer/) | Someone is picking off members of your group one at a time, rewarding early defectors, punishing holdouts |
| 5 | [`fighting-a-lie-that-gets-repeated-into-truth`](fighting-a-lie-that-gets-repeated-into-truth/) | A confidently-stated falsehood is gaining ground through sheer repetition |
| 6 | [`staying-focused-when-they-flood-the-zone`](staying-focused-when-they-flood-the-zone/) | An opponent is manufacturing a constant stream of outrages and distractions |
| 7 | [`handling-strategic-insults-and-mockery`](handling-strategic-insults-and-mockery/) | You or your group is being branded, ridiculed, or attacked in calculated personal terms |
| 8 | [`seeing-through-a-leaders-grandiose-armor`](seeing-through-a-leaders-grandiose-armor/) | You're dealing with a leader whose self-presentation feels like overcompensation, and you need to know what kind of criticism actually lands |
| 9 | [`predicting-who-the-leader-keeps-drops-and-attacks`](predicting-who-the-leader-keeps-drops-and-attacks/) | You're trying to predict who the leader will retain, rehabilitate, discard, or attack |

## How the skills map to the book's ten chapters

| Book chapter | Corresponds to skill(s) |
|---|---|
| Ch. 1: Hub-and-Spokes | #1 |
| Ch. 2: Art of Trump's Deal | #2 |
| Ch. 3: Divide and Conquer | #4 |
| Ch. 4: How Trump Makes Money | #3 |
| Ch. 5: Behind Closed Doors | cross-cutting — material distributed across #1, #5, #7, #9 |
| Ch. 6: Wall of Sound | #6 |
| Ch. 7: Winners and Losers | #9 (primary) + #8 (class-for-the-masses) |
| Ch. 8: Sleeper Effect | #5 |
| Ch. 9: Sultan of Insult | #7 |
| Ch. 10: Donald the Great | #8 |

The book organizes by attacker tactic (the "commandments"); these skills reorganize by
defender situation. Ch. 5 (private charm, fluidity of relationships) is mostly context and gets
distributed rather than becoming its own skill.

## Why nine skills, not ten

The book has ten chapters, but problem-centric distillation doesn't map one-to-one. Chapter 5
is mostly relational context that strengthens the other skills rather than a standalone problem
class. Chapters 7 and 10 are closely linked (winner-sort and grandeur are related mechanisms of
the same self-concept) but produce two distinct user-situations (predicting sort decisions vs.
reading self-presentation), so they're separate skills.

A single "Trump-leadership skill" would violate three rules of the distill-to-skill framework at
once: operator overload (80+ operators), persona-wrapper (name after person), and
problem-centric-naming (no single problem class). Multiple narrow skills is the right shape.

## Each skill's structure

```
<skill-name>/
├── SKILL.md                     ← runtime artifact loaded by Claude, 1,400–2,000 words
├── OPERATORS.md                 ← author-time operator index with chapter + academic lineage
└── references/
    ├── source-notes.md          ← full academic lineage (Hovland-Weiss, Fisher-Ury, etc.) + bias caveats
    ├── rejected-candidates.md   ← what was cut and why
    └── cases.md                 ← longer-form cases cited inline, each with "decision effect for a user"
```

Every operator in every skill follows the same shape:
- **Plain English:** one sentence describing what it is, no jargon
- **Source:** book chapter + underlying academic/historical concept
- **Detect:** observable signals
- **Intent behind it:** what the attacker is trying to achieve
- **Counter-move:** what the defender does
- **Do not use when:** scope boundary

## Source caveats (important)

**This is not a primary source.** The book is Jeffrey Sonnenfeld's interpretation of Donald
Trump, not Trump's own writing. Sonnenfeld discloses:
- A 25-year personal relationship with Trump spanning friendship, advisory engagement, and
  opposition.
- Direct involvement in catalyzing collective CEO responses (2017 post-Charlottesville
  resignations, 2020 Business Leaders for National Unity).
- A generally adversarial current stance toward Trump's second-term conduct.

The skills abstract the patterns from the specific person to generic dominance-seeking-leader
behavior. Operators are marked **`is_primary_source: false`** with noted bias and
time-boundedness caveats. Users should treat cases as illustrations of mechanism rather than
definitive adjudications of specific political disputes.

## Institutional lineage across the skills

The academic and historical sources most frequently drawn on:

- **Alfred Chandler** (*Strategy and Structure*, 1962) and **Larry Greiner** ("Evolution and
  Revolution as Organizations Grow," 1972) — organizational forms.
- **Sonnenfeld's own *The Hero's Farewell*** (1988) — CEO typology, heroic-identity vs.
  heroic-mission.
- **Roger Fisher and William Ury** (*Getting to Yes*, 1981) — principled negotiation, the foil
  shock-opening style rejects.
- **Carl Hovland and Walter Weiss** (*Public Opinion Quarterly*, 1951) — the sleeper effect.
- **Herbert Simon** (*Sciences of the Artificial*, 1969) — the attention economy.
- **Arthur Schlesinger Jr.** (*The Imperial Presidency*, 1973) — constitutional-constraint erosion.
- **Leo Braudy** (*The Frenzy of Renown*, 1986) — fame as insatiable, stage-requires-renewal.
- **Joseph Campbell** (*The Hero with a Thousand Faces*, 1949) — monomyth, messianic framing.
- **Thorstein Veblen** (*The Theory of the Leisure Class*, 1899) — aspirational imitation of
  success.
- **Jonathan Swift** (*Gulliver's Travels*, 1726) — the Lilliputians binding Gulliver, Trump's
  framing of coalition resistance.
- **Kurt Lewin** (MIT, 1940s) — field theory, group dynamics under external pressure.
- **Herbert Kelman** (Harvard, 1970s onward) — interactive problem-solving, enlarging the
  scope of conflict for constructive resolution.
- **Machiavelli** (*The Prince*, 1513) — implicit master-text for power-based retention
  calculus.
- **Clausewitz** (*On War*, 1832) and the Realpolitik tradition — strategic-interest-based
  alliances.
- **Merrill Flood & Melvin Dresher** (RAND, 1950) and **Robert Axelrod** (*Evolution of
  Cooperation*, 1984) — prisoner's dilemma formalized and iterated.

Specific non-academic cultural sources cited:
- **Phil Spector's Wall of Sound** (1960s music production)
- **Insult-comedian lineage** (Don Rickles, Joan Rivers, Andrew Dice Clay, Jackie Mason, Howard
  Stern, Ted Turner)
- **P. T. Barnum** — "there's no such thing as bad publicity"
- **Roy Cohn** (1927–1986) — Trump's early mentor and fixer
- **Shelley's Ozymandias** (1818) — the cautionary coda

## Using these skills

When a user's situation maps to one of these nine triggers, load the corresponding SKILL.md.
Each skill ends with a required response structure:

1. **Judgment** — does this skill apply? Which operators are active?
2. **What Would Change My Mind** — what conditions would reverse the diagnosis?
3. **Next Action** — concrete move.

Multiple skills often apply to one situation (e.g., a user working under a centralizing boss
who is also grandiose will benefit from #1 and #8 together). The skills are designed to compose.

## Version and credits

Produced using the `distill-to-skill` framework (v0.2).

Primary source: Sonnenfeld, Jeffrey, and Steven Tian. *Trump's Ten Commandments: Strategic
Lessons from the Trump Leadership Toolbox*. 2025.
