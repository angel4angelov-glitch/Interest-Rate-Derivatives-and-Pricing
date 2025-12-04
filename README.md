# Interest Rate Products – Pricing & Curve Experiments

> ⚠️ Educational sandbox. Not production code or financial advice.

Personal learning repo for interest rate derivatives: pricing, curve construction, hedging mechanics, and risk sensitivities.

---

## Contents

| # | Product | Description |
|---|---------|-------------|
| 1 | Overnight Indexed Swap (OIS) | OIS pricing, OIS curve bootstrapping |
| 2 | Plain-Vanilla Interest Rate Swap (IRS) | Fixed-float swap valuation, DV01 |
| 3 | Forward Rate Agreement (FRA) | FRA pricing and settlement |
| 4 | Interest Rate Futures | SOFR / Eurodollar futures, margining, convexity adjustment |
| 5 | Fixed-Coupon Bond | Government bond pricing, duration, convexity |
| 6 | Zero-Coupon Swap / Bond | Zero-coupon instrument valuation |
| 7 | European Swaption | Payer/receiver swaption, Black's model |
| 8 | Bermudan Swaption | Early exercise, tree/lattice methods |
| 9 | Cap / Floor / Collar | Caplet stripping, vol surface |
| 10 | Range Accrual Note | Path-dependent coupon accrual |
| 11 | Inverse Floater | Leveraged rate exposure |
| 12 | Callable & Puttable Bond | Embedded optionality, OAS |
| 13 | Constant Maturity Swap (CMS) | CMS convexity adjustment |
| 14 | CMS Spread Option | Correlation, copula methods |
| 15 | Cross Currency Swap (CCS) | FX basis, dual-curve discounting |

---

## Attribution

Code is adapted from textbooks, courses, and articles. Each file notes its source at the top.

---

## Setup
```bash
pip install -r requirements.txt
```
