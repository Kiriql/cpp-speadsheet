#cpp-spreadsheet
Teaching Project - Spreadsheet

# Requirements
C++17 and higher

[Java SE Runtime Environment 8](https://www.oracle.com/java/technologies/downloads/#java8)

[ANTLR](https://www.antlr.org/)

# Description
The program is implemented using dynamic polymorphism, integration of the ANTLR (java) library for working with an abstract syntax tree, a hash table as the main data structure for implementing the interface (Sheet Excel). Data is stored in cells and protected from circular dependencies. An abstract syntax tree is used to solve formula problems similar to MS Office Excel. You can also place text in cells.

# Instructions for assembling the project
1. Install [Java SE Runtime Environment 8.](https://www.oracle.com/java/technologies/javase-jre8-downloads.html)
2. Install [ANTLR](https://www.antlr.org/) (ANother Tool for Language Recognition) by following all the steps in the Quick Start menu.
3. Check the file name antlr-X.X.X-complete.jar in the FindANTLR.cmake and CMakeLists.txt files for the correct version. Instead of "X.X.X" indicate your version of antlr.
4. Create a folder called "antlr4_runtime" without quotes and download [files.](https://github.com/antlr/antlr4/tree/master/runtime/Cpp) into it
5. Run cmake build with CMakeLists.txt.
