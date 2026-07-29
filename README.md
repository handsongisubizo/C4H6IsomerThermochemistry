# C₄H₆ Isomer Thermochemistry: DFT vs CCSD(T) vs Experiment

How well do DFT and CCSD(T) match experiment? Tested on the four C₄H₆ isomers:
**1,3-butadiene, 1,2-butadiene, 1-butyne, and 2-butyne**.

## Why this system

Four molecules share one formula, C₄H₆, but arrange their bonds differently:

| Isomer | Bond arrangement |
|---|---|
| 1,3-Butadiene | two double bonds, separated |
| 1,2-Butadiene | two double bonds, side by side |
| 1-Butyne | one triple bond, at the end |
| 2-Butyne | one triple bond, in the middle |

## Objective

To test whether DFT and CCSD(T) reproduce the experimental enthalpies of
formation from ATcT. The comparison shows how much each method deviates —
and whether it can be trusted.

## Target result

One table, three methods, side by side:

| Isomer | DFT | CCSD(T) | Experiment (ATcT) | Error DFT | Error CCSD(T) |
|---|---|---|---|---|---|
| 1,3-Butadiene | | | 0.00 ± 0.29 | | |
| 2-Butyne | | | 35.46 ± 0.45 | | |
| 1,2-Butadiene | | | 51.40 ± 0.42 | | |
| 1-Butyne | | | 55.68 ± 0.56 | | |

*Relative enthalpies, kJ/mol, 298.15 K, gas phase. Experimental values from
ATcT v1.220, relative to 1,3-butadiene (absolute ΔfH°: 111.15, 146.61,
162.55, 166.83 kJ/mol). DFT and CCSD(T) columns will be filled from my
calculations.*

Plus one figure: a bar chart of all three methods per isomer, showing
whether they agree on the ordering and how closely each tracks experiment.




© 2026 Handson Gisubizo. All rights reserved. No part of this work may be used, reproduced, or distributed without written permission.
