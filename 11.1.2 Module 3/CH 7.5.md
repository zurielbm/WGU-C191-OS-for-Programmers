---
tags:
  - C191
  - C191Mod3
---
Updated [[2024-11-27]]

![[C191 Ch 7 Section 5.wav]]

## Terms

A segment → a variable-size block of a logical address space identified by a single number, the segment number.

A segment table → an array that keeps track of which segment resides in which area of physical memory. Each entry corresponds to one segment and contains the starting address of the segment.

A translation lookaside buffer (TLB) → a fast associative memory buffer that maintains recent translations of logical addresses to frames in physical memory for faster retrieval.

The principle of locality → states that locations accessed recently are more likely to be accessed again than locations accessed in the distant past.

The TLB's hit ratio → the fraction of memory accesses that find a match in the TLB.
