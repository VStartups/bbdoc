---
description: what's a procedural programming language?
cover: >-
  https://images.unsplash.com/photo-1557324232-b8917d3c3dcb?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHwxMHx8cGFzY2FsJTIwcHJvZ3JhbW1pbmclMjBsYW5ndWFnZXxlbnwwfHx8fDE3MjE0NTIyMDd8MA&ixlib=rb-4.0.3&q=85
coverY: 0
---

# Procedural Programming Language

A procedural language is a type of programming language where programs are structured around procedures or routines (functions/subroutines) that perform specific tasks on data. It emphasizes a step-by-step approach to problem-solving, where instructions are executed sequentially in order to achieve a desired outcome. Examples include C, Pascal, and FORTRAN, where programs are organized into procedures that manipulate data directly.

Example Pascal Code :&#x20;

`program MaxNumber;`

`// Function to find maximum of two numbers function Max(a, b: Integer): Integer; begin if a > b then Max := a else Max := b; end;`

`var num1, num2, maxNum: Integer;`

`begin num1 := 10; num2 := 5; maxNum := Max(num1, num2); writeln('Maximum of ', num1, ' and ', num2, ' is ', maxNum);`&#x20;

`end.`
