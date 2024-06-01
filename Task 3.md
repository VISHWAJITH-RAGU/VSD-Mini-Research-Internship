# TASK-3

 Functional simulation experiment using RISC-V Core Verilog netlist and testbench.
   *  IVERILOG:-Icarus Verilog, commonly referred to as IVerilog, is an open-source Verilog simulation and synthesis tool. It supports a wide range of Verilog standards and is used for designing and testing digital circuits. IVerilog is popular for its flexibility, allowing users to simulate complex designs and generate netlists for various FPGA and ASIC platforms. It is widely used in both educational and professional settings for hardware design and verification.

   *  GTKWAVE:- GTKWave is an open-source waveform viewer used for visualizing simulation results from digital circuit designs. It is commonly used in conjunction with simulation tools like Icarus Verilog.It is a fully featured GTK+ based waveform viewer for Unix and Win32, capable of displaying signal waveforms dumped in a variety of formats.

     
1. 
INSTALL IVERILOG:
using follwing command:-

    $ sudo apt install iverilog 
    
  ![Screenshot from 2024-05-31 15-02-55](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/5399c962-c922-467b-a5ad-39f0d7922b8f) 

INSTALL GTKWAVE:
using following command:-

    $ sudo apt install iverilog gtkwave
    
![Screenshot from 2024-05-31 15-04-33](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/37703910-bf49-47c9-98a2-7eac2c617dec)


2. created the verilog file and testbench file in github repository.

cloned it to machine using following command:-

    $ git clone [https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship]
    $ cd vsdsquadron-mini-internship

![Screenshot from 2024-05-31 15-10-07](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/c0785417-51bd-4088-9914-90a1b710729a)

![Screenshot from 2024-05-31 15-11-49](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/1b064d6d-9e07-4b58-b9ac-11fa392f3360)

    
simulate and run the code ,using following command:-

    $ iverilog -o vsdsquadron-mini-internship vjith_rv32i.v vjith_rv32i_tb.v
    $ ./vsdsquadron-mini-internship

![Screenshot from 2024-05-31 15-14-48](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/b6958a2a-1996-4839-8f3f-9850dd463851)

![Screenshot from 2024-05-31 15-15-39](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/8e083602-0dd6-4f4c-bf0a-a954ac32ccb9)

And for output waveform give following command:-

    $ gtkwave vjith_rv32i.vcd

![Screenshot from 2024-05-31 15-16-35 (1)](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/dd430df4-1ff5-4d10-9ee8-7213f64aeccb)


3.Analyze the wave form of each instruction using gtkwave.

following instruction are:-
   1.ADD r6, r2, r1
    
   2.SUB r7, r1, r2
    
   3.AND r8, r1, r3
   
   4.OR r9, r2, r5
    
   5.XOR r10, r1, r4
    
   6.SLT r11, r2, r4
    
   7.ADDI r12, r4, 5
    
   8.SW r3, r1, 2
    
   9.SRL r16, r14, r2
    
   10.BEQ r0, r0, 15
  

Let's analyze:-

    1.ADD r6, r2, r1
    
![Screenshot from 2024-06-01 09-51-38](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/da504703-371f-45c0-92fc-149a5996e5e7)


    2.SUB r7, r1, r2
    
 ![Screenshot from 2024-06-01 09-51-41](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/c7c79cfe-ecd0-4680-8154-599435991c1d)


    3.AND r8, r1, r3

![Screenshot from 2024-06-01 09-51-46](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/aa2da411-f1e1-4886-a174-2b4ad971c60b)


    4.OR r9, r2, r5

![Screenshot from 2024-06-01 09-51-52](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/e5afa2c8-d607-4161-9984-0659e7df9886)


    5.XOR r10, r1, r4

![Screenshot from 2024-06-01 09-52-19](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/58464c10-29b6-4add-9b8a-0ea4d6a7bed0)


    6.SLT r11, r2, r4

![Screenshot from 2024-06-01 09-52-23](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/c9479b09-b5a3-43cc-b5f6-345507ce6b0b)


    7.ADDI r12, r4, 5

![Screenshot from 2024-06-01 09-52-34](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/70d48204-2fdf-4c70-ac74-f11066da73d4)


    8.SW r3, r1, 2

![Screenshot from 2024-06-01 09-52-38](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/bbee2389-b728-4574-ac55-f41ebf6c376d)


    9.LW r13, r1, 2

![Screenshot from 2024-06-01 09-52-56](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/a26e463f-6457-45f3-814e-cb322fcaf146)


    10.BEQ r0, r0, 15

![Screenshot from 2024-06-01 09-53-09](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/63db96f4-2edc-4956-bbee-acbf1573700f)

Full 5-stage instruction pipeline and pc-increment description Waveform

![Screenshot from 2024-06-01 16-32-06](https://github.com/VISHWAJITH-RAGU/VSD-Mini-Research-Internship/assets/115524986/394ae3e1-fd3a-4c50-a064-01ce742321fa)
