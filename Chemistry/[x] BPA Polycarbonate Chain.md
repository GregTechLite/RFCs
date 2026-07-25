# BPA Polycarbonate Chain

- **Author(s)**: Magic_Sweepy
- **Created**: 2026-06-19

## Summary
Add BPA Polycarbonate (BPA-PC) chain for BPA Polycarbonate Glass and some other parts.

## Motivation
Now BPA Polycarbonate Glass block missing a recipe, but it is already existed in game,
so maybe we can add a recipe for it.

## Usage
Directly, BPA Polycarbonate Glass (UV tier glass), or its lens, plate as some recipe ingredients.

## Chemistry Processing
1. 2CH4O + CO2 -> C3H6O3 + H2O
> 2B **Methanol** + 1B **Carbon Dioxide** --[**Chemical Reactor**, 480 EU/t, 6s]--> 1B **Dimethyl Carbonate** + 1B **Water**
2. C3H6O3 + 2C6H6O -> C13H10O3 + 2CH4O (cycle)
> 1B **Dimethyl Carbonate** + 2B **Phenol** --[**Chemical Reactor**, 1920 EU/t, 6s]--> 1B **Diphenyl Carbonate** + 2B **Methanol**
3. C13H10O3 + C15H16O2 -> C16H14O3 + 2C6H6O (cycle)
> 1B **Diphenyl Carbonate** + 1B **Bisphenol A** --[**Chemical Reactor**, 7860 EU/t, 8s]--> 144mB **BPA Polycarbonate** + 2B **Phenol**