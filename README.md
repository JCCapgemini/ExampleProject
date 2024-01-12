# OCR on hardware

The idea of this project is to build a hardware/software system that is capable to do an OCR in custom logic.

## Requirements

The basic requirements for this project are divided depending on the part is desired to compile.

For the FPGA/VHDL side we will use **Xilinx Vivado** toolsuite.

For the embedded software running in the FPGA it will require **GCC** for the compiler. It will also require the **Make** program to properly build the final image.

## Build instructions

For the compilation of the **C**/**C++** source code go to the folder **src/c** and execute the make command.

For compiling the FPGA it is required to open the VHDL project in the tool and set it to the **spartan 7 modelnumber**.

## Execution instructions

For the execution of the solution is required to have compiled first the **C** part and then the **VHDL** part.

Once all the artifacts have been obtained, you can use the **vivado** programmer to load the binary to the board.


## Documentation

For more information check [documentation](documentation/README.md).

## Sources

For more information check [sources](sources/README.md).


