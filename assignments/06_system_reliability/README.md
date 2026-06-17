# Assignment 06 — System Reliability Simulation

## Problem
Estimate the reliability of a parallel server system.
The system is operational if at least one server is functioning.

## Setup
| Server | Reliability |
|--------|-------------|
| 1      | 0.70        |
| 2      | 0.80        |
| 3      | 0.90        |

## Method
Monte Carlo simulation — each server independently fails
with probability (1 - reliability) per trial.
100 simulations total.

## Legend
| Value | Meaning |
|-------|---------|
| 1     | server working |
| 0     | server failed  |
| yes   | request served |
| no    | request failed |

## Result
system_reliability ≈ 0.55

## Theoretical Value
P(system up) = 1 - P(all fail) = 1 - (0.3 × 0.2 × 0.1) = 0.994
