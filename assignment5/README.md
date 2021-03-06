# Assignment 5: Vivado Lab 3 and 6
## All vhd and constraint files in .srcs folder of respective project

### Lab 3 Part 1: VGAball
- Code
	- Created a new project in Vivado called `vgaball`
	- Followed the instructions from [Lab 3](https://github.com/kevinwlu/dsd/tree/master/Nexys-A7/Lab-3) to set up the Vivado project
	- Using code provided, edited the Design Sources and Constraints of the project
	- Ran synthesis and implementation
  	- Then generated bitstream
	- Programmed the Nexys A7-100T board with the generated `vga_top.bit` file

- Usage
	- Plug VGA Display cable into appropriate monitor.
	- Ball will automatically start moving up and down.
		
		![vgaball](./vgaball/vgaball.gif)
	
### Lab 3 Part 2: VGAball modifications
- Code
  	- Created project called vgaball_modifications
	- Similar steps from Part 1, but source and constraint files are from [modifcations subfolder](https://github.com/kevinwlu/dsd/tree/master/Nexys-A7/Lab-3/Modifications)
	- Used code from respective project, but with the aforementioned procedure
	- Programmed the Nexys A7-100T board with the generated `vga_top.bit` file
-  Usage
	- Ball is round
	- Ball speed is increased
	- Ball can move in x and y direction
	- Ball will automatically start bouncing around screen
		
		![vgaball_modifications](./vgaball_modifications/vgaball_modifications.gif)


### Lab 6 Part 1: PONG
- Code
	- Created a new project in Vivado called `pong`
	- Followed the instructions from [Lab 6](https://github.com/kevinwlu/dsd/tree/master/Nexys-A7/Lab-6) to set up the Vivado project
	- Using code provided, edited the Design Sources and Constraints of the project
	- Ran synthesis and implementation
  	- Then generated bitstream
	- Programmed the Nexys A7-100T board with the generated `pong.bit` file

- Usage
	- Plug VGA Display cable into appropriate monitor.
	- Plug in potentiometer and move analog paddle to move potentiometer
	- Press BTNC button to spawn ball 
	- Ball will automatically start moving.
		
		![Pong](./pong/pong.gif)
	
### Lab 6 Part 2: Pong modifications
- Code
  	- Created project called pong_modifications
	- Similar steps from Part 1, but source and constraint files are from [modifcations subfolder](https://github.com/kevinwlu/dsd/tree/master/Nexys-A7/Lab-6/Modifications)
	- Used code from respective project, but with the aforementioned procedure
	- Programmed the Nexys A7-100T board with the generated `pong.bit` file
-  Usage
	- Set switches to set speed of ball.
	- Plug in components same as first part
	- Points will count upwards on leds on boards
	- Bar will get one pixel smaller for every intersection between ball and bar
		
		![Pong with Counter](./pong_modifications/pong_modifications.gif)
