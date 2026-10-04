# CMOS Digital Circuit Design Using Cadence Virtuoso

This repository contains a collection of **semi-custom CMOS digital
circuit implementations** designed and analyzed using **Cadence
Virtuoso**.

The project covers the implementation of fundamental digital logic
circuits from **transistor-level schematic design to physical layout,
verification, parasitic extraction, and post-layout simulation**.

---

## Circuits Implemented

The following CMOS digital circuits are included in this repository:

| Circuit | Logic Function | Folder |
|--------|----------------|--------|
| CMOS Inverter | \(Y=\overline{A}\) | [Inverter](./inverter) |
| 2-Input NAND Gate | \(Y=\overline{AB}\) | [NAND](./nand) |
| 2-Input NOR Gate | \(Y=\overline{A+B}\) | [NOR](./nor) |
| 2-Input AND Gate | \(Y=AB\) | [AND](./and) |
| 2-Input OR Gate | \(Y=A+B\) | [OR](./or) |
| 2-Input XOR Gate | \(Y=A\oplus B\) | [XOR](./xor) |
| 2-Input XNOR Gate | \(Y=A\odot B\) | [XNOR](./xnor) |
| 2:1 Multiplexer | \(Y=\overline{S}A+SB\) | [MUX 2:1](./mux2x1) |

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
