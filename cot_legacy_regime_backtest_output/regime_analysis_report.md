# COT Regime Score Backtest Report

Generated: 2026-10-02T23:12:41Z

This report is regenerated from the same current Legacy COT inputs used by the dashboard. COT observations are Tuesday report dates; signals start at the first available close on or after Friday publication.

## Data Cutoffs

| Market | Latest COT report | Latest signal close | Latest price | Scored rows |
| --- | --- | --- | --- | --- |
| S&P 500 | 2026-09-29 | 2026-10-02 | 2026-10-02 | 436 |
| NASDAQ-100 | 2026-09-29 | 2026-10-02 | 2026-10-02 | 458 |
| VIX Futures | 2026-09-29 | 2026-10-02 | 2026-10-02 | 458 |
| Russell 2000 | 2026-09-29 | 2026-10-02 | 2026-10-02 | 140 |
| Dow Jones | 2026-09-29 | 2026-10-02 | 2026-10-02 | 458 |
| Gold | 2026-09-29 | 2026-10-02 | 2026-10-02 | 458 |

## Current Tradable COT Signals

| Market | Report date | Signal date | Score | Bucket | Active triggers |
| --- | --- | --- | --- | --- | --- |
| S&P 500 | 2026-09-29 | 2026-10-02 | -1.00 | Mixed | nonreportable 93.9% -1.00 Non-reportable contrarian (retail long) |
| NASDAQ-100 | 2026-09-29 | 2026-10-02 | -1.00 | Mixed | nonreportable 93.0% -1.00 Non-reportable contrarian (retail long) |
| VIX Futures | 2026-09-29 | 2026-10-02 | +0.00 | Mixed | No active extreme trigger |
| Russell 2000 | 2026-09-29 | 2026-10-02 | +0.00 | Mixed | No active extreme trigger |
| Dow Jones | 2026-09-29 | 2026-10-02 | +0.00 | Mixed | No active extreme trigger |
| Gold | 2026-09-29 | 2026-10-02 | +0.00 | Mixed | No active extreme trigger |

## Forward Returns by Regime Bucket

| Market | Horizon | Bucket | N | Average return | Hit rate | Average drawdown |
| --- | --- | --- | --- | --- | --- | --- |
| S&P 500 | 4w | Mixed | 317 | +1.06% | 69.1% | -2.77% |
| S&P 500 | 4w | Caution | 21 | -0.35% | 61.9% | -3.66% |
| S&P 500 | 4w | Risk-On | 93 | +1.61% | 68.8% | -2.65% |
| S&P 500 | 13w | Mixed | 308 | +4.11% | 77.3% | -5.23% |
| S&P 500 | 13w | Caution | 21 | -3.58% | 23.8% | -9.41% |
| S&P 500 | 13w | Risk-On | 93 | +3.27% | 71.0% | -4.59% |
| S&P 500 | 26w | Mixed | 296 | +7.75% | 76.7% | -7.78% |
| S&P 500 | 26w | Caution | 21 | -3.71% | 28.6% | -15.81% |
| S&P 500 | 26w | Risk-On | 92 | +8.07% | 84.8% | -5.69% |
| NASDAQ-100 | 4w | Mixed | 401 | +1.51% | 64.1% | -3.57% |
| NASDAQ-100 | 4w | Risk-On | 52 | +2.30% | 71.2% | -2.81% |
| NASDAQ-100 | 13w | Mixed | 394 | +4.71% | 69.3% | -6.55% |
| NASDAQ-100 | 13w | Risk-On | 50 | +7.99% | 96.0% | -4.23% |
| NASDAQ-100 | 26w | Mixed | 384 | +10.24% | 76.8% | -9.03% |
| NASDAQ-100 | 26w | Risk-On | 47 | +12.12% | 89.4% | -4.44% |
| VIX Futures | 4w | Mixed | 454 | +6.13% | 50.2% | -13.08% |
| VIX Futures | 13w | Mixed | 444 | +9.97% | 46.4% | -19.71% |
| VIX Futures | 26w | Mixed | 431 | +9.99% | 46.6% | -23.45% |
| Russell 2000 | 4w | Mixed | 135 | +1.39% | 63.0% | -3.14% |
| Russell 2000 | 13w | Mixed | 126 | +4.48% | 74.6% | -5.52% |
| Russell 2000 | 26w | Mixed | 113 | +9.08% | 79.6% | -8.06% |
| Dow Jones | 4w | Mixed | 453 | +0.76% | 64.5% | -2.78% |
| Dow Jones | 13w | Mixed | 444 | +2.49% | 68.0% | -5.11% |
| Dow Jones | 26w | Mixed | 431 | +5.08% | 74.0% | -7.38% |
| Gold | 4w | Mixed | 453 | +1.19% | 57.4% | -2.32% |
| Gold | 13w | Mixed | 444 | +3.91% | 66.4% | -3.82% |
| Gold | 26w | Mixed | 431 | +8.50% | 74.0% | -4.74% |

## Predictivity Diagnostics

| Market | Horizon | N | Score/return r | HAC p | Risk-On minus Caution | Edge HAC p | Drift-adjusted accuracy | Evidence |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| S&P 500 | 4w | 431 | +0.088 | 0.214 | +1.96% | 0.137 | 52.5% | Unclear |
| S&P 500 | 13w | 422 | +0.103 | 0.363 | +6.86% | 0.003 | 55.7% | Supported |
| S&P 500 | 26w | 409 | +0.139 | 0.267 | +11.78% | 0.002 | 55.8% | Supported |
| NASDAQ-100 | 4w | 453 | +0.024 | 0.646 | n/a | n/a | 53.6% | Insufficient |
| NASDAQ-100 | 13w | 444 | +0.067 | 0.301 | n/a | n/a | 53.1% | Insufficient |
| NASDAQ-100 | 26w | 431 | -0.016 | 0.829 | n/a | n/a | 52.6% | Insufficient |
| VIX Futures | 4w | 454 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| VIX Futures | 13w | 444 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| VIX Futures | 26w | 431 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 4w | 135 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 13w | 126 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 26w | 113 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 4w | 453 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 13w | 444 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 26w | 431 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Gold | 4w | 453 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Gold | 13w | 444 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Gold | 26w | 431 | n/a | n/a | n/a | n/a | n/a | Insufficient |

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
