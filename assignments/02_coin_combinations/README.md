# Assignment 02 — Coin Change Combinations

## Problem
Find all ways to make exactly 23 EUR using coins of 
denominations: 2 EUR, 1 EUR, and 0.50 EUR.

## Approach
Enumerate all non-negative integer combinations (a, b, c) such that:
  2a + 1b + 0.5c = 23
where a, b, c ≥ 0

## Parameters
| Parameter     | Value  |
|---------------|--------|
| total_amount  | 23 EUR |
| coin_1        | 2.00 EUR |
| coin_2        | 1.00 EUR |
| coin_3        | 0.50 EUR |
