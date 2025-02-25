# Branch Instruction
 These are [[I Instruction]]s and manipulates the [[Program Counter|PC]] based on a condition and the immediate value of the [[instruction]]. The manipulation is done via addition. The 16 [[bit]] immediate (imm) is first [[Sign Extension|sign extended]] to 30 [[Bit|bits]]. Then the imm gets [[shift|left shifted]] by two (since the [[address]] must be a multiple of 4). After that 4 is added and lastly the current [[Program Counter|PC]] is added to the result. The [[Program Counter|PC]] is then set to the final result.
 
 ![[PC-branch.png]]