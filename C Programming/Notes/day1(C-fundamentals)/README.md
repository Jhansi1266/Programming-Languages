<img width="892" height="427" alt="image" src="https://github.com/user-attachments/assets/193f5470-d42c-4d3d-a744-2972a0cefce1" /><br>
## History of programming
Long ago people used to remember the codes in binary format<br>
### 1. Before Programming Languages — Machine Code<br>
1940s<br>
Early computers were programmed using machine language.<br>
Machine language consists of 0s and 1s.<br>
#### Example:
     10110000 01100001
The CPU can directly understand machine instructions.
#### Problems
    Very difficult for humans to write
    Difficult to remember
    Machine-dependent
    Difficult to debug
    Programs were very long
This created the need for assembly language.
### 2. Assembly Language
Around 1940s–1950s<br>
Assembly language replaced binary instructions with mnemonics.
#### For example:
    MOV A, B
    ADD A, C
#### Instead of writing binary directly, programmers could use words such as:<br>
    MOV ADD SUB JMP
An assembler converts assembly language into machine code.
#### Important
Machine Code<br>
→ directly understood by CPU<br>
Assembly<br>
→ converted by an Assembler
## Why c?
C was developed at Bell Labs in the early 1970s by Dennis Ritchie. UNIX was initially developed in assembly language, but assembly is machine-dependent and difficult to port. C provided better portability while still giving programmers low-level hardware control and good performance. Therefore, UNIX was largely rewritten in C around 1973.
## what is portable?
Portability means the ability to use the same program or source code on different computer systems with little or no modification.
## Why is C called a middle-level language?
Because it combines high-level programming features with low-level hardware access.
## Is C completely portable?
No. C is relatively portable, but hardware-, OS-, compiler-, or implementation-specific code may require changes.

