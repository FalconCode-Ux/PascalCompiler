# Pascal compiler

A C program that does lexical, syntax and some semantic analysis of Pascal programs.
It generates a Tokens text file and the parse tree in a XML file,
and it displays lexical, syntax and some semantic errors if existent.

# Usage
Open the command prompt and execute Pascal_compiler.exe with a Pascal file's path as command line argument.

# Build
To build the executable (.exe) from the source files on Windows:

1/ Open Windows Command Prompt (CMD.exe) or PowerShell

2/ Make sure you have the "make" package installed by trying the command "mingw32-make"

3/ Change command directory to the project's folder

4/ Run the following command "mingw32-make --f makefile.txt"
