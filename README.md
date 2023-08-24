# monty
This repository contains a C program that implements a Monty bytecode interpreter.
The Monty bytecode interpreter is a program that reads and executes Monty bytecode files.

WHAT THE PROGRAM DOES
This C program is a Monty bytecode interpreter. It takes a file as an argument, opens the file, and reads the instructions in the file, line by line. For each line read, the interpreter executes the instructions on that line.

The Monty bytecode is made up of a small number of instructions that can be used to manipulate a stack. The instructions are:

push: Pushes an integer onto the stack.
pop: Pops an integer off the stack.
swap: Swaps the top two elements on the stack.
add: Adds the top two elements on the stack and pushes the result onto the stack.
sub: Subtracts the top two elements on the stack and pushes the result onto the stack.
mul: Multiplies the top two elements on the stack and pushes the result onto the stack.
div: Divides the top two elements on the stack and pushes the result onto the stack.
mod: Performs the modulus operation on the top two elements on the stack and pushes the result onto the stack.
pall: Prints the contents of the stack, starting from the top.
The interpreter reads each line and performs the specific operation on the given stack.

USAGE
To use the program, you need to compile it and then run it with the name of the Monty bytecode file as an argument. For example, to run the program on the file bytecodes/000.m, you would type the following command:

./monty bytecodes/000.m
The program will then execute the instructions in the file and print the results to the standard output.

REQUIREMENTS
The program requires the following:
	1. A C compiler
	2. The GNU Make utility

LICENSE
Vincent Mugendi 2023.

