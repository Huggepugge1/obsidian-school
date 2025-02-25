Multiplication is done the same way as in base-10. The only difference is that we have limited space in computers. If there is an [[Overflow]] and we want to handle it, we [[Binary Shift|shift]] the [[Bit|bits]] to the right. Something noteworthy is that a $n$ [[Bit]] $*$ $n$ [[Bit]] multiplication gives a $2n$ [[Bit]] answer. In [[MIPS]], there is two [[Register|registers]], HI and LO to keep track of all 64 [[Bit|bits]] in a 32 [[Bit]] system.

# Multiplicators
To multiply there is two choices, do it like humans do ([[Parallell]] multiplication) or using addition over and over (serial multiplication). The tradeoff is time against space. [[Parallell]] multiplication is faster because we can do many steps at once but also way bigger in terms of area because we need a lot of adders.

## Serial Multiplication
A multiplication consists of a multiplicand and a multiplier. First the [[Least Significant Bit|LSB]] of the multiplier is checked. If this is one we add the multiplicand to the result. Then the multiplicand is [[Binary Shift|shifted]] to the left by 1 and the multiplier is [[Binary Shift|shifted]] to the left by one. Then the process is repeated.

## [[Parallell]] Multiplication
[[Parallell]] multiplication is way faster because as the name suggests we do it in [[Parallell]]. The reason we did not do this in the 1900's is that each [[Parallell]] multiplicator needs a lot of adders to work. This was not feasible due to physical size limitations.