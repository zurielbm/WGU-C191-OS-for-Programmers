---
tags:
  - C191
  - C191Mod3
---
Updated [[2024-11-27]]

![[C191 Ch 8 Section 5.wav]]

## Terms

Page fault rate → the number of page faults, f, occurring during a number of memory references, t. The page fault rate can be expressed as P = f/t, where 0 ≤ P ≤ 1.

Effective access time → the average time to access memory in the presence of page faults.

Load control → the activity of determining how many processes should be running concurrently at any given time to maximize overall system performance.

Thrashing → an execution state during which most of the time is spent on moving pages between the memory and the disk while the CPU is mostly idle and no process is making any real progress.