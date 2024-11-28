---
tags:
  - C191
  - C191Mod3
---
Updated [[2024-11-27]]

![[C191 Ch 8 Section 3.wav]]

## Terms

A referenced bit (r-bit) → a bit associated with a page and is set automatically by the hardware whenever the page is referenced by any instruction.

An aging register → associated with a page and is shifted periodically to the right by 1 bit. Unless the most significant bit is set to 1, the page is aging in the sense that the associated register value is steadily decreasing.

The aging page replacement algorithm → does not maintain pages sorted in the exact LRU order, but groups together pages referenced during a period of d consecutive references. Each period is represented by 1 bit in a periodically shifting aging register.

The second-chance page replacement algorithm → a coarse-grain approximation of LRU. The algorithm uses the r-bit to divide all pages into only two categories: recently referenced and not recently referenced. A page is selected from the not-recently referenced category.

The third-chance page replacement algorithm, also known as the not-recently-used page replacement algorithm (NRU), → a coarse-grain approximation of LRU, which divides pages into 4 categories based on the 4 possible combination of the r- bit and the m-bit.