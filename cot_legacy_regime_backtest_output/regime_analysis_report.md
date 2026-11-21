# COT Regime Score Backtest Report

Generated: 2026-11-21T00:56:26Z

This report is regenerated from the same current Legacy COT inputs used by the dashboard. COT observations are Tuesday report dates; signals start at the first available close on or after Friday publication.

## Data Cutoffs

| Market | Latest COT report | Latest signal close | Latest price | Scored rows |
| --- | --- | --- | --- | --- |
| S&P 500 | 2026-11-17 | 2026-11-20 | 2026-11-20 | 443 |
| NASDAQ-100 | 2026-11-17 | 2026-11-20 | 2026-11-20 | 465 |
| VIX Futures | 2026-11-17 | 2026-11-20 | 2026-11-20 | 465 |
| Russell 2000 | 2026-11-17 | 2026-11-20 | 2026-11-20 | 147 |
| Dow Jones | 2026-11-17 | 2026-11-20 | 2026-11-20 | 465 |
| Gold | 2026-11-17 | 2026-11-20 | 2026-11-20 | 465 |

## Current Tradable COT Signals

| Market | Report date | Signal date | Score | Bucket | Active triggers |
| --- | --- | --- | --- | --- | --- |
| S&P 500 | 2026-11-17 | 2026-11-20 | -1.00 | Mixed | nonreportable 92.7% -1.00 Non-reportable contrarian (retail long) |
| NASDAQ-100 | 2026-11-17 | 2026-11-20 | -1.00 | Mixed | nonreportable 99.3% -1.00 Non-reportable contrarian (retail long) |
| VIX Futures | 2026-11-17 | 2026-11-20 | +0.00 | Mixed | No active extreme trigger |
| Russell 2000 | 2026-11-17 | 2026-11-20 | +0.00 | Mixed | No active extreme trigger |
| Dow Jones | 2026-11-17 | 2026-11-20 | +0.00 | Mixed | No active extreme trigger |
| Gold | 2026-11-17 | 2026-11-20 | +0.00 | Mixed | No active extreme trigger |

## Forward Returns by Regime Bucket

| Market | Horizon | Bucket | N | Average return | Hit rate | Average drawdown |
| --- | --- | --- | --- | --- | --- | --- |
| S&P 500 | 4w | Mixed | 325 | +0.99% | 68.3% | -2.79% |
| S&P 500 | 4w | Caution | 21 | -0.35% | 61.9% | -3.66% |
| S&P 500 | 4w | Risk-On | 93 | +1.61% | 68.8% | -2.65% |
| S&P 500 | 13w | Mixed | 315 | +4.04% | 77.1% | -5.18% |
| S&P 500 | 13w | Caution | 21 | -3.58% | 23.8% | -9.41% |
| S&P 500 | 13w | Risk-On | 93 | +3.27% | 71.0% | -4.59% |
| S&P 500 | 26w | Mixed | 303 | +7.73% | 76.9% | -7.62% |
| S&P 500 | 26w | Caution | 21 | -3.71% | 28.6% | -15.81% |
| S&P 500 | 26w | Risk-On | 92 | +8.07% | 84.8% | -5.69% |
| NASDAQ-100 | 4w | Mixed | 409 | +1.39% | 63.3% | -3.63% |
| NASDAQ-100 | 4w | Risk-On | 52 | +2.30% | 71.2% | -2.81% |
| NASDAQ-100 | 13w | Mixed | 399 | +4.65% | 69.2% | -6.54% |
| NASDAQ-100 | 13w | Risk-On | 52 | +7.66% | 94.2% | -4.43% |
| NASDAQ-100 | 26w | Mixed | 390 | +10.23% | 76.7% | -8.93% |
| NASDAQ-100 | 26w | Risk-On | 48 | +11.68% | 87.5% | -4.54% |
| VIX Futures | 4w | Mixed | 461 | +6.56% | 50.5% | -12.99% |
| VIX Futures | 13w | Mixed | 452 | +10.40% | 46.9% | -19.55% |
| VIX Futures | 26w | Mixed | 438 | +9.85% | 46.8% | -23.46% |
| Russell 2000 | 4w | Mixed | 143 | +1.16% | 60.1% | -3.19% |
| Russell 2000 | 13w | Mixed | 133 | +3.90% | 70.7% | -5.66% |
| Russell 2000 | 26w | Mixed | 120 | +8.62% | 78.3% | -7.74% |
| Dow Jones | 4w | Mixed | 461 | +0.72% | 64.2% | -2.77% |
| Dow Jones | 13w | Mixed | 451 | +2.43% | 67.2% | -5.09% |
| Dow Jones | 26w | Mixed | 438 | +5.09% | 74.2% | -7.27% |
| Gold | 4w | Mixed | 461 | +1.05% | 56.4% | -2.41% |
| Gold | 13w | Mixed | 451 | +3.81% | 66.1% | -3.85% |
| Gold | 26w | Mixed | 438 | +8.12% | 72.8% | -4.93% |

## Predictivity Diagnostics

| Market | Horizon | N | Score/return r | HAC p | Risk-On minus Caution | Edge HAC p | Drift-adjusted accuracy | Evidence |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| S&P 500 | 4w | 439 | +0.097 | 0.169 | +1.96% | 0.137 | 53.5% | Unclear |
| S&P 500 | 13w | 429 | +0.107 | 0.341 | +6.86% | 0.003 | 56.2% | Supported |
| S&P 500 | 26w | 416 | +0.139 | 0.267 | +11.78% | 0.002 | 55.8% | Supported |
| NASDAQ-100 | 4w | 461 | +0.036 | 0.489 | n/a | n/a | 54.0% | Insufficient |
| NASDAQ-100 | 13w | 451 | +0.059 | 0.362 | n/a | n/a | 53.6% | Insufficient |
| NASDAQ-100 | 26w | 438 | -0.022 | 0.762 | n/a | n/a | 52.3% | Insufficient |
| VIX Futures | 4w | 461 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| VIX Futures | 13w | 452 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| VIX Futures | 26w | 438 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 4w | 143 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 13w | 133 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 26w | 120 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 4w | 461 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 13w | 451 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 26w | 438 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Gold | 4w | 461 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Gold | 13w | 451 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Gold | 26w | 438 | n/a | n/a | n/a | n/a | n/a | Insufficient |

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
