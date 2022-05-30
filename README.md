# MIXEDSOC
This repository explains the implementation of Mixed Signal SoC (RISC-V based Core + PLL) on FPGA.
Tools used:
>>>>>  Makerchip is a free web-based IDE 
>>>>>  Icarus Verilog is a Verilog simulation and synthesis tool.
>>>>>  GTKWave is a waveform viewer.
BLOCK DIAGRAM 
![image](https://user-images.githubusercontent.com/104430712/170943118-9ec8b027-0cf0-4e91-9d68-46a17b84a407.png)

Steps to convert TL-Verilog to Verilog or SystemVerilog
SandPiper is a code generator that generates readable, well-structured, Verilog or SystemVerilog code from the given TL-Verilog code.
INSTLLATION COMMAND : pip3 install sandpiper-saas
![image](https://user-images.githubusercontent.com/104430712/170943583-060ecf55-7463-4f54-9cab-1a456f16540b.png)

git clone https://github.com/shivanishah269/vsdfpga.git

![image](https://user-images.githubusercontent.com/104430712/170943618-91744ded-2da9-428a-8b6b-6fd12baf923a.png)

Steps for RTL Simulation of RVMYTH+PLL using iverilog
iverilog rvmyth_pll_tb.v rvmyth_pll.v clk_gate.v
./a.out
gtkwave rvmyth_pll.vcd

![image](https://user-images.githubusercontent.com/104430712/170943810-db227789-72d2-4ee4-b24a-8615ba1bed22.png)

![image](https://user-images.githubusercontent.com/104430712/170943851-1e5da5f6-fb07-4221-a9f9-ad6cb33ffe7a.png)

Acknowledgements
Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd.
Steve Hoover, Founder, Redwood EDA
Shivani Shah,VSD
