# OCR on hardware

The idea of this project is to build a hardware/software system that is capable to do an OCR in custom logic.

## Requirements

The basic requirements for this project are divided depending on the part is desired to compile.

For the FPGA/VHDL side we will use **Xilinx Vivado** toolsuite.

For the embedded software running in the FPGA it will require **GCC** for the compiler. It will also require the **Make** program to properly build the final image.

## Build instructions

For compiling the FPGA it is required to open the VHDL project in the tool and set it to the **spartan 7 modelnumber**.

For the compilation of the **C**/**C++** source code go to the folder **src/c** and execute the make command.
