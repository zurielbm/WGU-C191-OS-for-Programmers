---
tags:
  - C191
  - C191Mod3
---
Updated [[2024-11-27]]

![[C191 Ch 7 Section 5.wav]]

1. Apartment Building Analogy

	Imagine an apartment building representing the computer's physical memory.
	
	**Segment:** Each apartment in the building is like a segment, representing a distinct, variable-sized block of memory. Apartments can have different sizes and layouts (similar to segments having different sizes).
	
	**Process:**  Each resident of the apartment building is like a process, occupying one or more apartments (segments).
	
	**Segment Table:** The building directory acts as the segment table, mapping each resident (process) to their specific apartments (segments). It indicates which apartment (segment) each resident (process) is assigned to and its location within the building (memory).

Each resident (process) has access only to their assigned apartment(s) (segment(s)) and cannot access other apartments (segments) without permission
## Terms

A segment → a variable-size block of a logical address space identified by a single number, the segment number.

A segment table → an array that keeps track of which segment resides in which area of physical memory. Each entry corresponds to one segment and contains the starting address of the segment.

A translation lookaside buffer (TLB) → a fast associative memory buffer that maintains recent translations of logical addresses to frames in physical memory for faster retrieval.

The principle of locality → states that locations accessed recently are more likely to be accessed again than locations accessed in the distant past.

The TLB's hit ratio → the fraction of memory accesses that find a match in the TLB.
