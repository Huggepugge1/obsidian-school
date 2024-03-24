# Signed magnitude
The first [[bit]], the [[Most Significant Bit|MSB]], is used to determine the sign of the number.

## Problems
If we want to check for zero we have to check for 0 and -0 because in signed magnitude they are not the same. This is because the [[byte]] $10000000_{binary} (-0) = 00000000_{binary} (0)$. We also have to separate positive and negative addition. Subtraction becomes even more messy becuase of the following:
- if A > B -> A-B
- if A < B -> -(B-A).

## Replacement
[[Two's Complement]]