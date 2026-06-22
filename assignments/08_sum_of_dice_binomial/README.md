# Assignment 09 — Sum of Dice vs Binomial Distribution

## Problem
Roll 5 dice (each 0–14), compute their sum.
Compare the empirical PDF of the sum with a theoretical Binomial fit.

## Parameters
| Parameter     | Value  |
|---------------|--------|
| n_dice        | 5      |
| die_faces     | 0–14   |
| n_simulations | 1000   |
| pdf_range     | 0–70   |

## Charts
- `empirical_pdf` — empirical distribution of the sum
- `pdf_vs_binomial` — empirical vs theoretical Binomial overlay

## Result
Empirical PDF approximates Binomial shape,
peaking around sum = 33–36
