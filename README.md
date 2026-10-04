# CMOS Digital Circuit Design Using Cadence Virtuoso

This repository contains a collection of **semi-custom CMOS digital
circuit implementations** designed and analyzed using **Cadence
Virtuoso** with **Documentation** of how to implement them. 

The project covers the implementation of fundamental digital logic
circuits from **transistor-level schematic design to physical layout,
verification, parasitic extraction, and post-layout simulation**.

The Documentation pdf can be downloaded for implementation purpose only.
---

## Circuits Implemented

The following CMOS digital circuits are included in this repository:

| Circuit | Logic Function | Folder |
|--------|----------------|--------|
| CMOS Inverter | $Y=\overline{A}$ | [Inverter](./inverter) |
| 2-Input NAND Gate | $Y=\overline{AB}$ | [NAND](./nand) |
| 2-Input NOR Gate | $Y=\overline{A+B}$ | [NOR](./nor) |
| 2-Input AND Gate | $Y=AB$ | [AND](./and) |
| 2-Input OR Gate | $Y=A+B$ | [OR](./or) |
| 2-Input XOR Gate | $Y=A\oplus B$ | [XOR](./xor) |
| 2-Input XNOR Gate | $Y=A\odot B$ | [XNOR](./xnor) |
| 2:1 Multiplexer | $Y=\overline{S}A+SB$ | [MUX 2:1](./mux2x1) |
---

## Design Methodology

Each circuit was implemented using a semi-custom CMOS design approach
in Cadence Virtuoso.

The general design flow followed for the circuits is:

```text
Transistor-Level Schematic
            ↓
        Symbol Creation
            ↓
       Physical Layout
            ↓
           DRC
            ↓
           LVS
            ↓
     RCX Parasitic Extraction
            ↓
    Post-Layout Simulation
            ↓
   Power & Delay Analysis

```
---
---

## License / Copyright

© 2026 Piyal Chakraborty. All Rights Reserved.

This repository contains original academic and engineering work,
including CMOS circuit designs, Cadence Virtuoso implementations,
layouts, simulation results, and documentation.

The contents may be viewed for educational and reference purposes,
but may not be copied, redistributed, modified, republished, or
presented as another person's work without prior written permission.

Any permitted use must include clear attribution to the original
author.

See the [LICENSE](./LICENSE) file for the full copyright notice.

presented as another person's work without prior written permission.

Any permitted use must include clear attribution to the original
author.

See the [LICENSE](./LICENSE) file for the full copyright notice.
