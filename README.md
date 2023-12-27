The project was part of CPE 233 at Cal Poly and includes my version of the OTTER MCU that we designed in the class.
It is a simple microprocessor designed to understand and execute instructions in the RISC-V RV32I instruction set.

Developed with Xilinx Vivado. All tests were done using a Digilent Basys3 development board. A constraints file for the Basys3 is included, other boards would need their own constraints file made.

An additional LCD Demo program is included to demonstate how a lcd might be hooked up to the Basys3 and how the OTTER executes instructions. Details on the wiring of the LCD and instructions for the demo program are in "CPE 233 Final Report.pdf"

To change the file that is loaded into the microprocessor's memory the otter memory file must be changed to load the new .mem file and then bitstream regeneration re-run.
