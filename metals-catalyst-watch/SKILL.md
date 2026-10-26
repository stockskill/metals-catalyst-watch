---
name: metals-catalyst-watch
description: Research current catalysts for gold, silver, copper, and palladium using primary market and macro sources plus liquid U.S. ETF proxies. Use for a short Catalyst Card, linked Deep Scan, or weekly/monthly metals roundup. Verify macro, ETF flows, futures structure, COT positioning, exchange stocks, physical supply/demand, and policy risks; label a research state as Buy, Conditional Buy, Neutral, or Avoid and distinguish facts from inference.
---

# Metals Catalyst Watch

Create evidence-led research for gold, silver, copper, and palladium. The output is a research signal, never a trade instruction or personalised investment advice.

## Sources and scope

Read `references/metal-universe.md` and `references/data-quality.md` before researching. Read `references/catalyst-rubric.md` before assigning a signal.

Use this order of evidence:

1. Official institutions and exchange data: Federal Reserve, CFTC, CME/COMEX, LME, LBMA, WGC, WPIC, ICSG, IEA.
2. Company or fund filings for ETF mechanics.
3. Reputable reporting only to add context where primary data is unavailable.

Treat GLD, SLV, CPER, and PALL as liquid U.S. trading proxies, not as interchangeable spot prices. State the quote date, market, and instrument.

## Workflow

1. Set the requested horizon; use one to four weeks for a Catalyst Card unless the user asks for weekly or monthly context.
2. Capture a timestamped price snapshot and identify the relevant catalyst window.
3. Check macro drivers: US dollar, real yields, the next Fed decision, inflation, and risk appetite.
4. Check metal-specific demand/supply, ETF flows, futures curve, COT positioning, warehouse stocks, and material policy or mining disruptions.
5. Compare the facts against the prior expectation. Do not promote a known narrative to a catalyst without new evidence.
6. Assign a research state using the rubric. Specify the catalyst required to upgrade/downgrade it and an invalidation condition.

## Signal discipline

Use exactly one of these labels:

- **Buy:** multiple independent positive confirmations and a defined, favourable risk/reward entry context.
- **Conditional Buy:** the structural thesis is positive, but a named macro, flow, or price-structure condition must confirm before a new position is justified. Until then, it is Watch / no new position.
- **Neutral:** evidence is mixed, incomplete, or already reflected in price.
- **Avoid:** downside drivers dominate or risk/reward is unfavourable. Use **Sell research state** only where a clearly evidenced negative catalyst supports it; never present it as an execution command.

For a Conditional Buy, name both the confirmation and the invalidation. Example: gold may require stable-to-lower real yields and continuing ETF inflows; invalidate the thesis if a stronger dollar and higher real yields coincide with persistent ETF outflows.

## Output

Start with a compact Catalyst Card:

| Field | Content |
|---|---|
| Market / proxy | Metal, relevant spot or futures market, and ETF proxy where useful |
| Event and primary source | Dated link or source |
| What changed | New fact versus prior expectation |
| Near-term read-through | Likely direction and confidence, not certainty |
| Research state | Buy / Conditional Buy / Neutral / Avoid |
| Bull / bear case | One concise evidence-based interpretation each |
| Liquidity / dilution / vehicle risk | ETF structure, futures leverage, roll, or liquidity caveat |
| Confirmation and invalidation | Observable conditions |

Then include a clickable `[Részletes Deep Scan](#deep-scan)` link and the `## Deep Scan` section. A Deep Scan must cover only available, dated data: price and relative strength; macro; ETF flows; futures curve and COT; inventories; physical balance; policy/supply shocks; and the final conditional thesis. Mark unavailable data explicitly rather than estimating it.

## Data integrity rules

- Identify the observation date. COT is a weekly, lagged positioning report; state its report date and participant category.
- Calculate managed-money net positioning as long contracts minus short contracts only when both figures use the same CFTC report.
- Label curve structure only when contracts and timestamps are comparable. Do not infer contango or backwardation from unrelated quotes.
- Identify exchange stock category and date. LME/COMEX inventory is not a global supply balance.
- Separate verifiable fact, market interpretation, and unknown. Cite primary sources close to the claim.
