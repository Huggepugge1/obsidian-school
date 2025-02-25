The biggest digit is negative, all others are positive. This means the [[Most Significant Bit|MSB]] in a 32-[[Bit]] number has the value $-(2^{32})$. This way we can represent all numbers from $-(2^{31})$ to $2^31-1$.

# Subtraction
Idea: $A-B = A+(-B)$. So all we have to do is negate $B$ and add $A$.

# Negation of a Number
Process:
- Invert numer
- Add 1

# Result
$A-B = A + (!B + 1)$

# [[Overflow]]
[[Overflow]] is defined as [[Carry]] in of the sign [[Bit|bits]] = [[Carry]] out. So, if the resulting [[Carry]] after the addition is of a different digit than the [[Carry]] coming in to the sign [[Bit|bits]], an [[Overflow]] has happened.![[Overflow Example.png|No overflow because carry in and carry out is the same]].