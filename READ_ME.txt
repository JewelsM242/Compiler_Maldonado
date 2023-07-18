Project Name: Compiler

Description: A two person project focused on creating a series of compilers, interpreters, and parsers
capable from bringing the fictional C-like language (LB) into computer executable assembly code.

Timeline: Project was completed for a compiler-based speed competition and completed within 3 months.

My Contribution: Due to the scale of the project, my partner and I worked together on most aspects of the compiler. 
Notable components of the project are the following:
- Development of a parser that reads characters of a file and sorts them into "tokens" that is used by the interpreter.
- Creating a visitor-based system to correctly idetified tokens created by a parser.
- Designing a loading/unloading variable system allowing for minimual stack usage at low level assembly.
- Proper implementation of conditional statements, loops, and methods.
- Tranformation of Tokens into tree structure to allow for small optimizations. (Ex: v = 1 | v2 = v + 2 => v2 = 3)


