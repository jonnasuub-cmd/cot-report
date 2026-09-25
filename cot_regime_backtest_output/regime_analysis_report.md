# COT Regime Score Backtest Report

Generated: 2026-09-25T22:43:42Z

This report is regenerated from the same current TFF Detailed inputs used by the dashboard. COT observations are Tuesday report dates; signals start at the first available close on or after Friday publication.

## Data Cutoffs

| Market | Latest COT report | Latest signal close | Latest price | Scored rows |
| --- | --- | --- | --- | --- |
| S&P 500 | 2026-09-22 | 2026-09-25 | 2026-09-25 | 435 |
| NASDAQ-100 | 2026-09-22 | 2026-09-25 | 2026-09-25 | 457 |
| Russell 2000 | 2026-09-22 | 2026-09-25 | 2026-09-25 | 139 |
| Dow Jones | 2026-09-22 | 2026-09-25 | 2026-09-25 | 457 |

## Current Tradable COT Signals

| Market | Report date | Signal date | Score | Bucket | Active triggers |
| --- | --- | --- | --- | --- | --- |
| S&P 500 | 2026-09-22 | 2026-09-25 | -2.50 | Caution | asset_mgr 97.8% -2.00 Asset Manager crowding; lev_money 9.7% +0.50 Leveraged Money underexposed; non_reportable 92.2% -1.00 Non-reportable contrarian (retail long) |
| NASDAQ-100 | 2026-09-22 | 2026-09-25 | +0.00 | Mixed | No active extreme trigger |
| Russell 2000 | 2026-09-22 | 2026-09-25 | +0.00 | Mixed | No active extreme trigger |
| Dow Jones | 2026-09-22 | 2026-09-25 | +0.00 | Mixed | No active extreme trigger |

## Forward Returns by Regime Bucket

| Market | Horizon | Bucket | N | Average return | Hit rate | Average drawdown |
| --- | --- | --- | --- | --- | --- | --- |
| S&P 500 | 4w | Mixed | 262 | +1.29% | 67.6% | -2.82% |
| S&P 500 | 4w | Caution | 158 | +0.48% | 69.6% | -2.85% |
| S&P 500 | 4w | Risk-On | 10 | +6.64% | 90.0% | -1.02% |
| S&P 500 | 13w | Mixed | 259 | +4.69% | 78.8% | -4.61% |
| S&P 500 | 13w | Caution | 152 | +1.73% | 65.1% | -6.52% |
| S&P 500 | 13w | Risk-On | 10 | +1.32% | 50.0% | -4.77% |
| S&P 500 | 26w | Mixed | 248 | +8.72% | 78.6% | -6.71% |
| S&P 500 | 26w | Caution | 150 | +4.70% | 70.0% | -9.61% |
| S&P 500 | 26w | Risk-On | 10 | +6.89% | 100.0% | -5.08% |
| NASDAQ-100 | 4w | Mixed | 340 | +1.70% | 65.6% | -3.53% |
| NASDAQ-100 | 4w | Risk-On | 88 | +1.62% | 63.6% | -3.21% |
| NASDAQ-100 | 4w | Caution | 24 | -0.03% | 58.3% | -3.86% |
| NASDAQ-100 | 13w | Mixed | 331 | +5.12% | 71.6% | -6.28% |
| NASDAQ-100 | 13w | Risk-On | 88 | +6.07% | 80.7% | -5.28% |
| NASDAQ-100 | 13w | Caution | 24 | +1.01% | 50.0% | -10.06% |
| NASDAQ-100 | 26w | Mixed | 321 | +9.68% | 74.5% | -8.59% |
| NASDAQ-100 | 26w | Risk-On | 85 | +13.17% | 85.9% | -6.63% |
| NASDAQ-100 | 26w | Caution | 24 | +10.13% | 100.0% | -14.79% |
| Russell 2000 | 4w | Mixed | 134 | +1.44% | 63.4% | -3.12% |
| Russell 2000 | 13w | Mixed | 125 | +4.57% | 75.2% | -5.51% |
| Russell 2000 | 26w | Mixed | 112 | +9.02% | 79.5% | -8.12% |
| Dow Jones | 4w | Mixed | 452 | +0.77% | 64.6% | -2.77% |
| Dow Jones | 13w | Mixed | 443 | +2.50% | 68.2% | -5.12% |
| Dow Jones | 26w | Mixed | 430 | +5.06% | 74.0% | -7.40% |

## Predictivity Diagnostics

| Market | Horizon | N | Score/return r | HAC p | Risk-On minus Caution | Edge HAC p | Drift-adjusted accuracy | Evidence |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| S&P 500 | 4w | 430 | +0.118 | 0.089 | +6.16% | 0.000 | 50.5% | Insufficient |
| S&P 500 | 13w | 421 | +0.158 | 0.170 | -0.41% | 0.854 | 56.0% | Insufficient |
| S&P 500 | 26w | 408 | +0.165 | 0.221 | +2.19% | 0.332 | 55.4% | Insufficient |
| NASDAQ-100 | 4w | 452 | +0.049 | 0.398 | +1.65% | 0.400 | 57.2% | Unclear |
| NASDAQ-100 | 13w | 443 | +0.096 | 0.230 | +5.07% | 0.277 | 52.3% | Unclear |
| NASDAQ-100 | 26w | 430 | +0.127 | 0.070 | +3.03% | 0.515 | 58.9% | Weak |
| Russell 2000 | 4w | 134 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 13w | 125 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 26w | 112 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 4w | 452 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 13w | 443 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 26w | 430 | n/a | n/a | n/a | n/a | n/a | Insufficient |

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
