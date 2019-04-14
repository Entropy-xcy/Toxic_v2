# ISA Specifications
* Little Endian
* 4-bit Instruction with 4-bit or 8-bit data bus.
* Variable width of addressing with multiple of 4-bit
* Stack Machine (0-address machine)
* Harvard Architecture

## Instruction Map

* Since it is a 4-bit processor with equal instruction length, the total number of instructions this processor supports is 16.

* The table below shows the map of the instructions:

  | 3,2\1,0 | 00   | 01   | 11   | 10   |
  | ------- | ---- | ---- | ---- | ---- |
  | **00**  | PUSH0   | A0  | ADD  | SV   |
  | **01**  | PUSH1   | POP  | NAND | LD   |
  | **11**  | A2    | SWP  | LS   | BLE  |
  | **10**  | A1    | DUP  | RS   | BGT  |

  

