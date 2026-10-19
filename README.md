# transistors-to-logic-gates

This project uses NPN and PNP transistors to build all standard logic gates: AND, OR, NOT, NAND, NOR, XOR, and XNOR. It explores how individual transistors can be connected to create the building blocks of digital circuits.


## Transistor schematics

Every gate schematic uses both NPN 2N3904 and PNP 2N3906 transistors in complementary BJT stages powered by 3.3 V. Each gate folder contains an SVG schematic, a parts list, and a truth table.

- [AND](AND/README.md)
- [OR](OR/README.md)
- [NOT](NOT/README.md)
- [NAND](NAND/README.md)
- [NOR](NOR/README.md)
- [XOR](XOR/README.md)
- [XNOR](XNOR/README.md)

The stage connections pass Boolean truth-table checks. Electrical simulation and hardware validation are still required before building.
