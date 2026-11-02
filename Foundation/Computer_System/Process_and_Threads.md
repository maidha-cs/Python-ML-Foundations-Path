# Topic 01: Computer Systems - Processes and Threads

Understanding how the operating system executes tasks via processes and threads is fundamental for writing efficient, concurrent programs.

---

## 1. What is a Process?
* **Definition:** An independent program in execution managed by the Operating System.
* **Memory Isolation:** Each process has its own dedicated memory space, ensuring crashes in one process do not affect others.
* **Overhead:** Creating and switching between processes is relatively heavy for the CPU.

---

## 2. What is a Thread?
* **Definition:** The smallest unit of execution within a process (often called a "lightweight process").
* **Shared Resources:** Threads within the same process share the same memory space and file descriptors.
* **Overhead:** Lightweight and fast to create, ideal for concurrent tasks (like background downloads while keeping a UI responsive).

---

## 3. Side-by-Side Comparison

| Feature | Process | Thread |
| :--- | :--- | :--- |
| **Memory** | Isolated / Separate | Shared within the process |
| **Resource Cost** | High | Low (Lightweight) |
| **Communication** | Complex (IPC required) | Direct and fast |