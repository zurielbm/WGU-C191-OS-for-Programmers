---
tags:
  - C191
  - C191Mod2
---
Last Updated on [[2024-11-29]]

![[C191 Ch 4 Section 4.wav]]

# Terms

A real-time process → characterized by continual input, which must be processed fast enough to generate nearly instantaneous output.

A period → a time interval (typically in milliseconds or even microseconds) within which each input item must be processed.

The rate monotonic (RM) algorithm → schedules processes according to the period. The shorter the period, the higher the priority.

The earliest deadline first (EDF) algorithm → schedules processes according to the shortest remaining time until the deadline. The shorter the remaining time, the higher the priority.

feasible → A schedule is feasible if the deadlines of all processes can be met.

The CPU utilization (U) → the sum of the individual fractions of CPU times used by each process.
