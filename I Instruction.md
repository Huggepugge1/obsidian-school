# I - Three Operand, [[Immediate Instruction]]

| ***Section*** | opcode | rs | rt | imm |
| ------------- | ------ | -- | -- | --------- |
| ***Size*** | 6 [[Bit\|bits]] | 5 [[Bit\|bits]] | 5 [[Bit\|bits]] | 16 [[Bit\|bits]] |
| `addi R8, R17, 10` | 001000 | 10001 | 10010 | 00000000 00001010 |

## Sections
- opcode - Describes what operation to do. Addition has one, jump one, or one etc.
- rs - source 1. First [[Register]] to use
- rt - source 2. Second [[Register]] to use
- Imm - Constant / Immediate