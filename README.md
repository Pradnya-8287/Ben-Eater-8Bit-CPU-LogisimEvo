Ben Eater’s 8-bit CPU (Logisim Evolution v3.8.0)

This is my implementation of an 8-bit breadboard CPU inspired by Ben Eater’s design, recreated in Logisim Evolution v3.8.0. It contains all the main components needed for a functioning CPU, along with supporting registers and flags.

Opening the Project:
I. Download and install Logisim Evolution v3.8.0.
II. Open the .circ file in Logisim.
III. Load the ROM contents (if needed) from the provided .rom files.


Components:
1. main - Top level circuit containing the main CPU
2. CLK - Clock generator for timing the CPU operations.
3. PROGRAM_COUNTER - Holds the address of the next instruction to execute.
4. A_Register - Primary accumulator register.
5. REGISTER_B - Secondary register used by the ALU.
6. ALU - Arithmetic Logic Unit for performing operations.
7. OUTPUT_REGISTER - Stores results to be output.
8. MAR - Memory Address Register, selects memory location to read/write.
9. INSTRUCTION_REGISTER - Stores the current instruction being executed.
10. STEP_COUNTER - Keeps track of micro-instruction steps.
11. zero_flag - Indicates if the last operation resulted in zero.
12. FLAGS – Stores CPU status flags.

