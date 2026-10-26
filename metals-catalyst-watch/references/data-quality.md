# Data Quality Rules

## Required labels

| Metric | Minimum label |
|---|---|
| Price | Instrument, venue/proxy, currency, observation time/date |
| Futures curve | Named contracts, same timestamp, price difference and sign |
| COT | CFTC report date, participant category, long, short, net calculation |
| Warehouse stock | Exchange, category where available, date, unit |
| ETF flow | Fund universe, period, tonnes/shares and/or currency flow |

## Interpretation limits

- Do not call a price move causal unless a dated event and credible linkage exist.
- Do not use a single warehouse observation as proof of shortage or surplus.
- Do not treat ETF inflow as proof of immediate price upside; it is one demand signal.
- Do not compare a delayed COT observation with live prices without stating the lag.
- If an options-skew, open-interest, futures curve, or inventory series cannot be verified, write **Unavailable / not verified**.

## Catalyst threshold

Treat an event as material only if it plausibly changes the demand path, supply path, liquidity, policy regime, positioning, or a key market expectation. Routine price moves and recycled commentary are not catalysts.
