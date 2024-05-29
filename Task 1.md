# TASK 1

## Writing a C code to count the sum of numbers from 1 to n and running this program using RISC-V simulator

## Writing a C code to count sum of numbers from 1 to n

![image](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/da1d78a8-caa9-48c4-9545-f951dfa0ae5c)

#### 1. First I opened terinal and wrote code to make and open a new C file in leafpad as shown below:

![image](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/1318eaeb-8b67-4517-b1ba-180d00fc33c8)

#### 2. Then I wrote my code in leafpad as shown below:

![image](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/28f947da-b39a-4887-adeb-531860eb4af6)

#### 3. And then compiled and run in terminal itself to check, and got the desired output.

![image](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/866b0cce-ff19-4c8b-8315-437625daa5a5)

#### 4. Tried for different value of n and got the results, like n=100.

![image](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/1920c642-6bdf-4703-b10c-d51a3cbf4a30)

![image](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/f152f0fb-6da1-4adb-bf05-cee12ef897e9)

## Running above program in RISC-V Simulator

#### Once I have ran the code in terminal, I need to run in RISC-V simulator so for that their is special set of code needed which I have done in following steps:

#### 1. First I wrote a code to compile it with RISC-V gcc compiler with option 1 so it will generate a file with .o extension.

![image](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/f3fd6671-69f1-437d-985c-77187c4e506e)

#### 2. Next I wrote a code riscv-unknown-elf-objdump -d sum1ton.o for getting the assembly code for the above c program, and got many assembly codes. Reduced the number of assembly codes just by writing | less after the command. We wanted main section so I searched for the main. The byte address for main was found to be 10184 and got 15 instrusctions when using option 1. It is observed that the address of each consecutive instructions get incremented by 4.

![image](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/8af0aa9d-8252-4ec9-b5b4-65b04f749ec2)

![image](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/7274840c-4d06-465f-a91c-bbe28caf5d69)

![image](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/3b957a9d-b2ed-4c6e-962f-7a784e086dfb)

#### 3. Next I run the same commands but with different option, instead of O1, I used Ofast. This time I got less number of instructions i.e. 12. This shows that the instrunctions in assembly codes of the file changes for different options of compilation.

![image](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/40ebbe8b-99ba-4ce0-9221-11ee18ced3b4)

## That is it for Task 1
