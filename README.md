# Subroutines-and-Parameters 

## Subroutines

A subroutine is a named self-contained block of instructions. By encapsulating and naming a a block of instructions in a program it becomes possible to call the block from other parts of the program. A subroutine may contain its own variable, type, label, and const declarations. A subroutine may also define subroutines.

### Advantages of a subroutine

- Reduces cognitive demand to understand program
- Main program block reduced in length
- Self-contained subroutines can be developed and maintained independently (writing and debugging)
- The more independent the subroutine is from the main program, the easier it is to write independently of understanding the context from which it is being called
- Subroutines can be re-used in a different program and may be included in a library which can be imported by other programs

## Parameters

A subroutine parameter is one way of passing data into and out of a subroutine. When a subroutine is called, any data passed to it via the subroutine parameter mechanism is copied into the memory area reserved for subroutine formal parameters as shown in the memory schematic.

There are two ways that data may be passed via the subroutine parameter mechanism into a subroutine:

- Call by value
- Call by reference

**Call by value** - formal parameter of subroutine gets a copy of the datum associated with the actual parameter used in call to subroutine.

**Call by address** - formal parameter of subroutine is assigned the address in memory of the datum associated with the actual parameter used in call to subroutine.

(Side effects, formal and actual parameteres)
