# Assignment 08 — Binomial Distribution

## Problem
Model a Bernoulli process with n=14 trials and p=0.4 success probability.
Compute the PDF and simulate outcomes for multiple participants.

## Parameters
| Parameter    | Value |
|--------------|-------|
| n_trials     | 14    |
| p_success    | 0.40  |
| p_failure    | 0.60  |
| sample_size  | 83    |

## Formula
P(K=k) = C(n,k) * p^k * (1-p)^(n-k)

## Result
PDF peaks at k=5 with P(K=5) ≈ 0.241
