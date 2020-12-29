# Leiontif's Economic I/O Model
# Author: Ryan Rosiak
<br /> <br />
## Project Description:
This project demonstrates matrix inversion. At its base, the project demonstrates the 
basic use of common and elementary matrix operations as well as puts them all together
to do a complex matrix calculation. All of the things in this project work up do 
complete the complex economic calculation model. Very finnicky base cases as well as
very tight edge cases make accuracy extremely important. This project shows how with
careful precision, you can create a real world application to a real world problem.
<br /> <br />
## Files to pay attention to:
* main.o, matrix.o, MatrixDriver.o - These are the compilation linker files
* iomodel, driver - Output files that are run when the program is executed by the user
* Makefile - File that allows the user to compile without having to input specific commands
<br /> <br />
## Makefile Instructions:
Type "make" without the quotes and the program will compile everything for you. 
Then proceed with useing ./main in order to run the program.
<br /> <br />
## Instructions for Program:
Follow the Makefile instructions above to run the program without any manual work. If
not using Makefile, then you must compile the .cpp files into .o files.
(g++ -c main.cpp) Then you must link those with a final compilation all while labeling
the output file as iomodel or driver\
**You must use -std=c++11 within your compilation steps.**\
**Examples used in data.txt do not represent real world examples and some will have
negative outputs for the final answer.**
<br /> <br />
## data.txt Format:
*START OF FILE*\
Company Names\
---\
Matrix\
---\
Demand Vector\
---\
**If the end then leave blank! Otherwise, for each consecutive entry of data refer back to format above**
