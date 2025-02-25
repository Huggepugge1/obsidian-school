A decimal value. The radix point "floats" throughout the number, in contrast to fixed-point numbers. This way, a floating point number can be very small and very big.

One problem with floating point numbers is the so called [[Floating Point Imprecision]].

# IEEE Floating Point Standard
For a 32-[[Bit]] number, we divide the it into three parts.
- 1 [[Bit]] - Sign (s)
- 8 [[Bit]] - Exponent (e)
- 23 [[Bit]] - Mantissa or Fraction  (f)
This is evaluated as $(-1)^s * (1.f) * (2^{e-127})$. The `1.0` makes sure there is only one way to represent each number.

# Spacing
Because of how floating point numbers are made the distribution is non-uniform. This means that the amount of numbers being able to be represented between 0 and 1 is greater than between 2 and 3. In fact, they are spaced exponentially. This means the bigger the absolute value of the number is, the bigger the risk of the number being different then the one initially intended.

# Arithmetic's
## Addition
Procedure of $A+B$:
- [[Binary Shift|Shift]] the mantissas to match the exponents of $A$ and $B$
- Add the mantissas of $A$ and $B$
- Round to fit the result

## Multiplication
Procedure of $A*B$:
- multiply the mantissas of $A$ and $B$
- Add the exponents of $A$ and $B$
- Round and [[Binary Shift|shift]] to fit the result