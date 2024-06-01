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
    


2. created the verilog file and testbench file in github repository.

cloned it to machine using following command:-

    $ git clone https://github.com/Harshit2747/vsdsquadron-mini-internship
    $ cd vsdsquadron-mini-internship



    

simulate and run the code ,using following command:-

    $ iverilog -o vsdsquadron-mini-internship Harshit_rv32i.v Harshit_rv32i_tb.v
    $ ./vsdsquadron-mini-internship
    
And for output waveform give following command:-

    $ gtkwave Harshit_rv32i.vcd




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
    


    2.SUB r7, r1, r2
    
 

    3.AND r8, r1, r3



    4.OR r9, r2, r5



    5.XOR r10, r1, r4



    6.SLT r11, r2, r4



    7.ADDI r12, r4, 5



    8.SW r3, r1, 2



    9.LW r13, r1, 2




    10.BEQ r0, r0, 15


