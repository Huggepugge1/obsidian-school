---
aliases:
	- R Instructions
---

# R - Three Operand, Non [[Immediate Instruction]]

| ***Section*** | opcode | rs | rt | rd | shamt | funct |
| ------------- | ------ | -- | -- | -- | ----- | ----- |
| ***Size*** | 6 [[Bit|bits]] | 5 [[Bit|bits]] | 5 [[Bit|bits]] | 5 [[Bit|bits]] | 5 [[Bit|bits]] | 6 [[Bit|bits]] |
| `add R8, R17, R18` | 00000 | 10001 | 10010 | 01000 | 00000 | 100000 |

## Sections
- opcode - Describes what operation to do. Addition has one, jump one, or one etc.
- rs - source 1. First [[register]] to use
- rt - source 2. Second [[register]] to use
- rd - destination. Destination [[register]]
- shamt - [[Binary Shift|shift]] amount.
- funct - Function selector. Using [[two's complement]], addition and subtraction is the same thing. Therefore we use the same opcode (0). The only thing we chage is the funct from 32 (addition) to 34 (subtraction).