---
tags:
  - C191
  - C191Mod2
---
Last Updated on [[2024-11-29]]



A process → an instance of a program being executed by an OS.

Process control block (PCB): → A data structure that holds information for a process, including the current instruction address, the execution stack, the set of resources used by the process, and the program being executed.

new state → A newly created process is placed into the new state before the process is allowed to compete for the CPU.

terminated state → A process is placed into the terminated state when execution can no longer continue but before the PCB is deleted.

suspended state → A process may be placed into the suspended state even though the CPU and all resources are available.

A context switch → the transfer of control from one process to another.

The CPU state → consists of all intermediate values held in any CPU registers and hardware flags at the time of the interruption.