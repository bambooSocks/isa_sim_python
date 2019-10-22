# ISA simulator
###### Build by Matej Majtan, Mihaela-Elena Nistor, Clifford Arnold III Rhodes

## Dependencies

The simulator is tested on Python 3.6.8 with no external dependencies.

## Executing

In order to run the simulator, run ```python3 isa-sim.py <max_cycles> <program_file> <data_mem_file>```. All three arguments are required in order to run the program. ```max_cycles``` describes the maximum amount of cycles the simulator should run through before terminating. ```program_file``` is an txt file which contains the program written in assembly language following specified format. ```data_mem_file``` is also a txt file which contains initial setup of the data memory following given format.