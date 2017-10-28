# README

Author: VG101 SU16 TA Group, VG101 FA17 TA Group    
Date: Decemeber 27, 2017

***

This is a README file for your homework template in C. You must follow the instructions carefully to understand how to use this template.

__Students who do not follow this template will lose great points.__

This file is also a sample README (without algorithm) for you. If you are not able to render markdown file, you could go [here](https://github.com/Reapor-Yurnero/VG101-FA17/tree/master/ctemplate) to view it in correct format online.

## USAGE:

### Stage 1. Coding

For each exerise, write your corresponding functions in ex1.c, ex2.c, etc. each file should contain sub-functions to solve corresponding problems, and also it should always include "assignment.h".

Remember to declare all the other sub-functions you used for all exercises in `assignment.h`.

If one assignment contains less than 4 exercises, delete the extra `.c` files, the corresponding function declarations in `assignment.h` and the extra cases in switch condition in `main.c`.

If there's more than 4 exercises, e.g. 5 exercises existing. Create `ex5.c`, add 
```
void ex5();
```
into `assignment.h` and add
```
case 5:
    ex5();
    break;
```
to the switch conditions in `main.c`.

### Stage 2. Compiling:

- For editor user, run the following command in your command line (terminal, cmd):
```
gcc -Wall main.c ex1.c ex2.c ex3.c ex4.c -o main
```
This is for 4 exercise condition, add or remove exi.c in this line under other cases.

If you want to know how this is working, check for [GNU's online documents](https://gcc.gnu.org/onlinedocs/) or simply type `man gcc` if you have installed the manualscript for gcc on your computer.

- For Clion users: please refer to the [Clion guide](https://github.com/Reapor-Yurnero/VG101-FA17/blob/master/docs/Clion_tutorial/clion_guide.md) we have offered. A sample `CMakeLists.txt` has been offered as well.

### Stage 3. Executing and Debugging

Execute your output file. Either (in command line) run
```
./main -exi
```
to test one specific i-th exercise (this what we graders will do) or run
```
./main
```
and then follow the input prompts can test different exercises repeatedly.

For Clion click "Run" then input the exercise number (an integer) into program to run a specific exercise and test its function. You can use the powerful tools Clion offered to debug.

## Some more suggestions:

1. We will compile just as mentioned, a compling-fail code will get zero point. Make sure your code can be compiled successfully.
2. This template aims to force you to split a long main functions into parts of sub-functions. Please follow the minimum requirement on the amount of sub-functions.
