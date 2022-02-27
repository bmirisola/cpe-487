# Assignment 3: Vivado Lab 1
## All vhd and constrain files in .srcs folder of respective project

### Lab 1 Part 1: LED decoder
- Code
	- Created a new project in Vivado called `leddec` (LED Decoder)
	- Followed the instructions from [Project 1 - LED Decoder](https://github.com/kevinwlu/dsd/tree/master/Nexys-A7/Lab-1#project-1---led-decoder) to set up the Vivado project
	- Using code provided, edited the Design Sources and Constraints of the project
	- Ran synthesis, implementation, and generated bitstream
	- Programmed the Nexys A7-100T board with the generated `leddec.bit` file

- Usage
	- Slide switches 0, 1, 2, and 3 to display the value of 4-bit hex digit from 0 to F
	- Slide switches 13, 14, and 15 to determine which display is illuminated
		
		![LED Decoder GIF](./leddec/leddec.gif)
	

### Lab 1 Part 2: Single-digit hex counter
- Code
	- Similar steps from Project 1, but in reference with [Project 2 - Hex Counter](https://github.com/kevinwlu/dsd/tree/master/Nexys-A7/Lab-1#project-2---hex-counter)
	- Used code from respective project, but with the aforementioned procedure
	- Programmed the Nexys A7-100T board with the generated `hexcount.bit` file
-  Usage
	- The least significant 7-segment decoder automatically cycles from 0 to F
		
		![4-bit_Hex_Counter GIF](./hexcount/hexcount.gif)

				[README.md file style inspired by Calvin Zheng](https://github.com/Crystal-Link/CPE487-Work/blob/main/Assignments/Assignment%203%20-%20Vivado%20Lab%201/README.md)
