---
tags:
  - C191
  - C191Mod2
---
Last Updated on [[2024-11-29]]

![[C191 Ch 5 Section 4.wav]]

# Terms

A monitor → a high-level synchronization primitive implemented using P and V operations.

A condition variable → a named queue on which processes can wait for some condition to become true.

C.wait → causes the executing process to block and be placed on a waiting queue associated with the condition variable c.

C.signal → reactivates the process at the head of the queue associated with the condition variable c.

A priority wait → has the form c.wait(p), where c is a conditional variable and p is an integer specifying a priority according to which processes blocked on c are reactivated.