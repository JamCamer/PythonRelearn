# PythonRelearn
I am relearning python, the goal is to complete the Python AN introduction to Programming. Then Advanced to play with building my own Machine Learning Networks.
Open a Python (.py) file and the Pylance extension will activate.

Here is how to convert 72 base 10 into binary
Step one identify if the right most number is odd. if so then 1 if not then 0.
After this step divide the number by 2. Let's try it
73=1 73/2 =36
36=0 36/2 =18
18=0 18/2 =9
9=1 9/2 = 4
4=0 4/2 = 2
2=0 2/2 = 1
1=1 1/2 = 0
this statement is equal to 1001001
this is equal to 1*2^0 + 1*2^3 + 1*2^6 = 1+8+64= 73

a summary of the process
start at digit n=0 (rightmost)
repeat
If x is even, the current digit n=0, otherwise current digit n=1
divide x by2
If x = 0, then end the repitition

Computers do all mathematical operations on binary numbers

billions of bits=gigabit

Computers run off the fetch and execute cycle the hardware fetches the instruction, executes, then fetches the next

I ran into a confusing concpet on page 14 the instruction register a special register that the computer sometimes uses for data values and addresses

The most difficult concept to grasp is the stored program concept
the program for the stored program concept can look like 
Fetch contents of memory location 9 into the accumulator
Add the contents ofmemory location 10 to the accumulator
store accumulator contents into station 11

This reminds me of a train station. You are placing passenegers into the station like contents of memory locations into the accumulator, the contents in accumulator are moved to different station

This is a PDP-8 COmputer the concepts of page 14-16 are shaky to me, but I only have 516 more pages to go :)\

MOdern Day disc drives replaced using switches to enter binary numbers

Operating systems allocate resources and control devices

The boot loader (bootstrap layer) is the lowest layer of software
The paper tape system is the second lowest layer
More layers were added so that the user had to understand less and less about the machine
OPerating on a disc drive is the third layer of software ti provides basic hardware functionality and gives the user access to a file system

Programming was once done in binary but thanks to the invention of the assembler a programmer could write in a task and the text could be converted into a binary executable

Example
LDA Data 1
ADD DAta2
STO Res
HLT
Data 1: 21
Data 2: 433
Res: 0

COmpilers translate high level language statements into assembler which turns into binary code

A=21
B=433
C = A+B

This allows the programmer to declare that certian names represent intergers.

Python is an intrepreter language it does a part of the compilation process but does not produce execution of code, it simulates the execution of code doing most of the work in the software, just like JavaScript in many cases

GUIS
MOst computesr interface through their users using a keyboard and mouse
GUI's are very difficult to program and require scores of C++

GErman company TeleFuken is the creator of the mouse

Widgets are graphical  objects that are drawn in windows or otherwise a computer screen that can be selected or operated using a the mouse

WIdgets come in the forms of
Buttons
Radio Button: 1 button can be selected at a time options are mutualy exclusive
Check box: A way to select options from a larger set
Drop DOwn list: a box containing text that displays a complete set of options
Icon: a pictogram that represents a function or a program file

A widget represents an activity using an understood symbol
Software implementing widgets is a module

Alohanet is radio computer communication: computuers communicated through radio. To communicate computers would listen for chatter if there was no chatter the computers sent out their information. Fun fact if 2 computers sent out information at the same time a collision would occur

A group of computers meant to handle network traffic is a POP Point of Presenece

The web is a layer of protocols above internet protocols

The internet is a client server system the client makes a request to the server and the server completes the clients request in exchange for the clients cookies and data. Surfing the web can be thought of a 24/7 365 christmas. YOu wish for snata to bring you the desired contents and all Snata wants is for you to enable cookies and data that feeds him

I wonder how the hardware can cumminicate to the software?

American standard Code for information interchange has values assinged to charchters or the ASCII

When organizing dates by numer it is best to follow this format YYYYMMDD because that way the largest dates will be the newest.

COmputer memory is sclusivly numeric

010000=

0*2^5+ 1*2^5= 32

Compiliers translate the cod, intrepeters can preform part of the compiliation process but not execute the code

