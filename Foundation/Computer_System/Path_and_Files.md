# Topic 01: Computer Systems - Files and Paths

Navigating file systems efficiently and avoiding path errors during data loading.

---

## 1. Absolute Path
* **Definition:** The complete file path starting from the root directory (`/` on Linux/macOS, `C:\` on Windows).
* **Example:** `/home/maidha/Core-CS-to-Machine-Learning/01-Computing-Foundations/notes.md`
* **Pros:** Always accurate regardless of current location.
* **Cons:** Breaks code portability when shared with others or run on different machines.

---

## 2. Relative Path
* **Definition:** The path relative to the current working directory.
* **Special Notation:**
  * `.` : Represents the current folder.
  * `..` : Represents the parent directory (one level up).
* **Example:** `./01-Computing-Foundations/notes.md`
* **Pros:** Highly portable; keeps project structure consistent across different environments.