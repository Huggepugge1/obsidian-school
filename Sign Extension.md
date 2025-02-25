---
aliases:
- Sign Extended
---

If we have an [[I Instruction]] and we want to extract the immediate value, we can't just do it right away. This is because [[MIPS]] is a 32-[[Bit]] processor and the value is 16-[[Bit]]. Therefore we must convert the 16-[[Bit]] value to a 32-[[Bit]] value. This is done using sign extension. Sign extension means taking the [[Most Significant Bit]] and repeating it. This works because of [[2's Complement]].

# Examples
`00000000 01100100` -> `00000000 00000000 00000000 01100100`
`10000000 01100100` -> `11111111 11111111 10000000 01100100`

# Use Cases
Sign Extension is used for [[arithmetic]] operations, not [[logical]]. This is because logical operations are not affected by [[2's complement]].