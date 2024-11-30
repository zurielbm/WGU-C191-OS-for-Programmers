---
tags:
  - C191
  - C191Mod2
---
Last Updated on [[2024-11-29]]

![[C191 Ch 5 Section 1.wav]]

# Terms

Concurrency → the act of multiple processes (or threads) executing at the same time.

A critical section → a segment of code that cannot be entered by a process while another process is executing a corresponding segment of the code.

Guarantee mutual exclusion → Only one process may be executing within the CS.

Prevent lockout → A process not attempting to enter the CS must not prevent other processes from entering the CS.

Prevent starvation → A process (or a group of processes) must not be able to repeatedly enter the CS while other processes are waiting to enter.

Prevent deadlock → Multiple processes trying to enter the CS at the same time must not block each other indefinitely.