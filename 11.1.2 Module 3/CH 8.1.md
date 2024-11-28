---
tags:
  - C191
  - C191Mod3
---
Updated [[2024-11-27]]

![[C191 Ch 8 Section 1.wav]]

## Terms

Virtual memory (VM) → a collection of one or more logical address spaces, each of which may exceed the size of physical memory.

Demand paging → the principle of loading a page into memory only when the page is needed, rather than at the start of the execution.

A present bit → a binary flag in each page table entry that indicates whether the corresponding page is currently resident in memory.

A page fault → an interrupt that occurs when a program attempts to reference a non-resident page.

Page replacement → the act of overwriting a page in memory with a different page loaded from the disk when needed.

A modified-bit (m-bit) → a binary flag in each page table entry that indicates whether the corresponding page has been modified during execution.