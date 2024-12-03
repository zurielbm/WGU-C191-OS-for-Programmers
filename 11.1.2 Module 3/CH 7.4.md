---
tags:
  - C191
  - C191Mod3
---
Updated [[2024-11-27]]

![[C191 Ch 7 Section 4.wav]]

![[Phone book.pdf]]
Analogies for Page, Page Frame, and Page Table
1. Phone Book Analogy
- **Physical Memory (RAM):** Imagine a large phone book representing the computer's physical memory.
- **Page Frame:** Each page in the phone book represents a page frame. Each page contains a fixed amount of information, like a list of names and phone numbers.
- **Process:** Consider a business that needs to access phone numbers. This business symbolizes a process running on the computer.
- **Page Table:** The business has its internal directory, which acts as the page table. This directory doesn't contain the actual phone numbers but holds references to the specific pages in the phone book where those numbers can be found.
- **Page:**  Each entry in the business's directory corresponds to a page in its logical address space. The entry includes the page number and the corresponding page frame number in the phone book.
When the business (process) needs a phone number, it looks up the name in its directory (page table), which directs it to the correct page in the phone book (physical memory).

2. Library Analogy
- **Physical Memory (RAM):** Think of a library as the physical memory of the computer.
- **Page Frame:** Each bookshelf in the library represents a page frame, holding a collection of books.
- **Process:** You, as a library user, are a process.
- **Page Table:** Your library card acts as the page table. It doesn't contain the actual books but provides you with access to the bookshelves (page frames) where the books you need are located.
- **Page:** Each book you want to read represents a page in your logical address space. Your library card (page table) tells you which bookshelf (page frame) to find the book (page) on.

You use your library card (page table) to locate the correct bookshelf (page frame) and retrieve the book (page) you're interested in.

3. Cookbook Analogy
- **Physical Memory (RAM):** Consider a kitchen counter as the physical memory, where you can work with only a limited number of ingredients at a time.
- **Page Frame:** Each section of the counter represents a page frame, holding a specific ingredient or set of ingredients.
- **Process:** You are the process, preparing a dish.
- **Page Table:** Your cookbook acts as the page table. It contains the recipe but doesn't hold the actual ingredients. It guides you to the location of each ingredient.
- **Page:** Each ingredient needed for your dish represents a page in your logical address space. The cookbook (page table) directs you to the right section of the counter (page frame) where you'll find that ingredient (page).
You refer to your cookbook (page table) to know which part of the counter (page frame) has the ingredient (page) you need at each step of the recipe.

## Terms

A page → a fixed-size contiguous block of a logical address space identified by a single number, the page number.

A page frame → a fixed-size contiguous block of physical memory identified by a single number, the page frame number.


A page table → an array that keeps track of which pages of a given logical address space reside in which page frames. Each page table entry corresponds to one page and contains the number or the starting address of the frame containing the page.

Internal fragmentation → the loss of usable memory space due to the mismatch between the page size and the size of a program, which creates a hole at the end of the program's last page.