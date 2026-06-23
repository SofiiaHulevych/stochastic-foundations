# Lab 09 — Binomial Distribution: Voting Simulation

## Problem
Model an election where each voter independently votes for A with p=0.6.
Compute the Binomial PDF for n=10 and n=100 voters.
Sheet 2 adds a custom simulation with p=0.7, n=8.

## Parameters
| Parameter | Value |
|-----------|-------|
| p(A)      | 0.60  |
| p(B)      | 0.40  |

## Sheets
| Sheet                | Description                              |
|----------------------|------------------------------------------|
| n10_and_n100         | PDF for n=10 and n=100 voters            |
| simulation_p07_n8    | Simulation p=0.7, n=8, empirical vs Binomial |

## Formula
P(X=k) = C(n,k) * p^k * (1-p)^(n-k)

## Result
For n=10: P(A wins majority) = P(X≥6) ≈ 0.666
For n=100: distribution peaks around k=60
For simulation p=0.7, n=8: empirical PDF closely matches Binomial(8, 0.7)
