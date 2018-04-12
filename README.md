# AssemblerLinkerLoader
Web based Stimulation of an Assembler Linker loader for a subset of 8085 microprocessor instruction set using Python for backend and javascript for front end.

# ALL-8085

A simple Assembler Linker Loader Simulator for subset of C language.
Converts in 8085 assembly language. Supports global variables and multiple file
definitions.

## Dependencies
### For GUI
Tkinter Library

### For command line
None

## File format?

In a txt file specify on separate line all the files you want to link.

## How to run?

`python3 app.py`

open the localhost server mentioned in command line by entering the given address in URL tab in the browser.

## Example?

Repo contains SampleCodes dir with sample codes.

# Instruction format

Initialization :

Local:

`var a = 5`

Global:

`glob a = 5`

From another file (External variable):

`extern a`

Arthimetic

add:

`a = b + c`

sub:

`a = b - c`

bit and

`a = b & c`

bit or

`a = b | c`

where a is a variable declared

b,c can be integers or variables

Loop:

`loop count`

//Instructions

//Instructions

//Instructions

//Instructions

`endloop`

where count is a variable (not integer!!)

Conditional:

`if x>y`

//Instructions

//Instructions


//Instructions

//Instructions

`endif`

`if x=y`

//Instructions

//Instructions

//Instructions

//Instructions

`endloop`

x and y should be variables!!!!

