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

`python3 gui.py`

Pass the txt file which contains all the files in separate lines you want to assemble link and load.

## How to simulate?

`python3 sim.py`

If you are coming from `gui.py` click on `open passed file` to simulate the
compiled code, or to open another file click on `open another file`.

## How to specify files for command line usage?

In `main.py`, add files in list x

## Example?

Repo contains SampleCodes dir in which there are `sampleCode1.txt`, `sampleCode2.txt`, `sampleCode3` and `testcode.txt`.

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

