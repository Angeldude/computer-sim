Computer chips simulated
===

This was done in the graphical programming environment Pure Data extended.
I've used the ideas in the 'Elements of Computing Systems' book and attempted to create
my own computer chips to be put together.
The computer in the book is 16 bits but due to the tediousness of the graphical programming environment, 
I kept the chips 8bit.

Challenges:
* Representing the data flip-flop for the bit register was my greatest achievement
* connecting all the inputs and outputs and correcting mistakes

To check it out you'll need Pure Data (I used Extended but I think vanilla version will work)
run the `tester.pd` file which then loads all other abstractions. ALU and other logic will work as is but 
in order to see the registers and program counter working you'll have to tick the box attached to the metro object.