# ISA
I spent months designing ISAs because I was bored and the only way to justify wasting the time is to post it on github for other people. 

At some point in the middle of the first ISA I had massive hallucinations about how ISAs work and I dont entirely know if thats gone yet.

- isa0 - isa11 = 1st ISA
- smi/smi2 = 2nd ISA
- war2 = 3rd ISA

The second ISA is kinda incomprehensible to read because I was barely formatting it and it's entirely built for my own mind. 

The goal was to create the best ISA for modern von neumann chips.

I can try to explain some recurring themes in the ISAs. For example, the Variable-length obsession is me trying to balance decode speed with compression, but I'm greedy. 

In the third ISA the opcode (6 bits) was intended to be the index into a small table that outputs the size of the instruction.
