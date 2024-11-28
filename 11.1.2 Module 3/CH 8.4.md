---
tags:
  - C191
  - C191Mod3
---
Updated [[2024-11-27]]

![[C191 Ch 8 Section 4.wav]]

## Terms

The optimal working set of a process → the set of resident pages that will still be needed in the immediate future and thus should remain resident.

The working set (WS) → of a process at time t is the set of pages referenced during the past d memory operations preceding t.

The working set page replacement algorithm → uses a trailing window of size d superimposed on the RS to determine the size and composition of the working set at time t.

The page-fault-frequency replacement algorithm → takes a direct approach to controlling the page fault rate by adjusting the current resident set based on how frequently consecutive page faults occur.