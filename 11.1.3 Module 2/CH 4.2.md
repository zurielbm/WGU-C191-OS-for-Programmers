---
tags:
  - C191
  - C191Mod2
---
Last Updated on [[2024-11-29]]

![[C191 Ch 4 Section 2.wav]]

# Terms


A batch process → performs a long-running and generally repetitive task that does not require any intervention from the user.

The FIFO (First-In-First-Out) algorithm, also known as FCFS (First-Come-First-Served) → schedules processes strictly according to the process arrival time. The earlier the arrival, the higher the priority.

The SJF (Shortest Job First) algorithm, also known as SJN (Shortest Job Next), → schedules processes according to the total CPU time requirements. The shorter the required CPU time, the higher the priority.

The SRT (Shortest Remaining Time) algorithm → schedules processes according to the remaining CPU time needed to complete the work. The shorter the remaining CPU time, the higher the priority.

The turnaround time of a process → the time between arrival and departure, and is the sum of the total CPU time and the waiting time.

The average turnaround time (ATT) → a set of n processes is the mean of the n individual turnaround times.

Starvation → the indefinite postponement of a process while other processes are allowed to proceed. Both SJF and SRT can lead to starvation.