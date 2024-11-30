---
tags:
  - C191
  - C191Mod2
---
Last Updated on [[2024-11-29]]

![[C191 Ch 3 Section 5.wav]]

# Terms

A resource control block (RCB) → a data structure that represents a resource.

allocated → A resource is allocated to a process if the process has access to and is able to utilize the resource.

free → A resource is free if the resource may be allocated to a requesting process.

The request resource function → allocates a resource r to a process p or blocks p if r is currently allocated to another process.

The release resource function → allocates the resource r to the next process on the r's waiting list. If the waiting list is empty, r is marked as free.

The scheduler function → determines which process should run next and starts the process.