# Two's Complement
The biggest digit is negative, all others are positive. This means the [[Most Significant Bit|MSB]] in a 32-[[bit]] number has the value $-(2^{32})$. This way we can represent all numbers from $-(2^{31})$ to $2^31-1$.

## Subtraction
Idea: $A-B = A+(-B)$. So all we have to do is negate $B$ and add $A$.

### Negation of a Number
Process:
- Invert numer
- Add 1

### Result
$A-B = A + (!B + 1)$

## [[Overflow]]
[[Overflow]] is defined as [[carry]] in of the sign [[Bit|bits]] = [[carry]] out. So, if the resulting [[carry]] after the addition is of a different digit than the [[carry]] coming in to the sign [[Bit|bits]], an [[overflow]] has happened.![[Overflow Example.png|No overflow because carry in and carry out is the same]].