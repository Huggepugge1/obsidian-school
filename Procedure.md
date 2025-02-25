---
aliases: Procedures, Function, Functions, Subroutine, Subroutines,
---

A procedure, also known as a function or subroutine, is a block of code that can be called and can also return with a value. When we call these we can also call them with arguments meaning different things can happen depending on what arguments we call it with.

# What Happens During a Procedure
- Put data where the procedure can access it
- Call the procedure
	- JAL instruction, Jump-And-Link
		- This stores the return [[Address]] ([[Program Counter|PC]] + 4) in $ra (return [[Address]], R31)
		- Jumps to the procedures [[Address]]
- Put the results where the caller can access them
- Return to the caller and continue execution from there
	- JR instruction, Jump-Return
		- This Jumps back to the [[Address]] stored in $ra (R31)

# [[Stack]]
Procedures often use the [[Stack]] in order for them to save [[Register|registers]]. They do this by  [[Push|pushing]] the current values of the [[Register|registers]] to be saved onto the [[Stack]]. If they want to retrieve the values they can simply just [[Pop]] them of the [[Stack]] and set the [[Register|registers]].