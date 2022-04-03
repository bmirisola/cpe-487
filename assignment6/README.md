# Assignment 5: Vivado Lab 3 and 6
## All vhd and constraint files in .srcs folder of respective project

### Lab 4 Part 1: Hexcalc
- Code
	- Created a new project in Vivado called `hexcalc`
	- Followed the instructions from [Lab 4](https://github.com/kevinwlu/dsd/tree/master/Nexys-A7/Lab-4) to set up the Vivado project
	- Using code provided, edited the Design Sources and Constraints of the project
	- Ran synthesis and implementation
  	- Then generated bitstream
	- Programmed the Nexys A7-100T board with the generated `hexcalc.bit` file

- Usage
	- Plug keypad into Nexys A7-100T board
	- Type multi-digit hex number using keypad
	- Press `BTNU` button for the + operator
	- Type multi-digit hex number using keypad
	- Press `BTNL` button for the = operator to calculate number
	- Press `BTNC` button to clear display
	
		
		![hexcalc](./hexcalc/hexcalc.gif)
		
	
### Lab 4 Part 2: Hexcalc modifications
- Code
  	- Created project called hexcalc_modifications
	- Similar steps from Part 1, but source and constraint files are from [modifcations subfolder](https://github.com/kevinwlu/dsd/tree/master/Nexys-A7/Lab-4/Modifications)
	- Used code from respective project, but with the aforementioned procedure
	- Programmed the Nexys A7-100T board with the generated `hexcalc_1.bit` file
-  Usage
	- Same procedure for calculating number as before
	- Display will now supress leading zeros
	- Press `BTND` button for - operator
		
		![hexcalc_modifications](./hexcalc_modifications/hexcalc_modifications.gif)
