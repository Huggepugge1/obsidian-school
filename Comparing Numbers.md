First $A-B$ is done. Then 4 checks are done on the result.

# Unsigned Operands
- ZERO: Equality
- [[Carry]] = 0: $A>=B$
- [[Carry]] = 1: $A<B$
- SIGN: no meaning
- [[Overflow]]: no meaning

# [[Two's Complement]] Operands
- ZERO: Equality
- [[Carry]] No meaning
- SIGN and [[Overflow]]
	- S [[Exclusive Or|XOR]] O = 0: $A>=B$
	- S [[Exclusive Or|XOR]] O = 0: $A<B$