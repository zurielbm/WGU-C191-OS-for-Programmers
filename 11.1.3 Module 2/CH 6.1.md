---
tags:
  - C191
  - C191Mod2
---
Last Updated on [[2024-11-29]]

![[C191 Ch 6 Section 1.wav]]

# Terms

A resource allocation graph → shows the current allocation of resources to processes and the current requests by processes for new resources.

A process p is blocked → on a resource r if one or more request edges directed from p to r exist and r does not contain sufficient free units to satisfy all requests.

A resource request (req r, m) → by a process p for m units of a resource r creates m new edges directed from p to r.

A resource acquisition (acq r, m) → by a process p of m units of a resource r reverses the direction of the corresponding request edges to point from the units of r to p.

A resource release (rel r, m) → operation by a process p of m units of a resource r deletes m allocation edges between p and r.

A process is deadlocked → in a state s if the process is blocked in s and if no matter what state transitions occur in the future, the process remains blocked.

deadlock state → A state s is called a deadlock state if s contains two or more deadlocked processes.

A state s → a safe state if no sequence of state transitions exists that would lead from s to a deadlock state.