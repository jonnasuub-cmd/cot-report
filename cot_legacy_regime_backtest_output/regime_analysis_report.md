# COT Regime Score Backtest Report

Generated: 2026-09-25T22:43:51Z

This report is regenerated from the same current Legacy COT inputs used by the dashboard. COT observations are Tuesday report dates; signals start at the first available close on or after Friday publication.

## Data Cutoffs

| Market | Latest COT report | Latest signal close | Latest price | Scored rows |
| --- | --- | --- | --- | --- |
| S&P 500 | 2026-09-22 | 2026-09-25 | 2026-09-25 | 435 |
| NASDAQ-100 | 2026-09-22 | 2026-09-25 | 2026-09-25 | 457 |
| VIX Futures | 2026-09-22 | 2026-09-25 | 2026-09-25 | 457 |
| Russell 2000 | 2026-09-22 | 2026-09-25 | 2026-09-25 | 139 |
| Dow Jones | 2026-09-22 | 2026-09-25 | 2026-09-25 | 457 |
| Gold | 2026-09-22 | 2026-09-25 | 2026-09-25 | 457 |

## Current Tradable COT Signals

| Market | Report date | Signal date | Score | Bucket | Active triggers |
| --- | --- | --- | --- | --- | --- |
| S&P 500 | 2026-09-22 | 2026-09-25 | -1.00 | Mixed | nonreportable 92.2% -1.00 Non-reportable contrarian (retail long) |
| NASDAQ-100 | 2026-09-22 | 2026-09-25 | +0.00 | Mixed | No active extreme trigger |
| VIX Futures | 2026-09-22 | 2026-09-25 | +0.00 | Mixed | No active extreme trigger |
| Russell 2000 | 2026-09-22 | 2026-09-25 | +0.00 | Mixed | No active extreme trigger |
| Dow Jones | 2026-09-22 | 2026-09-25 | +0.00 | Mixed | No active extreme trigger |
| Gold | 2026-09-22 | 2026-09-25 | +0.00 | Mixed | No active extreme trigger |

## Forward Returns by Regime Bucket

| Market | Horizon | Bucket | N | Average return | Hit rate | Average drawdown |
| --- | --- | --- | --- | --- | --- | --- |
| S&P 500 | 4w | Mixed | 316 | +1.07% | 69.3% | -2.78% |
| S&P 500 | 4w | Caution | 21 | -0.35% | 61.9% | -3.66% |
| S&P 500 | 4w | Risk-On | 93 | +1.61% | 68.8% | -2.65% |
| S&P 500 | 13w | Mixed | 307 | +4.11% | 77.2% | -5.24% |
| S&P 500 | 13w | Caution | 21 | -3.58% | 23.8% | -9.41% |
| S&P 500 | 13w | Risk-On | 93 | +3.27% | 71.0% | -4.59% |
| S&P 500 | 26w | Mixed | 295 | +7.70% | 76.6% | -7.80% |
| S&P 500 | 26w | Caution | 21 | -3.71% | 28.6% | -15.81% |
| S&P 500 | 26w | Risk-On | 92 | +8.07% | 84.8% | -5.69% |
| NASDAQ-100 | 4w | Mixed | 400 | +1.50% | 64.0% | -3.57% |
| NASDAQ-100 | 4w | Risk-On | 52 | +2.30% | 71.2% | -2.81% |
| NASDAQ-100 | 13w | Mixed | 393 | +4.71% | 69.2% | -6.55% |
| NASDAQ-100 | 13w | Risk-On | 50 | +7.99% | 96.0% | -4.23% |
| NASDAQ-100 | 26w | Mixed | 383 | +10.18% | 76.8% | -9.05% |
| NASDAQ-100 | 26w | Risk-On | 47 | +12.12% | 89.4% | -4.44% |
| VIX Futures | 4w | Mixed | 453 | +6.14% | 50.1% | -13.11% |
| VIX Futures | 13w | Mixed | 443 | +10.02% | 46.5% | -19.70% |
| VIX Futures | 26w | Mixed | 430 | +10.12% | 46.7% | -23.38% |
| Russell 2000 | 4w | Mixed | 134 | +1.44% | 63.4% | -3.12% |
| Russell 2000 | 13w | Mixed | 125 | +4.57% | 75.2% | -5.51% |
| Russell 2000 | 26w | Mixed | 112 | +9.02% | 79.5% | -8.12% |
| Dow Jones | 4w | Mixed | 452 | +0.77% | 64.6% | -2.77% |
| Dow Jones | 13w | Mixed | 443 | +2.50% | 68.2% | -5.12% |
| Dow Jones | 26w | Mixed | 430 | +5.06% | 74.0% | -7.40% |
| Gold | 4w | Mixed | 452 | +1.21% | 57.5% | -2.31% |
| Gold | 13w | Mixed | 443 | +3.92% | 66.4% | -3.83% |
| Gold | 26w | Mixed | 430 | +8.53% | 74.2% | -4.72% |

## Predictivity Diagnostics

| Market | Horizon | N | Score/return r | HAC p | Risk-On minus Caution | Edge HAC p | Drift-adjusted accuracy | Evidence |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| S&P 500 | 4w | 430 | +0.088 | 0.217 | +1.96% | 0.137 | 52.3% | Unclear |
| S&P 500 | 13w | 421 | +0.103 | 0.362 | +6.86% | 0.003 | 56.0% | Supported |
| S&P 500 | 26w | 408 | +0.140 | 0.265 | +11.78% | 0.002 | 55.8% | Supported |
| NASDAQ-100 | 4w | 452 | +0.025 | 0.639 | n/a | n/a | 53.8% | Insufficient |
| NASDAQ-100 | 13w | 443 | +0.067 | 0.298 | n/a | n/a | 53.4% | Insufficient |
| NASDAQ-100 | 26w | 430 | -0.015 | 0.838 | n/a | n/a | 52.6% | Insufficient |
| VIX Futures | 4w | 453 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| VIX Futures | 13w | 443 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| VIX Futures | 26w | 430 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 4w | 134 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 13w | 125 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 26w | 112 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 4w | 452 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 13w | 443 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 26w | 430 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Gold | 4w | 452 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Gold | 13w | 443 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Gold | 26w | 430 | n/a | n/a | n/a | n/a | n/a | Insufficient |

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
