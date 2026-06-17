# Assignment 05 — Monte Carlo: Geometric Distribution

## Problem
Simulate rolling a custom 4-outcome die repeatedly until outcome 4 appears.
Estimate the average number of rolls needed (expected trial length).

## Setup
| outcome | probability | range_start | range_end |
|---------|-------------|-------------|-----------|
| 1       | 0.25        | 0.00        | 0.25      |
| 2       | 0.50        | 0.25        | 0.75      |
| 3       | 0.10        | 0.75        | 0.85      |
| 4       | 0.15        | 0.85        | 1.00      |

## Method
Monte Carlo simulation — generate uniform random numbers,
map to outcomes via range intervals, repeat until outcome 4 is hit.

## Theoretical Expected Value
E(X) = 1 / P(4) = 1 / 0.15 ≈ 6.67
