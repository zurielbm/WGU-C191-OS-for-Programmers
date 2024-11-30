---
tags:
  - C191
  - C191Mod1
---
Last Updated on [[2024-11-29]]

![[C191 Ch 1 Section 2.wav]]

# Terms

The kernel of an OS → the minimal set of functions necessary to manage the system resources safely and efficiently.

A privileged instruction → performs critical operations that access I/O devices and the CPU's status and control registers.

Kernel mode → the CPU state where both privileged and non-privileged instructions may be used.

User mode → the CPU state where only non-privileged instructions may be used.

A graphical user interface (GUI) → presets various icons on the screen, which the user can click on in different ways to invoke services associated with the icons, or to reveal pull-down menus for additional tasks.

The OS shell → a command interpreter that accepts and interprets textual commands issued by the user via a keyboard.

A shell script → a program that implements a new operation by combining multiple commands and control statement into one named unit interpreted by the shell.

A system call → a request from an application for an OS service.

A supervisor call (kernel call) → a privileged instruction that automatically transfers execution control to a well-defined location within the OS kernel.

An interrupt → an event that diverts the current execution of a program to a predefined location in the kernel in order to respond to an event.

A trap (also called an internal interrupt) → an interrupt triggered by the currently executing instruction.

An interrupt handler → a kernel function, invoked whenever an interrupt occurs, that determines the cause of the interrupt and invokes the appropriate kernel function to provide the response.