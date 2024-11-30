---
tags:
  - C191
  - C191Mod2
---
Last Updated on [[2024-11-29]]

![[C191 Ch 4 Section 3.wav]]

# Terms


An interactive process → communicates with the user in the form of a dialog by receiving commands or data from the keyboard or a pointing device and responding by generating output on the user's terminal or another output device.

A time quantum, Q, → a small amount of time (typically 10 to 100 milliseconds) during which a process is allowed to use the CPU.

The round-robin (RR) algorithm → uses a single queue of processes. The priority is determined solely by a process's position within the queue. The process at the head of the queue has the highest priority and is allowed to run for Q time units. When Q ends, the process is moved to the tail of the queue and the next process now at the head of the queue is allowed to run for Q time units.

Multilevel (ML) scheduling → maintains a separate queue of processes at each priority level. Within each level, processes are scheduled using RR.

Under the multilevel feedback (MLF) algorithm → a newly arriving process enters the highest-priority queue, N, and is allowed to run for Q time units. When Q is exceeded, the process is moved to the next lower priority queue, N-1, and is allowed to run for 2Q time units. The quantum size is doubled with each decreasing priority level.

The response time of a process → the elapsed time from the submission of a request (pressing the Enter key or clicking a mouse button) until the response begins to arrive.