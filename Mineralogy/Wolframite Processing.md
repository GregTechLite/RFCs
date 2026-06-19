# Wolframite Processing

- **Author(s)**: 金丝雀
- **Created**: 2026-06-19

## Summary
**Wolframite** (FeMnWO4) is a new Tungsten group ores for GregTech, 
it can progress to Na2WO4 or Scheelite.

## Motivation
A new Tungsten ore has world generator with vein format,
and its ore processing line.

## Wolframite Vein
| Filler Type | Ore Type    |
|-------------|-------------|
| Primary     | Scheelite   |
| Secondary   | Wolframite  |
| Between     | Wolframite  |
| Sporadic    | Molybdenite |

## Wolframite Processing

1. FeMnWO4 + Na2CO3 + 3O -> Na2WO4 + MnO2 + FeO2 + CO2
> 7x **Wolframite dust** + **6x Soda Ash dust** + 3B **Oxygen**(g) --[Roaster, 480 EU/t, 10s]-->
> 7x **Sodium Tungstate dust** + 3x **Pyrolusite dust** + **3x Banded Iron dust** + 1B **Carbon Dioxide**
2. Na2WO4 + CaCl2 -> CaWO4 + 2NaCl
> 7x **Sodium Tungstate dust** + 3x **Calcium Chloride dust** --[Chemical Reactor, 120 EU/t, 5s]-->
> 6x **Scheelite dust** + 4x **Salt dust**
3. Back to **Scheelite Processing** and done.