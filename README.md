# Microprocessor-8085-86

**8085 Microprocessor**
8085 Microprocessor is a predecessor of version 8086 Microprocessor, designed by Intel in 1976 with the help of NMOS technology. It includes a data bus of 8 bits, and 16 bits of the address bus, having a +5V voltage supply, and operates at 3.2 MHz single segment CLK.

It has an internal clock generator and functions on a clock cycle having a duty cycle of 50%. 246 total operational codes and 80 instructions are present in the 8085 Microprocessor.

**8086 Microprocessor**
8086 Microprocessor is an advanced version of the 8085 Microprocessor, designed by Intel in 1976. The number 8086 denotes the IC number of this microprocessor. It is a 16-bit microprocessor. It has 16 bits of the data bus, which is why it can read or write either 16 bits or 8 bits of data at a time. It has 20 bits of address lines that can access 220 address locations.
This directory contains assembly language programs for Intel 8085.

**8085 Microprocessor Architecture Diagram**
The 8085 microprocessor architecture diagram is as follows:
![8085-microprocessor-architecture-diagram](https://github.com/paritosh22/Microprocessor-8085-86/assets/122518099/80207035-6b08-4820-a8ed-88936b312f18)
![8085-microprocessor-pin-diagram](https://github.com/paritosh22/Microprocessor-8085-86/assets/122518099/01d3fb2f-97d2-4a1a-bde0-b9d6c2e1890d)

8085 Microprocessor Architecture Diagram
The 8085 microprocessor architecture has the following essential components:

**Accumulator (A):**
The accumulator is an 8-bit register used for arithmetic and logical operations. It holds one of the operands during calculations and stores the result.

**General-Purpose Registers (B, C, D, E, H, L):**
The 8085 microprocessor has six general-purpose registers, each of which is 8 bits. These registers can be used for data manipulation and storage.

**Stack Pointer (SP):**
The stack pointer is a 16-bit register that points to the top of the stack. The stack is used to store return addresses during subroutine calls, as well as local variables and other data.

**Program Counter (PC):**
Program counter is a 16-bit register that holds the memory address of the following instruction for fetching and executing. It automatically increments after each instruction fetch, allowing programs to execute the next instruction quickly.

**Flag Register (F):**
The flag register is a 8-bit register that contains several flags that indicate the status of certain conditions after arithmetic and logical operations. The flags are as follows:

**Carry Flag (C):**
Set if there is a carry or borrow during arithmetic operations.

**Zero Flag (Z):**
Set if the result of an operation is zero.

**Sign Flag (S):**
Set if the result of an operation is negative (MSB set).

**Parity Flag (P):**
Set if the result of an operation has even parity.

**Auxiliary Carry Flag (AC):**
Set if there is a carry or borrow from bit 3 to bit 4 during arithmetic operations.

**Address and Data Buses:**
The 8085 microprocessor has a 16-bit address bus, allowing it to address up to 64 KB of memory.

**Instruction Decoder and Control Unit:**
The instruction decoder interprets the fetched instructions and generates control signals to execute the corresponding operation. 

**Interrupts:**
Interrupts allow the microprocessor to respond to external events and handle them in a prioritized manner.

**Input/Output (I/O) Ports:**
The 8085 microprocessor has a limited number of I/O pins. It uses I/O ports to connect with external devices for input and output operations.

## **Programs**

 1: Write a program in 8085 to find the largest and smallest bytes from the list of 20 bytes stored starting from memory location C050 H. Store the largest byte and smallest byte in C070H and C071H.
 
 2: Write a program for 8085 to add the upper and lower nibble of ten 8-bit words stored in a table that starts from location 8B20H. Store the separate results in locations just after the table.
 
 3: Write a program for 8085 to check if the number in memory 2000H is even or odd. If the number is even store 22H in next memory location else store 11H in next memory.
 
 4: Write an 8085 assembly language program that converts a binary number located at memory address 3000H into a BCD (Binary Coded Decimal) format. The BCD result should be stored at memory locations 4000H, 4001H, and 4002H. Use subroutines 'CONVERT' and 'STORE' to carry out the conversion and storage operations.
 
 5: Write a program for 8085 to convert a 3-digit BCD number stored at memory locations 4000H, 4001H, and 4002H into its binary equivalent and store the result at memory location 5000H.
 
 6: Load any hex number in register D and E and add these numbers. If sum is greater than FFH, display 01H at output port FEH otherwise displaysum at same port.
 
 7: Load any hex number in register D and E and subtract these numbers. If there is borrow, display 01H at output port FEH, otherwise display 80H at same port.
 
 8: 16 bytes of data ar stored from address 3000H to 300FH. Transfer these blocks of data to destination whose starting address is 2000H.
 
 9: WAP to move a block of 10 bytes of data stored continuously at starting address 6000H to starting address 6004H.
 
 10: Check if bit D6 of a data is 1. If yes move it to registerD else insert FFH in register D.
 
 11: Write a program in 8085 to multiply two 8-bit data 05H and 08H by using repetitive addition method and store the result at memory location 2500H.

 12: Write a program for 8086 to add two 8-bit numbers stored in data1 and data2. Store the result in the variable 'result' and display it in ASCII format.
  
 13: Write a program in 8086 assembly to find the largest 8-bit number in an array and display it in ASCII format.
