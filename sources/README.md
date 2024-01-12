# Sources

Here a high level overview of the source file estructure will be given to the reader.

## VHDL

For the **VHDL** sources the standard *insert here* has been followed for the compilation.

The project is structure for the components:
- Top
- MIPI Interface
    - IO configuration 
    - Buffer
    - AXI4 endpoint
- OCR module
    - AXI4 endpoint
    - Buffer
    - Logic


## C

For the **C** files the following structure has been used to organize the code:
- Main
- UART
- Etherne
- IP Stack
- JSON Library (BOOST - C++)
    - C_CppInterface.h
    - CppJson.h
    - CppJson.cpp
