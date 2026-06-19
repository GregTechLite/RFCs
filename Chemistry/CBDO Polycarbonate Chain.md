# CBDO Polycarbonate Chain

- **Author(s)**: Magic_Sweepy
- **Created**: 2026-06-19

## Summary
Add CBDO Polycarbonate (CBDO-PC) chain for CBDO Polycarbonate Glass and some other parts.

## Motivation
Now CBDO Polycarbonate Glass block missing a recipe, but it is already existed in game,
so maybe we can add a recipe for it.

## Usage
Just like BPA Polycarbonate, at first, CBDO Polycarbonate Glass (UIV tier glass), or its lens, plate as some recipe 
ingredients.

## Chemistry Processing
For *Diphenyl Carbonate* chain, please see the **Chemistry Processing** part of [BPA Polycarbonate Chain](/Chemistry/BPA%20Polycarbonate%20Chain.md).

1. C3H6 + CO + H2O -> C4H8O2
> 1B **Propene** + 1B **Carbon Monoxide** + **1B Water** --[**Chemical Reactor**, 480 EU/t, 9s]--> 1B **Isobutyric Acid**
2. 2C4H8O2 + C4H6O3 -> C8H14O3 + 2C2H4O2
> 2B **Isobutyric Acid** + 1B **Acetic Anhydride** --[**Chemical Reactor**, 1920 EU/t, 3s]--> 1B **Isobutyric Anhydride** + 2B **Acetic Acid**
3. C8H14O3 -> 2C4H6O2 + 2H2O (lost)
> 1B **Isobutyric Anhydride** + 1x **Long YttriumBariumCuprate Stick** (catalyst) --[**Pyrolyse Oven**, 30720 EU/t, 12s]--> 2B **Dimethylketene**
4. 2C4H6O2 + 4H -> C8H16O2
> 2B **Dimethylketene** + 4B **Hydrogen** + 1x **Rhenium dust** (catalyst) --[**Chemical Reactor**, 491520 EU/t, 6s]--> 1B **Tetramethylcyclobutanediol**
5. C8H16O2 + C13H10O3 -> C9H14O3 + 2C6H6O
> 1B **Tetramethylcyclobutanediol** + 1B **Diphenyl Carbonate** --[**Chemical Reactor**, 120 EU/t, 8s]--> 144mB **CBDO Polycarbonate** + 2B **Phenol**