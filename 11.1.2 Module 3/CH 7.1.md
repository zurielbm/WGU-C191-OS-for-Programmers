---
tags:
  - C191
  - C191Mod3
---
Updated [[2024-11-27]]



## Terms

physical memory (RAM) → a hardware structure consisting of a linear sequence of words that hold a program during execution. 

A word → a fixed-size unit of data. A typical word size is 1, 2, or 4 bytes.

A physical address → an integer in the range [0 : n-1] that identifies a word in a physical memory of size n.

logical address space → an abstraction of physical memory, consisting of a sequence of imaginary memory locations in a range [0 : m-1], where m is the size of the logical address space.

A logical address → an integer in the range [0 : m-1] that identifies a word in a logical address space.

A source module → a program or a program component written in a symbolic language, like C, or an assembly language, that must be translated by a compiler or assembler into executable machine code.

An object module → the machine-language output of a compiler or assembler generated from a source module

A load module → a program or combination of programs in a form ready to be loaded into main memory and executed.

Program relocation → the act of moving a program component from one address space to another.

Static relocation → binds all logical addresses to physical addresses prior to execution.

Dynamic relocation → postpones the binding of a logical address to a physical address until the addressed item is accessed during execution.

A relocation register → contains the physical starting address of a program or program component in memory.

First-fit → always starts the search from the beginning of the list and allocates the first hole large enough to accommodate the request.

Next-fit → starts each search at the point of the last allocation. 

Best-fit → searches the entire list and chooses the smallest hole large enough to accommodate the request. 

Worst-fit → takes the opposite approach from best-fit by always choosing the largest available hole for any request.