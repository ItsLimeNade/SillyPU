# Silly ALU

A really really simple Arithmetic and Logic Unit built specifficaly for the SillyPU

## What can it do?

It can take in two 8-bit numbers A and B with a 1-bit opcode

| Opcode |Operation|
|--------|:-------:|
|    0   |  A + B  |
|    1   |  A - B  |

#### Yup.. That's it! Silly isn't it?

## What components does it use?



| Product Number         | Manufacturer      |  Price per Unit | IC type|
|--------------|:-----------------:|-------:|-----------:|
| [CD74HC283M96](https://www.lcsc.com/product-detail/Special-Logic-ICs_Texas-Instruments-CD74HC283M96_C543032.html) |  Texas Instruments | 0,69 € | 4-Bit Binary Full Adder|
| [SN74HCS86PWR](https://www.lcsc.com/product-detail/Gates_Texas-Instruments-SN74HCS86PWR_C2869860.html) |  Texas Instruments | 0,32 € | 4 Circuit XOR Logic Gate |
| [AAA-BAT-046-K01](https://www.lcsc.com/product-detail/Battery-Connectors_LOTES-AAA-BAT-046-K01_C2926854.html) |  LOTES | 0.3167 € | AAA Battery Connector |
| [MK-12C02G1.5-W](https://www.lcsc.com/product-detail/Slide-Switches_HOOYA-MK-12C02G1-5-W_C20611677.html) |  HOOYA |  0.1229 € | SMD Slide Switch |

## Linked Files
- **ALU.circ is the logisim-evolution simulation of the ALU**
- **NOT ADDED YET ALU.idk is the electrical schematic of the ALU**
- **NOT ADDED YET ALU.idk2 is the PCB design of the ALU**