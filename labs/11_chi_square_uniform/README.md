# Lab 11 — Chi-Square Goodness-of-Fit: Uniform Distribution

## Problem
Test whether 30 die rolls follow a uniform distribution
across 6 faces using the Chi-square test.
Sheet 2 adds a Binomial simulation with p=0.6, n=10.

## Parameters (Sheet chi_square_die)
| Parameter          | Value       |
|--------------------|-------------|
| n_rolls            | 30          |
| n_faces            | 6           |
| significance_level | 0.05        |
| p(each face)       | 1/6 ≈ 0.167 |

## Formula
χ² = Σ (nj - npj)² / npj

## Result (Sheet chi_square_die)
| Statistic          | Value        |
|--------------------|--------------|
| χ² statistic       | 55.20        |
| critical value     | 11.07        |
| p-value            | 1.19e-10     |
| decision           | H rejected — die is not fair |

## Sheets
| Sheet                | Description                     |
|----------------------|---------------------------------|
| chi_square_die       | Chi-square test for fair die    |
| binomial_simulation  | Binomial simulation p=0.6, n=10 |
