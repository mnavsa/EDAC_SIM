EDAC_SIM_1 by Mikhaeel Navsa

Instructions:
1. Make sure all VHDL files are in the same directory.
2. Use ModelSim to simulate the EDAC operation with a simulated RAM component.
3. Create a new project in ModelSim and add all the VHDL files.
4. Start simulation and simulate VHDL file EDAC_SIM_1.vhd.
5. Click on EDAC_SIM_1 and select "Add wave."
6. Set the device clock.
7. Set the other inputs as follows:
	> MESSAGE: 4-bits to be encoded and written to memory.
	> WRITE_EN: select 1 for write and 0 for read.
	> SCRUB_EN: set to 1 to enable scrubbing.
	> ADDRESS: 8-bit value, where to write or read.
8. Both reads and writes require three clock cycles. Allow for three clock cycles before initiating
   another read or write command.