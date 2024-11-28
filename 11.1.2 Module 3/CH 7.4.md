---
tags:
  - C191
  - C191Mod3
---
Updated [[2024-11-27]]

![[C191 Ch 7 Section 4.wav]]

## Terms

A page → a fixed-size contiguous block of a logical address space identified by a single number, the page number.

A page frame → a fixed-size contiguous block of physical memory identified by a single number, the page frame number.


A page table → an array that keeps track of which pages of a given logical address space reside in which page frames. Each page table entry corresponds to one page and contains the number or the starting address of the frame containing the page.

Internal fragmentation → the loss of usable memory space due to the mismatch between the page size and the size of a program, which creates a hole at the end of the program's last page.