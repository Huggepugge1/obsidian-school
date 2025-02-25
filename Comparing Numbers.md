# Comparing Numbers
First $A-B$ is done. Then 4 checks are done on the result.

## Unsigned Operands
- ZERO: Equality
- [[CARRY]] = 0: $A>=B$
- [[CARRY]] = 1: $A<B$
- SIGN: no meaning
- [[OVERFLOW]]: no meaning

## [[Two's Complement]] Operands
- ZERO: Equality
- [[Carry]] No meaning
- SIGN and [[OVERFLOW]]
	- S [[Exclusive Or|XOR]] O = 0: $A>=B$
	- S [[Exclusive Or|XOR]] O = 0: $A<B$