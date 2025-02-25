==OBS! Everything below is related to [[MIPS]]. Things may be different in other architectures!==

A jump instruction means set the [[Program Counter|PC]] to the value. These are [J-Instructions](J\Instruction) meaning the [[Address]] is only 26 [[Bit|bits]] long. This means we can't just set the [[Program Counter|PC]] to the target. We solve this by only replacing 26 [[Bit|bits]] of the [[Program Counter|PC]]. This is done by [[Binary Shift|left shifting]] the immediate by two and merging the [[Program Counter|PC]] and the result of the [[Binary Shift|shift]].

![[PC-Jump.png]