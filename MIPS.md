An [[Instruction Set]] for old 32-[[Bit]] [[Central Processing Unit|CPU]]s. It is not very simple and nowadays outdated. Although you would never see one in a computer today you might find some in printers and other non performance focused appliances.

# [[Register]] Names
MIPS has 32 general purpose [[Register|regisers]]. They are called R0-R31. There is a problem though and that is the fact that it is hard to remember what 32 different things are used for. Therefore we give them better names.

| Number | Name | Function |
| ------ | ---- | -------- |
| R0 | $0 | Always 0 |
| R1 | $ak | Reserved Temp |
| R2 | $v0 | Return Value |
| R3 | $v1 | Return Value |
| R4 | $a0 | [[Procedure]] Argument |
| R5 | $a1 | [[Procedure]] Argument |
| R6 | $a2 | [[Procedure]] Argument |
| R7 | $a3 | [[Procedure]] Argument |
| R8 | $t0 | Caller Save |
| R9 | $t1 | Caller Save |
| R10 | $t2 | Caller Save |
| R11 | $t3 | Caller Save |
| R12 | $t4 | Caller Save |
| R13 | $t5 | Caller Save |
| R14 | $t6 | Caller Save |
| R15 | $t7 | Caller Save |
| R24 | $t8 | Caller Save |
| R25 | $t9 | Caller Save |
| R16 | $s0 | Callee Save |
| R17 | $s1 | Callee Save |
| R18 | $s2 | Callee Save |
| R19 | $s3 | Callee Save |
| R20 | $s4 | Callee Save |
| R21 | $s5 | Callee Save |
| R22 | $s6 | Callee Save |
| R23 | $s7 | Callee Save |
| R26 | $k0 | Reserved for [[Operating System]] |
| R27 | $k1 | Reserved for [[Operating System]] |
| R28 | $gp | Global Pointer |
| R29 | $sp | [[Stack Pointer]] |
| R30 | $gp | Frame Pointer |
| R31 | $ra | Return [[Address]] |