# Assignment 4: Vivado Lab 2
## All vhd and constraint files in .srcs folder of respective project

### Lab 2 Part 1: Four-Digit Hex Counter
- Code
	- Created a new project in Vivado called `hex4count`
	- Followed the instructions from [Lab 2](https://github.com/kevinwlu/dsd/tree/master/Nexys-A7/Lab-2) to set up the Vivado project
	- Using code provided, edited the Design Sources and Constraints of the project
	- Ran synthesis and implementation
  - Opened the implemented design and edited the configuration modes to include "Master SPI x1"
  - Then generated bitstream
	- Programmed the Nexys A7-100T board with the generated `hex4count.bit` file

- Usage
	- The left group of leds automatically cycle from 0 to F and overflow when one to its left has reached the max value.
		
		![4 digit counter GIF](./hex4count/hex4count.gif)
	
### Lab 2 Part 2: Save Four-Digit Hex Counter to Flash
- Code
	- Moved the blue MODE jumper on the board from JTAG to QSPI (Quad-SPI)
    - Documentation can be found [here](https://digilent.com/reference/_media/reference/programmable-logic/nexys-a7/nexys-a7_rm.pdf) in Sections 2.1, 2.2, and 3.2
    - A visual representation is also shown below
  - Instructions were followed from [Generate and boot from configuration memory, and close project](https://github.com/kevinwlu/dsd/tree/master/Nexys-A7/Lab-2#6-generate-and-boot-from-configuration-memory-and-close-project)
  - POWER OFF > POWER ON > Wait for 10 seconds > The program runs

- Usage
	- Counter starts ticking up automatically and overflows when needed
		
		![flashed program](./hex4count/flash.gif)


### Lab 1 Part 3: Modifications
- Code
  - Created project called hex8count
	- Similar steps from Part 1, but source and constraint files are from [modifcations subfolder](https://github.com/kevinwlu/dsd/tree/master/Nexys-A7/Lab-2/Modifications)
	- Used code from respective project, but with the aforementioned procedure
	- Programmed the Nexys A7-100T board with the generated `hex8count.bit` file
-  Usage
	- The left group of leds automatically cycle from 0 to F and overflow when one to its left has reached the max value.
		
		![32 bit counter GIF](./hex8count/hex8count.gif)

	
	
	
[README.md file style inspired by Calvin Zheng](https://github.com/Crystal-Link/CPE487-Work/blob/main/Assignments/Assignment%203%20-%20Vivado%20Lab%201/README.md)
