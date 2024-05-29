#TASK 1
# Writing a C code to count the sum of numbers from 1 to n and running this program using RISC-V simulator
## Writing a C code to count sum of numbers from 1 to n
#### 1. First I opened terinal and wrote code to make and open a new C file in leafpad as shown below:
#### 2. Then I wrote my code in leafpad as shown below:
#### 3. And then compiled and run in terminal itself to check, and got the desired output.
#### 4. Tried for different value of n and got the results, like n=100.
## Running above program in RISC-V Simulator
#### Once I have ran the code in terminal, I need to run in RISC-V simulator so for that their is special set of code needed which I have done in following steps:
#### 1. First I wrote a code to compile it with RISC-V gcc compiler with option 1 so it will generate a file with .o extension.
#### 2. Next I wrote a code riscv-unknown-elf-objdump -d sum1ton.o for getting the assembly code for the above c program, and got many assembly codes. Reduced the number of assembly codes just by writing | less after the command. We wanted main section so I searched for the main. The byte address for main was found to be 10184 and got 15 instrusctions when using option 1. It is observed that the address of each consecutive instructions get incremented by 4.
#### 3. Next I run the same commands but with different option, instead of O1, I used Ofast. This time I got less number of instructions i.e. 12. This shows that the instrunctions in assembly codes of the file changes for different options of compilation.
## That is it for Task1
