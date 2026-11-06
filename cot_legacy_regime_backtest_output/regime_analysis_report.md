# COT Regime Score Backtest Report

Generated: 2026-11-06T23:48:04Z

This report is regenerated from the same current Legacy COT inputs used by the dashboard. COT observations are Tuesday report dates; signals start at the first available close on or after Friday publication.

## Data Cutoffs

| Market | Latest COT report | Latest signal close | Latest price | Scored rows |
| --- | --- | --- | --- | --- |
| S&P 500 | 2026-11-03 | 2026-11-06 | 2026-11-06 | 441 |
| NASDAQ-100 | 2026-11-03 | 2026-11-06 | 2026-11-06 | 463 |
| VIX Futures | 2026-11-03 | 2026-11-06 | 2026-11-06 | 463 |
| Russell 2000 | 2026-11-03 | 2026-11-06 | 2026-11-06 | 145 |
| Dow Jones | 2026-11-03 | 2026-11-06 | 2026-11-06 | 463 |
| Gold | 2026-11-03 | 2026-11-06 | 2026-11-06 | 463 |

## Current Tradable COT Signals

| Market | Report date | Signal date | Score | Bucket | Active triggers |
| --- | --- | --- | --- | --- | --- |
| S&P 500 | 2026-11-03 | 2026-11-06 | -1.00 | Mixed | nonreportable 96.3% -1.00 Non-reportable contrarian (retail long) |
| NASDAQ-100 | 2026-11-03 | 2026-11-06 | -1.00 | Mixed | nonreportable 97.7% -1.00 Non-reportable contrarian (retail long) |
| VIX Futures | 2026-11-03 | 2026-11-06 | +0.00 | Mixed | No active extreme trigger |
| Russell 2000 | 2026-11-03 | 2026-11-06 | +0.00 | Mixed | No active extreme trigger |
| Dow Jones | 2026-11-03 | 2026-11-06 | +0.00 | Mixed | No active extreme trigger |
| Gold | 2026-11-03 | 2026-11-06 | +0.00 | Mixed | No active extreme trigger |

## Forward Returns by Regime Bucket

| Market | Horizon | Bucket | N | Average return | Hit rate | Average drawdown |
| --- | --- | --- | --- | --- | --- | --- |
| S&P 500 | 4w | Mixed | 323 | +1.03% | 68.7% | -2.76% |
| S&P 500 | 4w | Caution | 21 | -0.35% | 61.9% | -3.66% |
| S&P 500 | 4w | Risk-On | 93 | +1.61% | 68.8% | -2.65% |
| S&P 500 | 13w | Mixed | 313 | +4.09% | 77.6% | -5.18% |
| S&P 500 | 13w | Caution | 21 | -3.58% | 23.8% | -9.41% |
| S&P 500 | 13w | Risk-On | 93 | +3.27% | 71.0% | -4.59% |
| S&P 500 | 26w | Mixed | 301 | +7.78% | 77.1% | -7.65% |
| S&P 500 | 26w | Caution | 21 | -3.71% | 28.6% | -15.81% |
| S&P 500 | 26w | Risk-On | 92 | +8.07% | 84.8% | -5.69% |
| NASDAQ-100 | 4w | Mixed | 407 | +1.44% | 63.6% | -3.59% |
| NASDAQ-100 | 4w | Risk-On | 52 | +2.30% | 71.2% | -2.81% |
| NASDAQ-100 | 13w | Mixed | 398 | +4.69% | 69.3% | -6.53% |
| NASDAQ-100 | 13w | Risk-On | 51 | +7.93% | 96.1% | -4.32% |
| NASDAQ-100 | 26w | Mixed | 389 | +10.26% | 76.9% | -8.93% |
| NASDAQ-100 | 26w | Risk-On | 47 | +12.12% | 89.4% | -4.44% |
| VIX Futures | 4w | Mixed | 459 | +6.41% | 50.5% | -12.98% |
| VIX Futures | 13w | Mixed | 450 | +10.06% | 46.7% | -19.62% |
| VIX Futures | 26w | Mixed | 436 | +9.80% | 46.6% | -23.48% |
| Russell 2000 | 4w | Mixed | 141 | +1.21% | 60.3% | -3.19% |
| Russell 2000 | 13w | Mixed | 131 | +4.09% | 71.8% | -5.58% |
| Russell 2000 | 26w | Mixed | 118 | +8.83% | 79.7% | -7.78% |
| Dow Jones | 4w | Mixed | 459 | +0.74% | 64.3% | -2.76% |
| Dow Jones | 13w | Mixed | 449 | +2.46% | 67.5% | -5.09% |
| Dow Jones | 26w | Mixed | 436 | +5.10% | 74.3% | -7.30% |
| Gold | 4w | Mixed | 459 | +1.10% | 56.6% | -2.38% |
| Gold | 13w | Mixed | 449 | +3.87% | 66.4% | -3.81% |
| Gold | 26w | Mixed | 436 | +8.25% | 73.2% | -4.87% |

## Predictivity Diagnostics

| Market | Horizon | N | Score/return r | HAC p | Risk-On minus Caution | Edge HAC p | Drift-adjusted accuracy | Evidence |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| S&P 500 | 4w | 437 | +0.092 | 0.191 | +1.96% | 0.137 | 53.1% | Unclear |
| S&P 500 | 13w | 427 | +0.104 | 0.359 | +6.86% | 0.003 | 55.8% | Supported |
| S&P 500 | 26w | 414 | +0.138 | 0.269 | +11.78% | 0.002 | 55.8% | Supported |
| NASDAQ-100 | 4w | 459 | +0.028 | 0.592 | n/a | n/a | 53.5% | Insufficient |
| NASDAQ-100 | 13w | 449 | +0.069 | 0.282 | n/a | n/a | 54.2% | Insufficient |
| NASDAQ-100 | 26w | 436 | -0.016 | 0.826 | n/a | n/a | 52.6% | Insufficient |
| VIX Futures | 4w | 459 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| VIX Futures | 13w | 450 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| VIX Futures | 26w | 436 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 4w | 141 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 13w | 131 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 26w | 118 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 4w | 459 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 13w | 449 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 26w | 436 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Gold | 4w | 459 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Gold | 13w | 449 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Gold | 26w | 436 | n/a | n/a | n/a | n/a | n/a | Insufficient |

## Interpretation

- Risk-On means the configured COT extremes historically aligned with better forward reward/risk; it is not a guaranteed long signal.
- Caution is primarily an exposure and position-sizing warning, not an automatic short.
- Mixed means the active COT extremes conflict or lack enough conviction for a directional call.
- The backtest is COT-only. Price, volatility, and the unified macro-liquidity score are excluded from the regime score.
- `Supported` requires a positive Risk-On-minus-Caution edge with an overlap-adjusted HAC p-value at or below 0.05 and at least 20 observations in the smaller directional bucket.
- Drift-adjusted accuracy asks whether the score sign predicted a return above or below the prior expanding average, rather than rewarding the model for the equity market's long-run positive drift.

## Caveats

1. The expanding-percentile warmup requires at least 104 prior weekly reports.
2. Equity-index drift can keep average returns positive even in Caution buckets.
3. Long-horizon observations overlap. The main evidence table therefore uses Newey-West HAC statistics with lags tied to the forecast horizon; conventional permutation and Welch statistics remain in the CSV only as secondary diagnostics.
4. Publication timing is approximated using the first available market close on or after Friday release.
5. Latest rows may lack longer-horizon returns until enough future price history exists.
6. Percentile ranks are walk-forward, but the rule thresholds and weights are fixed researcher choices rather than rules selected in a sealed out-of-sample training process.
