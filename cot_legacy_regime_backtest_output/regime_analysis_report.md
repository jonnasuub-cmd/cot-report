# COT Regime Score Backtest Report

Generated: 2026-10-16T22:11:38Z

This report is regenerated from the same current Legacy COT inputs used by the dashboard. COT observations are Tuesday report dates; signals start at the first available close on or after Friday publication.

## Data Cutoffs

| Market | Latest COT report | Latest signal close | Latest price | Scored rows |
| --- | --- | --- | --- | --- |
| S&P 500 | 2026-10-13 | 2026-10-16 | 2026-10-16 | 438 |
| NASDAQ-100 | 2026-10-13 | 2026-10-16 | 2026-10-16 | 460 |
| VIX Futures | 2026-10-13 | 2026-10-16 | 2026-10-16 | 460 |
| Russell 2000 | 2026-10-13 | 2026-10-16 | 2026-10-16 | 142 |
| Dow Jones | 2026-10-13 | 2026-10-16 | 2026-10-16 | 460 |
| Gold | 2026-10-13 | 2026-10-16 | 2026-10-16 | 460 |

## Current Tradable COT Signals

| Market | Report date | Signal date | Score | Bucket | Active triggers |
| --- | --- | --- | --- | --- | --- |
| S&P 500 | 2026-10-13 | 2026-10-16 | -1.00 | Mixed | nonreportable 92.1% -1.00 Non-reportable contrarian (retail long) |
| NASDAQ-100 | 2026-10-13 | 2026-10-16 | -1.00 | Mixed | nonreportable 95.7% -1.00 Non-reportable contrarian (retail long) |
| VIX Futures | 2026-10-13 | 2026-10-16 | +0.00 | Mixed | No active extreme trigger |
| Russell 2000 | 2026-10-13 | 2026-10-16 | +0.00 | Mixed | No active extreme trigger |
| Dow Jones | 2026-10-13 | 2026-10-16 | +0.00 | Mixed | No active extreme trigger |
| Gold | 2026-10-13 | 2026-10-16 | +0.00 | Mixed | No active extreme trigger |

## Forward Returns by Regime Bucket

| Market | Horizon | Bucket | N | Average return | Hit rate | Average drawdown |
| --- | --- | --- | --- | --- | --- | --- |
| S&P 500 | 4w | Mixed | 320 | +1.06% | 69.4% | -2.76% |
| S&P 500 | 4w | Caution | 21 | -0.35% | 61.9% | -3.66% |
| S&P 500 | 4w | Risk-On | 93 | +1.61% | 68.8% | -2.65% |
| S&P 500 | 13w | Mixed | 310 | +4.10% | 77.4% | -5.22% |
| S&P 500 | 13w | Caution | 21 | -3.58% | 23.8% | -9.41% |
| S&P 500 | 13w | Risk-On | 93 | +3.27% | 71.0% | -4.59% |
| S&P 500 | 26w | Mixed | 298 | +7.80% | 76.8% | -7.73% |
| S&P 500 | 26w | Caution | 21 | -3.71% | 28.6% | -15.81% |
| S&P 500 | 26w | Risk-On | 92 | +8.07% | 84.8% | -5.69% |
| NASDAQ-100 | 4w | Mixed | 404 | +1.52% | 64.1% | -3.55% |
| NASDAQ-100 | 4w | Risk-On | 52 | +2.30% | 71.2% | -2.81% |
| NASDAQ-100 | 13w | Mixed | 395 | +4.71% | 69.4% | -6.55% |
| NASDAQ-100 | 13w | Risk-On | 51 | +7.93% | 96.1% | -4.32% |
| NASDAQ-100 | 26w | Mixed | 386 | +10.31% | 76.9% | -8.99% |
| NASDAQ-100 | 26w | Risk-On | 47 | +12.12% | 89.4% | -4.44% |
| VIX Futures | 4w | Mixed | 456 | +6.17% | 50.2% | -13.06% |
| VIX Futures | 13w | Mixed | 447 | +9.91% | 46.3% | -19.66% |
| VIX Futures | 26w | Mixed | 433 | +9.80% | 46.4% | -23.50% |
| Russell 2000 | 4w | Mixed | 138 | +1.27% | 61.6% | -3.18% |
| Russell 2000 | 13w | Mixed | 128 | +4.32% | 73.4% | -5.54% |
| Russell 2000 | 26w | Mixed | 115 | +9.06% | 80.0% | -7.92% |
| Dow Jones | 4w | Mixed | 456 | +0.74% | 64.3% | -2.78% |
| Dow Jones | 13w | Mixed | 446 | +2.47% | 67.7% | -5.10% |
| Dow Jones | 26w | Mixed | 433 | +5.10% | 74.1% | -7.34% |
| Gold | 4w | Mixed | 456 | +1.14% | 57.0% | -2.35% |
| Gold | 13w | Mixed | 446 | +3.90% | 66.6% | -3.82% |
| Gold | 26w | Mixed | 433 | +8.40% | 73.7% | -4.79% |

## Predictivity Diagnostics

| Market | Horizon | N | Score/return r | HAC p | Risk-On minus Caution | Edge HAC p | Drift-adjusted accuracy | Evidence |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| S&P 500 | 4w | 434 | +0.088 | 0.215 | +1.96% | 0.137 | 52.5% | Unclear |
| S&P 500 | 13w | 424 | +0.103 | 0.363 | +6.86% | 0.003 | 55.7% | Supported |
| S&P 500 | 26w | 411 | +0.138 | 0.270 | +11.78% | 0.002 | 55.8% | Supported |
| NASDAQ-100 | 4w | 456 | +0.023 | 0.667 | n/a | n/a | 53.3% | Insufficient |
| NASDAQ-100 | 13w | 446 | +0.067 | 0.297 | n/a | n/a | 53.7% | Insufficient |
| NASDAQ-100 | 26w | 433 | -0.017 | 0.819 | n/a | n/a | 52.6% | Insufficient |
| VIX Futures | 4w | 456 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| VIX Futures | 13w | 447 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| VIX Futures | 26w | 433 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 4w | 138 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 13w | 128 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 26w | 115 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 4w | 456 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 13w | 446 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 26w | 433 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Gold | 4w | 456 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Gold | 13w | 446 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Gold | 26w | 433 | n/a | n/a | n/a | n/a | n/a | Insufficient |

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
