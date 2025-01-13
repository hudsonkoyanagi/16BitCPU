# 16 Bit CPU Design

This is a kind of proof of concept project on the way to a more featureful 32-bit cpu design that I have been playing around with. It is built in [Logism Evolution](https://github.com/logisim-evolution/logisim-evolution).

It is a fairly simple implementatin of a custom 16-bit ISA with support for some of the most basic computer instructions including arthimetic, logic, branching and memory access.

The instruction set can be found in *isa.txt*.

The only way to program the CPU is through manually writing binary instructions into the ROM which feeds into the program counter.

Results of operations and some miscellaneous state variables are displayed through 7-bit number displays at the top of the CPU schematic.

## CPU Layout
![CPU Layout](https://github.com/hudsonkoyanagi/16BitCPU/blob/master/images/cpu.png)

## Arithmetic Logic Unit
![ALU Design](https://github.com/hudsonkoyanagi/16BitCPU/blob/master/images/alu.png)

## Control Unit
![Control Unit Design](https://github.com/hudsonkoyanagi/16BitCPU/blob/master/images/control_unit.png)

## Register Page
![Register Page](https://github.com/hudsonkoyanagi/16BitCPU/blob/master/images/registers.png)

