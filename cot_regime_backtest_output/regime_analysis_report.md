# COT Regime Score Backtest Report

Generated: 2026-10-02T23:12:31Z

This report is regenerated from the same current TFF Detailed inputs used by the dashboard. COT observations are Tuesday report dates; signals start at the first available close on or after Friday publication.

## Data Cutoffs

| Market | Latest COT report | Latest signal close | Latest price | Scored rows |
| --- | --- | --- | --- | --- |
| S&P 500 | 2026-09-29 | 2026-10-02 | 2026-10-02 | 436 |
| NASDAQ-100 | 2026-09-29 | 2026-10-02 | 2026-10-02 | 458 |
| Russell 2000 | 2026-09-29 | 2026-10-02 | 2026-10-02 | 140 |
| Dow Jones | 2026-09-29 | 2026-10-02 | 2026-10-02 | 458 |

## Current Tradable COT Signals

| Market | Report date | Signal date | Score | Bucket | Active triggers |
| --- | --- | --- | --- | --- | --- |
| S&P 500 | 2026-09-29 | 2026-10-02 | -3.00 | Caution | asset_mgr 92.0% -2.00 Asset Manager crowding; non_reportable 93.9% -1.00 Non-reportable contrarian (retail long) |
| NASDAQ-100 | 2026-09-29 | 2026-10-02 | -0.75 | Mixed | non_reportable 93.0% -0.75 Non-reportable contrarian (retail long) |
| Russell 2000 | 2026-09-29 | 2026-10-02 | +0.00 | Mixed | No active extreme trigger |
| Dow Jones | 2026-09-29 | 2026-10-02 | +0.00 | Mixed | No active extreme trigger |

## Forward Returns by Regime Bucket

| Market | Horizon | Bucket | N | Average return | Hit rate | Average drawdown |
| --- | --- | --- | --- | --- | --- | --- |
| S&P 500 | 4w | Mixed | 263 | +1.28% | 67.3% | -2.82% |
| S&P 500 | 4w | Caution | 158 | +0.48% | 69.6% | -2.85% |
| S&P 500 | 4w | Risk-On | 10 | +6.64% | 90.0% | -1.02% |
| S&P 500 | 13w | Mixed | 259 | +4.69% | 78.8% | -4.61% |
| S&P 500 | 13w | Caution | 153 | +1.75% | 65.4% | -6.49% |
| S&P 500 | 13w | Risk-On | 10 | +1.32% | 50.0% | -4.77% |
| S&P 500 | 26w | Mixed | 249 | +8.77% | 78.7% | -6.69% |
| S&P 500 | 26w | Caution | 150 | +4.70% | 70.0% | -9.61% |
| S&P 500 | 26w | Risk-On | 10 | +6.89% | 100.0% | -5.08% |
| NASDAQ-100 | 4w | Mixed | 341 | +1.71% | 65.7% | -3.52% |
| NASDAQ-100 | 4w | Risk-On | 88 | +1.62% | 63.6% | -3.21% |
| NASDAQ-100 | 4w | Caution | 24 | -0.03% | 58.3% | -3.86% |
| NASDAQ-100 | 13w | Mixed | 332 | +5.11% | 71.7% | -6.28% |
| NASDAQ-100 | 13w | Risk-On | 88 | +6.07% | 80.7% | -5.28% |
| NASDAQ-100 | 13w | Caution | 24 | +1.01% | 50.0% | -10.06% |
| NASDAQ-100 | 26w | Mixed | 322 | +9.75% | 74.5% | -8.57% |
| NASDAQ-100 | 26w | Risk-On | 85 | +13.17% | 85.9% | -6.63% |
| NASDAQ-100 | 26w | Caution | 24 | +10.13% | 100.0% | -14.79% |
| Russell 2000 | 4w | Mixed | 135 | +1.39% | 63.0% | -3.14% |
| Russell 2000 | 13w | Mixed | 126 | +4.48% | 74.6% | -5.52% |
| Russell 2000 | 26w | Mixed | 113 | +9.08% | 79.6% | -8.06% |
| Dow Jones | 4w | Mixed | 453 | +0.76% | 64.5% | -2.78% |
| Dow Jones | 13w | Mixed | 444 | +2.49% | 68.0% | -5.11% |
| Dow Jones | 26w | Mixed | 431 | +5.08% | 74.0% | -7.38% |

## Predictivity Diagnostics

| Market | Horizon | N | Score/return r | HAC p | Risk-On minus Caution | Edge HAC p | Drift-adjusted accuracy | Evidence |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| S&P 500 | 4w | 431 | +0.118 | 0.088 | +6.16% | 0.000 | 50.6% | Insufficient |
| S&P 500 | 13w | 422 | +0.157 | 0.171 | -0.43% | 0.848 | 55.8% | Insufficient |
| S&P 500 | 26w | 409 | +0.164 | 0.223 | +2.19% | 0.332 | 55.2% | Insufficient |
| NASDAQ-100 | 4w | 453 | +0.048 | 0.402 | +1.65% | 0.400 | 57.0% | Unclear |
| NASDAQ-100 | 13w | 444 | +0.096 | 0.230 | +5.07% | 0.277 | 52.1% | Unclear |
| NASDAQ-100 | 26w | 431 | +0.126 | 0.072 | +3.03% | 0.515 | 58.9% | Weak |
| Russell 2000 | 4w | 135 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 13w | 126 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Russell 2000 | 26w | 113 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 4w | 453 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 13w | 444 | n/a | n/a | n/a | n/a | n/a | Insufficient |
| Dow Jones | 26w | 431 | n/a | n/a | n/a | n/a | n/a | Insufficient |

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
