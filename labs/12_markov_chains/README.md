# Lab 12 — Markov Chains: Stationary Distribution

## Problem
Find the stationary distribution of a 2-state Markov chain
and verify convergence from different initial states.

## Transition Matrix
|         | State 1 | State 2 |
|---------|---------|---------|
| State 1 | 0.5     | 0.5     |
| State 2 | 0.2     | 0.8     |

## Sheets
| Sheet                  | Description                           |
|------------------------|---------------------------------------|
| stationary_distribution| Power iteration from 3 initial states |
| simulation             | Monte Carlo verification (20 steps)   |

## Result
| Stationary distribution | Value  |
|-------------------------|--------|
| p1                      | ≈ 0.286|
| p2                      | ≈ 0.714|

## Key Observation
Regardless of initial state (0,1), (1,0), or (0.5, 0.5),
the chain converges to the same stationary distribution after ~15 steps
