# Micro_computer
It is a 16-bit microcomputer, which allows the user to use various operations like addition, subtraction and even multiplication with some logic.
This microcomputer followed the Vonneumann architecture. Which has a single memory for both RAM and ROM. The instructions should load into the RAM and the data should load into the ROM.
It takes 6-clock cycles to excute a command. and 3 commands required to complete an operation.

#HOW TO USE
Copy the code from each file and paste it in each verilog module.
For simulation copy the testbench file too.
Open the RAM module, The 16'bit value is the instruction and the instructions were executed in the order.
The first 4 bits of an instruction is the command (i.e load,add,sub and out).
The last 8 bits are the address of the data in the same memory which we will access later.
