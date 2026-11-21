# COT Regime Score Backtest Report

Generated: 2026-11-21T00:56:20Z

This report is regenerated from the same current TFF Detailed inputs used by the dashboard. COT observations are Tuesday report dates; signals start at the first available close on or after Friday publication.

## Data Cutoffs

| Market | Latest COT report | Latest signal close | Latest price | Scored rows |
| --- | --- | --- | --- | --- |
| S&P 500 | 2026-11-17 | 2026-11-20 | 2026-11-20 | 443 |
| NASDAQ-100 | 2026-11-17 | 2026-11-20 | 2026-11-20 | 465 |
| Russell 2000 | 2026-11-17 | 2026-11-20 | 2026-11-20 | 147 |
| Dow Jones | 2026-11-17 | 2026-11-20 | 2026-11-20 | 465 |

## Current Tradable COT Signals

| Market | Report date | Signal date | Score | Bucket | Active triggers |
| --- | --- | --- | --- | --- | --- |
| S&P 500 | 2026-11-17 | 2026-11-20 | -1.00 | Mixed | non_reportable 92.7% -1.00 Non-reportable contrarian (retail long) |
| NASDAQ-100 | 2026-11-17 | 2026-11-20 | -0.75 | Mixed | non_reportable 99.3% -0.75 Non-reportable contrarian (retail long) |
| Russell 2000 | 2026-11-17 | 2026-11-20 | +0.00 | Mixed | No active extreme trigger |
| Dow Jones | 2026-11-17 | 2026-11-20 | +0.00 | Mixed | No active extreme trigger |

## Forward Returns by Regime Bucket

| Market | Horizon | Bucket | N | Average return | Hit rate | Average drawdown |
| --- | --- | --- | --- | --- | --- | --- |
| S&P 500 | 4w | Mixed | 267 | +1.24% | 67.4% | -2.83% |
| S&P 500 | 4w | Caution | 162 | +0.40% | 67.9% | -2.86% |
| S&P 500 | 4w | Risk-On | 10 | +6.64% | 90.0% | -1.02% |
| S&P 500 | 13w | Mixed | 261 | +4.62% | 78.2% | -4.62% |
| S&P 500 | 13w | Caution | 158 | +1.78% | 66.5% | -6.34% |
| S&P 500 | 13w | Risk-On | 10 | +1.32% | 50.0% | -4.77% |
| S&P 500 | 26w | Mixed | 256 | +8.72% | 78.9% | -6.53% |
| S&P 500 | 26w | Caution | 150 | +4.70% | 70.0% | -9.61% |
| S&P 500 | 26w | Risk-On | 10 | +6.89% | 100.0% | -5.08% |
| NASDAQ-100 | 4w | Mixed | 348 | +1.61% | 64.9% | -3.57% |
| NASDAQ-100 | 4w | Risk-On | 88 | +1.62% | 63.6% | -3.21% |
| NASDAQ-100 | 4w | Caution | 25 | -0.53% | 56.0% | -4.26% |
| NASDAQ-100 | 13w | Mixed | 339 | +5.00% | 71.4% | -6.30% |
| NASDAQ-100 | 13w | Risk-On | 88 | +6.07% | 80.7% | -5.28% |
| NASDAQ-100 | 13w | Caution | 24 | +1.01% | 50.0% | -10.06% |
| NASDAQ-100 | 26w | Mixed | 327 | +9.75% | 74.3% | -8.48% |
| NASDAQ-100 | 26w | Risk-On | 87 | +12.85% | 85.1% | -6.59% |
| NASDAQ-100 | 26w | Caution | 24 | +10.13% | 100.0% | -14.79% |
| Russell 2000 | 4w | Mixed | 143 | +1.16% | 60.1% | -3.19% |
| Russell 2000 | 13w | Mixed | 133 | +3.90% | 70.7% | -5.66% |
| Russell 2000 | 26w | Mixed | 120 | +8.62% | 78.3% | -7.74% |
| Dow Jones | 4w | Mixed | 461 | +0.72% | 64.2% | -2.77% |
| Dow Jones | 13w | Mixed | 451 | +2.43% | 67.2% | -5.09% |
| Dow Jones | 26w | Mixed | 438 | +5.09% | 74.2% | -7.27% |

## Predictivity Diagnostics

| Market | Horizon | N | Score/return r | HAC p | Risk-On minus Caution | Edge HAC p | Drift-adjusted accuracy | Evidence |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| S&P 500 | 4w | 439 | +0.125 | 0.068 | +6.23% | 0.000 | 51.4% | Insufficient |
| S&P 500 | 13w | 429 | +0.157 | 0.165 | -0.46% | 0.834 | 56.2% | Insufficient |
| S&P 500 | 26w | 416 | +0.165 | 0.218 | +2.19% | 0.332 | 54.9% | Insufficient |
| NASDAQ-100 | 4w | 461 | +0.064 | 0.265 | +2.15% | 0.273 | 57.2% | Unclear |
| NASDAQ-100 | 13w | 451 | +0.093 | 0.244 | +5.07% | 0.277 | 51.2% | Unclear |
| NASDAQ-100 | 26w | 438 | +0.118 | 0.095 | +2.72% | 0.565 | 58.1% | Weak |
| Russell 2000 | 4w | 143 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 13w | 133 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 26w | 120 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 4w | 461 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 13w | 451 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 26w | 438 | n/a | n/a | n/a | n/a | n/a | Insufficient |

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
