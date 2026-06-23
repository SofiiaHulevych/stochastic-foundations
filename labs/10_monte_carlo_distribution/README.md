# Lab 10 — Monte Carlo: Discrete Distribution Simulation

## Problem
Simulate a custom discrete distribution using Monte Carlo method.
Compare theoretical PDF with empirical results from 1000 trials.
Sheet 2 analyzes a Uniform distribution with confidence interval.

## Distribution (Sheet L)
| k | PDF  |
|---|------|
| 0 | 0.20 |
| 1 | 0.10 |
| 2 | 0.40 |
| 3 | 0.20 |
| 4 | 0.10 |

## Statistics (Sheet L)
| Statistic      | Theoretical | Simulated |
|----------------|-------------|-----------|
| E(X)           | 1.90        | 1.853     |
| D(X)           | 1.49        | —         |
| σ              | 1.221       | —         |

## Uniform Distribution (Sheet uniform_distribution)
| Parameter      | Value         |
|----------------|---------------|
| E(X)           | 20            |
| D(X)           | 140           |
| σ              | 11.83         |
| Interval (c=1) | [8.17, 31.83] |

## Sheets
| Sheet                | Description                         |
|----------------------|-------------------------------------|
| L                    | Discrete distribution + Monte Carlo |
| uniform_distribution | Uniform distribution analysis       |

## Result
Simulated distribution closely matches theoretical PDF after 1000 trials
