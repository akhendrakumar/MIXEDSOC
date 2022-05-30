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

FPGA IMPLEMENTATION
![image](https://user-images.githubusercontent.com/104430712/170983236-b8ee9c35-2f7c-43db-806f-52f2e9aece9d.png)
![image](https://user-images.githubusercontent.com/104430712/170983264-07346e2d-1e72-45d9-8692-09a9bf83dc68.png)
![image](https://user-images.githubusercontent.com/104430712/170983282-269608c8-662a-44e1-8245-c7bcf338fa69.png)
![image](https://user-images.githubusercontent.com/104430712/170983307-33fe4f5b-4a01-41bf-880e-a2959073adca.png)
![image](https://user-images.githubusercontent.com/104430712/170983322-f432e1c7-6b53-415d-a8e5-79cfb35410c1.png)
![image](https://user-images.githubusercontent.com/104430712/170983341-34dcf49c-b9d5-4795-870e-7c684b8965e3.png)
![image](https://user-images.githubusercontent.com/104430712/170983359-6de067bd-19f7-4a50-b43b-a5a7c1b832ee.png)
![image](https://user-images.githubusercontent.com/104430712/170983377-49ff7e5f-be21-45a6-9736-616d68432e0d.png)
![image](https://user-images.githubusercontent.com/104430712/170983407-eb7809e3-ea37-469a-af40-50dabb10134a.png)
![image](https://user-images.githubusercontent.com/104430712/170983423-526e1751-7700-4aa1-aa99-e6c076b90908.png)
![image](https://user-images.githubusercontent.com/104430712/170983441-11974971-e79f-473b-9ff6-cc174361faf0.png)
![image](https://user-images.githubusercontent.com/104430712/170983459-16e91c86-a7d2-444b-97f2-51fa9687cec7.png)
![image](https://user-images.githubusercontent.com/104430712/170983478-57f88a7b-2e85-49e3-86b3-d026283cf106.png)
![image](https://user-images.githubusercontent.com/104430712/170983492-12ec639f-e557-4a1d-ba8a-5b764e647c7c.png)
![image](https://user-images.githubusercontent.com/104430712/170983513-76bbe608-5d18-4083-b150-5d444a0d012f.png)
![image](https://user-images.githubusercontent.com/104430712/170983533-1a29fc0d-4016-45c8-a010-34c9c88d6216.png)
![image](https://user-images.githubusercontent.com/104430712/170983552-eda55d8e-b2c4-4d11-9557-fd4c0c0d95f6.png)






Acknowledgements

Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd.

Steve Hoover, Founder, Redwood EDA

Shivani Shah,VSD
