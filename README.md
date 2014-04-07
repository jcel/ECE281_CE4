ECE281_CE4
==========

Intro To Assembly Code

##Bug Report
When attempting to interact with the PRISM system, my computer was unable to start the program.  Even working with
Capt. Silva, reinstalling the Java Runtime Environment twice, and attempting to run as an administrator, the program
still refused to open.  I believe it may be a problem with downloading Java.  In order to recieve credit for my code
I have included the operations below.

###Section A: Memory Manipulation
LDAI: 0111 1001
OUT: 0100 10110000
LDAI: 0111 1000
OUT: 0100 11000100
LDAI: 0111 1011
OUT: 0100 11001011
"Loop" NOP: 0000
JMP: 1001 "Loop"

###Section B: Math
IN: 0101 10010000
ROR: 0011
ROR: 0011
ROR: 0011
ADDI: 0110 1100
"Loop" NOP: 0000
JMP: 1001 "Loop"

###Section C: Loops
IN: 0101 0011
"Loop" OUT: 0100 0000
ADDI: 0111 1111
OUT: 0100 0001
ADDI: 0111 1111
OUT: 0100 0010
ADDI: 0111 1111
JMP: 1001 "Loop"
