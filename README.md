# transistors-to-logic-gates

This project uses **both NPN and PNP transistors in every gate** to build all standard logic gates: AND, OR, NOT, NAND, NOR, XOR, and XNOR. It explores how individual transistors can be connected to create the building blocks of digital circuits.

## Transistor schematics

Every gate schematic uses both NPN 2N3904 and PNP 2N3906 transistors in complementary BJT stages powered by 3.3 V. Each gate folder contains an SVG schematic, a parts list, and a truth table.

The PNP transistors provide the pull-up path to the positive supply, and the NPN transistors provide the pull-down path to ground. Every transistor has its own 10 kΩ base resistor.

| Logic gate | NPN transistors (2N3904) | PNP transistors (2N3906) |
|---|---|---|
| [AND](AND/README.md) | 4 | 4 |
| [OR](OR/README.md) | 3 | 3 |
| [NOT](NOT/README.md) | 1 | 1 |
| [NAND](NAND/README.md) | 5 | 5 |
| [NOR](NOR/README.md) | 2 | 2 |
| [XOR](XOR/README.md) | 9 | 9 |
| [XNOR](XNOR/README.md) | 8 | 8 |

The stage connections pass Boolean truth-table checks. Electrical simulation and hardware validation are still required before building.
