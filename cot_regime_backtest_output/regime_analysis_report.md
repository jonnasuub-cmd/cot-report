# COT Regime Score Backtest Report

Generated: 2026-11-06T23:47:57Z

This report is regenerated from the same current TFF Detailed inputs used by the dashboard. COT observations are Tuesday report dates; signals start at the first available close on or after Friday publication.

## Data Cutoffs

| Market | Latest COT report | Latest signal close | Latest price | Scored rows |
| --- | --- | --- | --- | --- |
| S&P 500 | 2026-11-03 | 2026-11-06 | 2026-11-06 | 441 |
| NASDAQ-100 | 2026-11-03 | 2026-11-06 | 2026-11-06 | 463 |
| Russell 2000 | 2026-11-03 | 2026-11-06 | 2026-11-06 | 145 |
| Dow Jones | 2026-11-03 | 2026-11-06 | 2026-11-06 | 463 |

## Current Tradable COT Signals

| Market | Report date | Signal date | Score | Bucket | Active triggers |
| --- | --- | --- | --- | --- | --- |
| S&P 500 | 2026-11-03 | 2026-11-06 | -1.00 | Mixed | non_reportable 96.3% -1.00 Non-reportable contrarian (retail long) |
| NASDAQ-100 | 2026-11-03 | 2026-11-06 | -2.25 | Caution | other_reportable 91.5% -1.50 Other Reportable crowding; non_reportable 97.7% -0.75 Non-reportable contrarian (retail long) |
| Russell 2000 | 2026-11-03 | 2026-11-06 | +0.00 | Mixed | No active extreme trigger |
| Dow Jones | 2026-11-03 | 2026-11-06 | +0.00 | Mixed | No active extreme trigger |

## Forward Returns by Regime Bucket

| Market | Horizon | Bucket | N | Average return | Hit rate | Average drawdown |
| --- | --- | --- | --- | --- | --- | --- |
| S&P 500 | 4w | Mixed | 266 | +1.28% | 67.7% | -2.80% |
| S&P 500 | 4w | Caution | 161 | +0.41% | 68.3% | -2.85% |
| S&P 500 | 4w | Risk-On | 10 | +6.64% | 90.0% | -1.02% |
| S&P 500 | 13w | Mixed | 259 | +4.69% | 78.8% | -4.61% |
| S&P 500 | 13w | Caution | 158 | +1.78% | 66.5% | -6.34% |
| S&P 500 | 13w | Risk-On | 10 | +1.32% | 50.0% | -4.77% |
| S&P 500 | 26w | Mixed | 254 | +8.79% | 79.1% | -6.56% |
| S&P 500 | 26w | Caution | 150 | +4.70% | 70.0% | -9.61% |
| S&P 500 | 26w | Risk-On | 10 | +6.89% | 100.0% | -5.08% |
| NASDAQ-100 | 4w | Mixed | 346 | +1.67% | 65.3% | -3.53% |
| NASDAQ-100 | 4w | Risk-On | 88 | +1.62% | 63.6% | -3.21% |
| NASDAQ-100 | 4w | Caution | 25 | -0.53% | 56.0% | -4.26% |
| NASDAQ-100 | 13w | Mixed | 337 | +5.08% | 71.8% | -6.27% |
| NASDAQ-100 | 13w | Risk-On | 88 | +6.07% | 80.7% | -5.28% |
| NASDAQ-100 | 13w | Caution | 24 | +1.01% | 50.0% | -10.06% |
| NASDAQ-100 | 26w | Mixed | 326 | +9.79% | 74.5% | -8.48% |
| NASDAQ-100 | 26w | Risk-On | 86 | +13.10% | 86.0% | -6.56% |
| NASDAQ-100 | 26w | Caution | 24 | +10.13% | 100.0% | -14.79% |
| Russell 2000 | 4w | Mixed | 141 | +1.21% | 60.3% | -3.19% |
| Russell 2000 | 13w | Mixed | 131 | +4.09% | 71.8% | -5.58% |
| Russell 2000 | 26w | Mixed | 118 | +8.83% | 79.7% | -7.78% |
| Dow Jones | 4w | Mixed | 459 | +0.74% | 64.3% | -2.76% |
| Dow Jones | 13w | Mixed | 449 | +2.46% | 67.5% | -5.09% |
| Dow Jones | 26w | Mixed | 436 | +5.10% | 74.3% | -7.30% |

## Predictivity Diagnostics

| Market | Horizon | N | Score/return r | HAC p | Risk-On minus Caution | Edge HAC p | Drift-adjusted accuracy | Evidence |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| S&P 500 | 4w | 437 | +0.124 | 0.072 | +6.22% | 0.000 | 51.1% | Insufficient |
| S&P 500 | 13w | 427 | +0.157 | 0.167 | -0.46% | 0.834 | 55.9% | Insufficient |
| S&P 500 | 26w | 414 | +0.163 | 0.224 | +2.19% | 0.332 | 54.6% | Insufficient |
| NASDAQ-100 | 4w | 459 | +0.059 | 0.307 | +2.15% | 0.273 | 56.9% | Unclear |
| NASDAQ-100 | 13w | 449 | +0.095 | 0.233 | +5.07% | 0.277 | 51.6% | Unclear |
| NASDAQ-100 | 26w | 436 | +0.121 | 0.085 | +2.97% | 0.523 | 58.3% | Weak |
| Russell 2000 | 4w | 141 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 13w | 131 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 26w | 118 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 4w | 459 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 13w | 449 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 26w | 436 | n/a | n/a | n/a | n/a | n/a | Insufficient |

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
