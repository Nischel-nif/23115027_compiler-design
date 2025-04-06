# 23115027_compiler-design
Design a custom instruction for a given equation in compiler.

# Sum of Squares Compiler

This project demonstrates a simple compiler in C++ that calculates the sum of squares of two input numbers.

## Features

- Lexical Analysis
- Syntax Analysis
- Semantic Analysis
- Intermediate Code Generation
- Code Optimization (basic)
- Target Code Generation

## Input Format

Enter two integer values when prompted.

## Output

Displays the sum of squares of the two input numbers.

## Compilation and Execution

```sh
g++ main.cpp -o compiler
./compiler
```

## Example

**Input:**
```
Enter two integers: 3 4
```

**Output:**
```
Tokens: [3, 4]
Intermediate Representation: (3^2 + 4^2)
Result: 25
```
✅ Three Address Code (TAC)
Three Address Code (TAC) is an intermediate representation often used in compilers. Here’s what it would look like:

ini
Copy
Edit
t1 = 3 * 3
t2 = 4 * 4
t3 = t1 + t2
🛠️ Assembly Code (Register-based Example)
Assuming a simple register-based machine with instructions like LOAD, MUL, ADD, and storing to temporary variables (or registers), the assembly might look like this:

nginx
Copy
Edit
LOAD R1, 3       ; Load first number into R1
MUL R2, R1, R1   ; R2 = R1 * R1 → R2 = 9

LOAD R3, 4       ; Load second number into R3
MUL R4, R3, R3   ; R4 = R3 * R3 → R4 = 16

ADD R5, R2, R4   ; R5 = R2 + R4 → R5 = 25

PRINT R5          ; Output the result


## GitHub Link

[GitHub Repository](https://github.com/example/sum_of_squares_compiler)


