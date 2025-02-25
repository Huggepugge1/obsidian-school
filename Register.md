---
aliases:
  - registers
  - regisers
---
# Register
A register is one component of the [[Central Processing Unit|CPU]] where data currently being used is stored. For example, if an addition instruction would be performed, `add rax, rbx`([[x86_64]]), rax and rbx are registers where rbx is added to rax and the resulting value being stored in rax. In a [[Central Processing Unit|CPU]], there are very few registers ([[MIPS]] uses 32 general purpose registers) but they are very fast (about 200 times faster than [[memory]]).


## Special Registers
Some registers have predetermined use cases and should not be tampered with.

==OBS! This text uses [[MIPS]] as an example! All of the registers below may and will probably not be the same in other instruction sets!==
### R0
This register always has the value 0.

### R29 / R31
These are used when [[Procedure|functions]] are called.

### [[Program Counter|PC]]
[[Program Counter]] points to the [[address]] of the current instruction in [[memory]].

### Hi & Lo Results of Multiplication
I don't know how computers do multiplication but something about that.

### [[Floating Point]] Registers
Something about [[floating point]] numbers.

### Control Registers
Used for errors and status codes.