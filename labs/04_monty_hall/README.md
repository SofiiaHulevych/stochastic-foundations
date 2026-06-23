# Lab 04 — Monty Hall Problem

## Problem
Simulate the Monty Hall problem: a car is hidden behind one of 3 doors.
The player picks a door, the host opens a losing door,
and the player decides to stay or switch.

## Strategies
| Sheet                  | Strategy                         | Win Probability |
|------------------------|----------------------------------|-----------------|
| strategy_always_switch | Player always switches           | ~57%            |
| strategy_random        | Player switches randomly (50/50) | ~54%            |

## Key Insight
The host's action is not random — he always reveals a losing door.
This makes switching strictly better than staying.
The host must be included in the simulation — his decision
affects the game flow and provides additional information to the player.
