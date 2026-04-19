# Source Notes

## Primary source

**Sonnenfeld & Tian, *Trump's Ten Commandments* (2025), Chapter 4** ("How Trump Makes Money: The
Art of Stealing the Deal"). Brief supplementary material from Ch. 2 (Mar-a-Lago, Winery cases).

## Source caveats

`is_primary_source: false` — Sonnenfeld's reading of Trump's business model, informed by decades
of reporting by others (Mary Trump's 2018 *NYT* leak, Timothy O'Brien's biographical work, Bethany
McLean's reporting for *Business Insider*).

Be careful with:
- **The rags-to-riches vs. heir narrative.** Sonnenfeld sides firmly with the "Trump was handed
  his money" reading, citing the 2018 *NYT* investigation. This is well-documented but politically
  contested. The operators in this skill do not depend on which narrative is correct — they are
  patterns of deal structure regardless of initial capital source.
- **The second-term political/business blur.** The chapter's last third covers crypto ventures,
  Qatar 747, pay-for-access clubs, and emoluments concerns. These are politically loaded. The
  underlying pattern — mixing personal financial interest with official role — is captured in
  skill #1's `hub-and-spokes-detection`, not here. This skill sticks to deal-structural patterns
  that apply regardless of whether one party is a government official.

## Academic and historical lineage per operator

### `heads-I-win-tails-you-lose structure detection`

- **Robert H. Frank and Philip J. Cook**, *The Winner-Take-All Society: Why the Few at the Top Get
  So Much More Than the Rest of Us* (Free Press, 1995). Analyzed how small performance differences
  in lotteries, sports, entertainment, and professional services yield enormous income gaps.
  Sonnenfeld invokes Frank & Cook for the ambient economic context — the "superstar clears the
  deck" dynamic.
- **Sun Tzu**, *The Art of War* (5th century BCE), "Leave your adversary a dignified path for
  retreat." Sonnenfeld frames Trump's approach as the diametric opposite: leave nothing on the
  table, take the other side's furniture.

### `buy-distressed-from-desperate-sellers`

- No formal academic lineage. This is a staple of real estate and distressed-debt investing;
  Sonnenfeld presents it as Trump's signature move.

### `other-peoples-money-default` (OPM)

- Background from the **leveraged buyout (LBO) literature of the 1980s** — KKR, Drexel Burnham,
  Michael Milken's junk-bond revolution. The term "OPM" is investor slang from this era. Trump was
  a participant in 1980s greenmailing (Quaker Oats 1986, Holiday Inn 1987, American Airlines 1989)
  before his Atlantic City overextension.
- Sonnenfeld cites **Saul Steinberg, Robert Maxwell, Boone Pickens** as parallel 1980s tycoons who
  over-leveraged spectacularly.

### `internecine-creditor-warfare`

- No single academic source. The structural logic maps to **divide-and-conquer** (covered in skill
  #4) applied to financial counterparties. Also relates to **game theory's prisoner's dilemma** as
  formalized by Merrill Flood & Melvin Dresher (RAND, 1950).

### `overleverage-as-failure-mode`

- **Hyman Minsky**, *Stabilizing an Unstable Economy* (1986) — the financial instability hypothesis:
  prolonged stability breeds risk-taking that eventually produces instability. Trump's 1990
  liquidity crisis is a personal-scale Minsky moment.

### `brand-licensing-pure-upside`

- No formal academic source. The late-career Trump business model is the exemplar. Parallel
  structures: celebrity fragrance lines, athlete equity for endorsement deals, author licensing
  of novel series to co-authors.

## Cross-references

- Skill #1 (`dealing-with-a-centralizing-boss`) — cash-flow signals (shell LLCs, related-party
  transactions) are folded into `hub-and-spokes-detection` there. This skill covers the deal-level
  structure.
- Skill #2 (`when-a-negotiation-opens-with-a-punch`) — shock-opener tactics used to secure favorable
  terms, especially `leverage-by-adjacent-assets` (how the buyer becomes the only bidder).
