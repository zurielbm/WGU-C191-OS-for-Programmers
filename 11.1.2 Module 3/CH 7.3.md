---
tags:
  - C191
  - C191Mod3
---
Updated [[2024-11-27]]

![[C191 Ch 7 Section 3.wav]]

## Terms

External memory fragmentation → the loss of usable memory space due to holes between allocated blocks of variable sizes.

The 50% rule → states that, if the probability of finding an exact match for a request approaches 0, one third of all memory partitions are holes and two thirds are occupied blocks. Formally, n = 0.5m, where n is the number of holes and m is the number of occupied blocks.

Swapping → the temporary removal of a module from memory. The module is saved on a disk and later moved back to memory.

Memory compaction → the systematic shifting of modules in memory, generally in one direction, to consolidate multiple disjoint holes into one larger hole.

Linking → the act of resolving external references among object modules and can be done statically, before loading, or dynamically, while the program is already executing.

Sharing → the act of linking the same copy of a module to multiple other modules.