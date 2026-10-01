# Features of C Programming Language
C is a general-purpose, procedural, structured, and efficient programming language developed by Dennis Ritchie at Bell Labs in the early 1970s.
## Important Features of C
### 1. Simple and Easy to Learn
C has a relatively small set of keywords and a simple syntax, making it easier to learn programming fundamentals.
### 2. Middle-Level Language
C combines high-level programming features with low-level capabilities, such as pointers and memory manipulation.
### 3. Portable
C source code can be compiled on different platforms with little or no modification, provided suitable compilers and compatible system interfaces are available.
### 4. Fast and Efficient
C generally produces fast executable programs and provides efficient control over memory and system resources.
### 5. Structured Programming
C supports functions, loops, and conditional statements, allowing programs to be divided into smaller, manageable parts.
### 6. Modularity
A large program can be divided into smaller functions and separate source files, making it easier to test, debug, and maintain.
### 7. Pointer Support
C supports pointers, which allow programmers to work with memory addresses and implement data structures efficiently.
### 8. Dynamic Memory Allocation
C provides functions such as malloc(), calloc(), realloc(), and free() to manage memory at runtime.
### 9. Rich Set of Operators and Libraries
C provides arithmetic, logical, relational, bitwise, and other operators, along with standard libraries for common operations.
### 10. Case-Sensitive
C distinguishes between uppercase and lowercase letters. For example, sum, Sum, and SUM are different identifiers.
### 11. Extensible
Programmers can create their own functions and combine them with existing library functions to extend a program's functionality.
# High level vs low level
High-level languages provide a higher level of abstraction from computer hardware, making them easier for humans to write and understand. Low-level languages are closer to the hardware and provide more direct control over the computer's resources.
# first C program
    //print hello world
    #include<stdio.h>
    int main()
    {
    printf("Hello World");
    return 0;
    }
## 1. #include <stdio.h>
      #include <stdio.h>
This tells the preprocessor to include the stdio.h header file.<br>
A preprocessor is a program that processes source code before the compiler compiles it.<br>
stdio.h means Standard Input Output Header.<br>
It provides functions such as:<br>
printf()<br>
scanf()<br>
## 2. int main()
      int main()
main() is the starting point of a C program.<br>
When you run a C program, execution begins from main().<br>
int means that main() returns an integer value to the operating system.<br>
## 3. { }
    {
    printf("Hello, World!");
    return 0;
    }
Curly braces define the body/block of the main() function.<br>
Everything between { and } belongs to main().<br>
## 4. printf()
      printf("Hello, World!");
printf() is used to display/output something on the screen.<br>
Here:<br>
"Hello, World!" is a string.<br>
Therefore, the output is:<br>
Hello, World!
## 5. ;
    printf("Hello, World!");
The semicolon ; marks the end of a statement in C.<br>
For example:<br>
printf("Hello");<br>
printf("World");<br>
Each statement ends with ;.<br>
## 6. return 0;
      return 0;
This tells the operating system that the program finished successfully.<br>
For now, remember:<br>
return 0; → program ended successfully.<br>
# Syntax of a function
<img width="643" height="145" alt="image" src="https://github.com/user-attachments/assets/eae032ca-eb05-4a58-b55f-ede5b10a031d" />
## Example:
    int add(int a, int b)
    {
    int sum = a + b;
    return sum;
     }
# “Why do we use different files in C?”
We use different files in C to divide a large program into smaller, manageable modules. Header files (.h) generally contain declarations, while source files (.c) contain the corresponding implementations. This provides modularity, code reusability, easier maintenance, faster development, and better collaboration among developers.
<img width="766" height="393" alt="image" src="https://github.com/user-attachments/assets/9d5cc330-a237-4d93-981a-c0575206d558" />
# “Why not keep everything in one file?”
For small programs, we can use a single file. But in large projects, putting everything in one file makes the code difficult to understand and maintain. Separating code into multiple files makes each module easier to develop, test, modify, and reuse.
## Example
    project/
    │
    ├── main.c          → program entry point
    ├── calculator.c    → function implementations
    └── calculator.h    → function declarations
