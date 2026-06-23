# Lab 08 — Binomial Distribution: Theory vs Simulation

## Problem
Roll a fair die 10 times per trial. Count how many times 6 appears.
Compare theoretical Binomial PDF with empirical results.

## Parameters
| Parameter   | Value       |
|-------------|-------------|
| n_rolls     | 10          |
| p_success   | 1/6 ≈ 0.167 |
| n_trials    | 100         |

## Formula
P(X=x) = C(n,x) * p^x * (1-p)^(n-x)

## Charts
- `theoretical_pdf` — theoretical Binomial PDF
- `empirical_pdf` — observed counts per outcome

## Result
Distribution peaks at x=1–2, consistent with Binomial(10, 1/6)
