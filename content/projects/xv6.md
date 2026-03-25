---
title: "Xv6 Kernel Optimization"
date: 2025-03-31T00:00:00+00:00
draft: false
slug: xv6
description: "A collection of advanced system calls for the XV6 kernel, based on MIT's 6.1810 (formerly 6.828) Operating Systems course."
summary: "A collection of advanced system calls for the XV6 kernel, based on MIT's 6.1810 (formerly 6.828) Operating Systems course."
featured: true
tags:
  - C
  - Assembly
  - RISC-V
categories:
  - projects
# cover: "images/01.avif"
# link: "https://github.com/michaeltin001/xv6-kernel-optimization"
status: "completed"
---

{{< button text="View GitHub" url="https://github.com/michaeltin001/xv6-kernel-optimization" icon="github" target="_blank" />}}

This project implements a collection of advanced system calls for the XV6 kernel. The goal is to expand on XV6's core functionality with file system traversal, inter-process communication, and optimized I/O operations. It is based on MIT's 6.1810 (formerly 6.828) Operating Systems course.

This project accomplishes the following objectives:

* Implements standard Unix user-level utilities: `sleep`, which pauses execution for a set number of ticks; `find`, which recursively searches directories for specific filenames; and `xargs`, which executes commands from standard input.
* Improves memory allocation by replacing statically declared arrays with a buddy allocator and implementing lazy page allocation for user-space heap memory.
* Optimizes the `fork()` system call by using a copy-on-write method that initially shares physical memory pages between parent and child processes, as opposed to directly duplicating them.
* Adds to the capabilities of the existing `Xv6` file system by supporting much larger file sizes and implementing symbolic links.
* Implements the `mmap` and `munmap` system calls, allowing processes to dynamically map files directly into memory and share memory with other processes.
