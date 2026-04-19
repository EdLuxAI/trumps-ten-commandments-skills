---
name: spotting-deals-where-youre-the-bag-holder
description: |
  Use when the user is evaluating a deal structure — investment, partnership, joint venture,
  contract, sale — and suspects the structure is designed so the other side keeps the upside while
  someone else inherits the downside. Helps identify "heads I win, tails you lose" arrangements
  before the user signs and becomes the bag-holder.
  Triggers on phrases like "this deal looks too good", "they keep insisting I personally guarantee
  it", "I'm one of several creditors and it feels weird", "they're offering their name but no
  capital", "something about this capital structure feels off", "how do I know if I'm the one who'll
  be left holding the bag".
  Do not use for: straightforward commercial deals without exotic structure, deals between parties
  of roughly equal leverage, or pure bargain-hunting advice (use ordinary deal-structuring or
  valuation resources).
---

# Spotting Deals Where You're the Bag-Holder

> *What this skill is about, in one sentence:*
> How to recognize deal structures engineered to extract maximum upside for one party while
> offloading downside risk to counterparties, creditors, partners, or the public — and how to
> spot that pattern *before* you sign.

## Where this comes from

This skill distills Chapter 4 ("How Trump Makes Money: The Art of Stealing the Deal — Heads I Win,
Tails You Lose") of Sonnenfeld & Tian's *Trump's Ten Commandments* (2025). Sonnenfeld's framing
draws on:

- **Robert H. Frank and Philip J. Cook**, *The Winner-Take-All Society* (1995) — how small
  performance differences produce enormous differences in rewards; how "superstar" structures
  clear the deck.
- **Sun Tzu**, *The Art of War* (5th century BCE) — "leave your adversary a dignified path for
  retreat." Sonnenfeld frames Trump's approach as the inverse: leave nothing on the table, take
  the opponent's furniture too.
- **Oliver Williamson's transaction cost economics** (1975 onward) — provides the theoretical
  backing for why opaque related-party structures can hide real economic flows. Not explicitly
  cited by Sonnenfeld but useful background.

Primary source status: `false` — the book is interpretive commentary on Trump's real-estate and
post-real-estate deals. Operators generalize to any deal structure engineered by a counterparty
who plans to retain optionality for themselves while eliminating yours.

## North Star

> *Does this operator change what the user does before signing?*

If an operator only helps the user understand how the counterparty makes money in the abstract, but
doesn't change due diligence, deal structure, covenants, walk-away criteria, or personal liability
decisions — cut it.

## Opening Gate: is this a heads-I-win-tails-you-lose structure?

Three threshold tests:

- **Asymmetric capital exposure.** Is the counterparty putting down significantly less capital than
  you, proportional to what each side stands to gain?
- **Asymmetric downside.** If the deal fails, who is left with the losses? If the answer is not
  roughly proportional to the upside split, this is a candidate.
- **Opacity.** Are there entities in the structure whose purpose you cannot clearly articulate
  (shell LLCs, related-party service companies, off-balance-sheet partners)?

If any two of three tests flag, apply this skill. If none do, the deal may be aggressive but not
structurally engineered against you; use ordinary deal evaluation.

## The Operators

### 1. `heads-I-win-tails-you-lose structure detection`

**Plain English:** The master pattern. The deal is engineered so that if things go well, the
counterparty captures the upside; if things go badly, someone else (you, creditors, employees,
taxpayers) absorbs the losses.

**Source:** Sonnenfeld & Tian, Ch. 4. Signature cases: the Commodore Hotel / Grand Hyatt
transaction (1976) where NYC's Urban Development Corporation bought the property outright, gave
Trump a 99-year lease, and granted an unprecedented 40-year property tax exemption; Atlantic
City bankruptcies where Trump personally walked away from $1B+ in losses borne by investors,
creditors, suppliers, and employees.

**Detect:**
- The counterparty's personal capital at risk is small relative to the total deal size.
- Tax abatements, subsidies, or public-sector participation are essential to the deal math but
  disproportionately benefit one party.
- The ownership structure is a long-term lease, license, or option rather than outright purchase.
- Operating upside flows to one party; maintenance and failure risk flows to another.

**Counter-move:**
- Before signing, write a one-page summary: "If this deal fails, who is left holding what?"
- Require symmetric exposure. If they are not personally at risk in a failure scenario, you are
  likely taking the risk they're avoiding.
- Beware deals where you are asked to personally guarantee something the counterparty will not.

**Do not use when:** the asymmetry is transparent and compensated (e.g., operating partner takes
smaller equity but no downside; capital partner takes larger equity and all downside — a normal
structure).

### 2. `buy-distressed-from-desperate-sellers`

**Plain English:** The counterparty targets sellers under acute financial or personal pressure —
bankruptcy, divorce, liquidity crunch, reputational crisis — where walking away means losing
everything. The price offered is well below fair value, anchored by the seller's desperation rather
than the asset.

**Source:** Sonnenfeld & Tian, Ch. 4 (and echoed in Ch. 2). Cases: Mar-a-Lago (Carter-administration
refusal, disenchanted descendants); Trump Winery (bankrupt Kluge); Trump National Doral (Great
Recession distressed sale); Commodore Hotel (Penn Central bankruptcy).

**Detect:**
- You are in financial or reputational distress and a potential buyer is approaching you.
- The offer is anchored to your situation, not the asset's value.
- The buyer is leveraging adjacency, timing pressure, or political connection to ensure they are
  effectively the only bidder.

**Counter-move:**
- **If you are the seller** (the most decision-critical side): the single highest-leverage move is
  to create a second bidder, even a weak one. Once there are two interested parties, the price
  anchors to market rather than to your distress.
- Buy yourself time before selling. A week to shop the asset is worth more than a polished pitch.
- Refuse to negotiate against yourself. "If this is your best offer, I'll consider it by Friday"
  is a full reply.

**Do not use when:** you genuinely have no alternative — in which case the counter-move shifts from
"create a second bidder" to "minimize the damage by negotiating specific terms rather than the
headline price."

### 3. `other-peoples-money-default` (OPM)

**Plain English:** The counterparty reflexively structures deals to use other people's capital — yours,
lenders', the public's — rather than their own. Their personal exposure is minimized at every
stage.

**Source:** Sonnenfeld & Tian, Ch. 4. The Commodore deal again — Trump's father guaranteed a $70M
construction loan; Hyatt became the operating partner; Trump personally put down almost nothing.
Trump Shuttle, Trump Princess, USFL's New Jersey Generals similarly structured.

**Detect:**
- The counterparty's own cash or equity contribution is small relative to the deal.
- Lenders, partners, or guarantors are absorbing what looks like the counterparty's risk.
- The counterparty pushes back hard on any structure that would require their own capital.

**Counter-move:**
- If you are being asked to provide the capital: insist that the counterparty has meaningful skin
  in the game. "Meaningful" = material relative to their own net worth, not relative to the deal.
- If they refuse to put in capital, insist on operational controls that let you protect your
  investment if things deteriorate (board seats, financial covenants, trigger clauses).
- If they offer their name/brand in lieu of capital, treat it as a separate transaction and price
  it separately — don't let them blur brand-value into equity-value.

**Do not use when:** OPM is the explicit agreed structure (e.g., a fund deploying LP capital — the
GP is supposed to deploy other people's money, that's the job).

### 4. `internecine-creditor-warfare`

**Plain English:** When a deal starts to fail, the counterparty brings in new layers of investors
or creditors with conflicting priorities. Existing creditors end up fighting the new ones —
fighting each other rather than fighting the counterparty, who becomes the arbiter instead of the
defendant.

**Source:** Sonnenfeld & Tian, Ch. 4. The Atlantic City casino bankruptcies: Trump issued $775M of
14% junk bonds despite promising earlier creditors he wouldn't; then took Trump Hotels and Casinos
public; then issued another $155M of 15.5% junk bonds. Much of each round went to pay down Trump's
personal loans rather than into the casinos.

**Detect:**
- You are one of several classes of creditors or investors with conflicting priorities.
- New capital rounds are being raised that dilute or subordinate your position.
- The counterparty is pushing you to agree to concessions while promising similar concessions from
  other creditor classes — who may or may not actually concede.
- Proceeds from new capital rounds are not visibly going into the underlying business.

**Counter-move:**
- Talk to the other creditor classes directly. Divide-and-conquer only works when the targets don't
  coordinate. Coordinated creditors have enormous leverage.
- Before agreeing to any concession, demand transparency on what other classes are actually
  conceding (not what is being promised).
- Track where capital raises are actually being spent. Proceeds diverted to insider-related uses
  (personal loans, affiliated entities) are a major red flag and often legally challengeable.

**Do not use when:** you are the sole creditor or investor — this pattern requires multiple classes
to fire.

### 5. `overleverage-as-failure-mode` (the cautionary operator)

**Plain English:** Even the master of "heads I win, tails you lose" can overleverage themselves
into genuine failure. When a shock-opener goes from using other people's money to personally
guaranteeing debt, they have become the bag-holder. A warning to recognize in others and avoid in
yourself.

**Source:** Sonnenfeld & Tian, Ch. 4. Trump by 1990 had amassed ~$4B in debt, ~$1B personally
guaranteed. His father had to send a crony to buy $3M of casino chips as a disguised emergency gift
to help Trump meet an interest payment. The 1990s financial scars never fully healed.

**Detect (about a counterparty):**
- Debt load has grown faster than cash flow for multiple years.
- Personal guarantees are expanding, not contracting.
- Counterparty is showing signs of liquidity pressure despite being "wealthy on paper."

**Detect (about yourself):**
- Your own deals have become increasingly dependent on new debt to service prior debt.
- You are personally guaranteeing deals you used to structure without personal exposure.
- You are spending time firefighting rather than originating.

**Counter-move:**
- **About a counterparty showing this pattern:** their bluster is less credible than it looks;
  they need the deal more than they're letting on. Patience is a weapon.
- **About yourself:** stop. Personal guarantees are the bag. Reduce exposure, refinance into
  non-recourse structures, sell non-core assets. Do not take on new personal risk until the
  existing stack is manageable.

**Do not use when:** apparent over-leverage is a temporary expansion phase with a credible
deleveraging plan tied to a specific liquidity event.

### 6. `brand-licensing-pure-upside`

**Plain English:** Once a brand is established, the highest-margin monetization is pure licensing —
lending your name to deals you don't capitalize, don't operate, and don't bear risk for, in
exchange for a royalty or fee. The licensor captures upside without downside.

**Source:** Sonnenfeld & Tian, Ch. 4. Post-*Apprentice*, Trump's income shifted decisively from
real-estate operating income to brand licensing: Trump Steaks, Trump Vodka, Trump Ice, Trump
Menswear, Trump Watches, Trump fragrances, Trump Mortgage, Trump University, Trump sneakers, Trump
coins, Trump guitars, Trump meme coins, Trump NFTs, Trump Mobile, Trump Bibles.

**Detect (about a counterparty):**
- They are offering brand association rather than capital or operational involvement.
- Their compensation is a royalty or fee, payable regardless of project performance.
- They will not personally guarantee anything; they keep the upside, you keep the downside.

**Detect (about yourself, as the operator):**
- You are being pitched on "leveraging a famous partner's brand" in a deal where the brand partner
  has no capital at risk.

**Counter-move:**
- **If you are considering licensing someone's brand:** treat the royalty as a pure cost. The brand
  partner will not share your downside. Model the deal assuming zero brand uplift, and only
  accept the licensing cost if the deal works on its own economics.
- **If you are considering licensing your brand:** the structure is legitimately upside-only for
  you. The risk is reputational — your brand rides on the operator's performance, which you don't
  control.

**Do not use when:** brand licensing is a normal commercial arrangement with disclosed terms and
both sides accept the asymmetry. This operator is about recognizing when the asymmetry is hidden
or misrepresented.

## Final-answer structure

### Judgment
- Is this a "heads I win, tails you lose" structure? Which of the three gates flagged?
- Which operators are load-bearing for this specific deal?

### What Would Change My Mind
- What disclosure would convert the opacity into normal commercial practice?
- What structural change would make the exposure symmetric?

### Next Action
- Concrete: do X before signing; renegotiate Y; walk if Z.

## References

- `references/source-notes.md` — Ch. 4 material, Frank/Cook, Sun Tzu, Williamson
- `references/rejected-candidates.md` — what was cut
- `references/cases.md` — Commodore Hotel, Mar-a-Lago, Atlantic City bankruptcies, Wollman Rink,
  brand-licensing catalog, Trump University
