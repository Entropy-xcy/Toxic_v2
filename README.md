# Toxic v2
Toxic v2 is one of the simplest implementation of a functional processor in the world. It is a 4-bit stack machine with variable addressing width. It is a new edition of the previous Toxic v1 project. You may want to refer to the [Documentation](Toxic_Specifications.pdf) of Toxic v2. This repository contains only the documentation of both the ISA and the micro-architecture. You may refer to descriptions below for the Simulators and SystemVerilog Implementation.
## Why going from v1 to v2?
Our goal of the project is to design a 4-bit processor as simple as possible while maintaining basic functionalities. We don't want to have an ISA with variable instruction length since that will increase the complexity of the hardware. As a result, there are only 16 possible combinations of instructions which is not enough for a register machine. As a result, we create this Toxic_v2 project and change our design to be a **stack machine**.
## Possible use cases for this processor
* Teach a little boy like my younger brother how a processor works.
* As a blueprint of a hand-crafted processor using logic gates or simply MOSFETs.
* As a blueprint to build a processor in **Minecraft**.
## Simulator
* Java based behavior modeled simulator: https://github.com/Entropy-xcy/Toxic_v2_simulator. (Recommended)
* Verilator and C++ Based RTL-level simulator can be found with the SystemVerilog Implementation.
## SystemVerilog Implementation
[Toxic_v2_RTL](https://github.com/Entropy-xcy/Toxic_v2_RTL)