# Semester 1: Programming Fundamentals Coursework

**C++ assignments, laboratory manuals, and algorithmic problem sets from Semester 1 at UET Taxila.**

[![Language](https://img.shields.io/badge/Language-C%2B%2B17-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)](https://en.cppreference.com/w/cpp/17)
[![Coursework](https://img.shields.io/badge/Coursework-UET%20Taxila%20BSCS-8B1E1E?style=flat-square)](https://uettaxila.edu.pk/)
[![Discipline](https://img.shields.io/badge/Discipline-Programming%20Fundamentals-10B981?style=flat-square)](#curriculum--directory-structure)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)

---

## Overview

This repository archives the foundational coursework, problem sets, and laboratory tasks completed during **Semester 1 (Fall 2025)** of the Bachelor of Science in Computer Science (BSCS) program at the **University of Engineering and Technology (UET), Taxila**.

The curriculum emphasizes structured imperative programming, basic memory addressing, algorithmic problem-solving, and procedural decomposition in modern C++.

---

## Curriculum & Directory Structure

### 1. Mathematics & Numerical Algorithms ([`Maths/`](Maths/))
Fundamental numerical methods and integer mathematics:
- `check-prime.cpp`, `prime-number.cpp` — Prime number detection and optimization
- `digits.cpp`, `number_reverse.cpp` — Integer digit extraction and reversal logic
- `even-odd.cpp` — Parity testing
- `factorial.cpp` — Iterative and recursive factorial computation
- `palindrome.cpp` — Numerical and character palindrome verification
- `power.cpp` — Exponentiation algorithms
- `Math_Formulas.txt` — Mathematical reference formulas

### 2. Lecture Coursework & Topic Assignments ([`PF_Class/`](PF_Class/))
Core theoretical concepts and graded classroom problem sets:
- **[`Arrays/`](PF_Class/Arrays/)** — 1D and 2D static arrays, bound safety, and basic manipulation
- **[`Functions/`](PF_Class/Functions/)** — Parameter passing (by value vs reference), return types, and recursion
- **[`Pointers/`](PF_Class/Pointers/)** — Addressing operators (`&`), pointer dereferencing (`*`), and basic pointer arithmetic
- **[`Switch/`](PF_Class/Switch/)** — Branching, calculator menus, and control flow
- **[`Assign_1/`](PF_Class/Assign_1/)**, **[`Assign_2/`](PF_Class/Assign_2/)**, **[`Assign_3/`](PF_Class/Assign_3/)** — Graded progressive homework sets

### 3. Laboratory Practicals ([`PF_LAB/`](PF_LAB/))
Hands-on laboratory experiments and implementations:
- **[`Lab-Tasks/`](PF_LAB/Lab-Tasks/)** — Weekly lab assignments (`LabPF1.cpp` through `LabPF13.cpp`)
- **[`Lab_Manuals_Tasks/`](PF_LAB/Lab_Manuals_Tasks/)** — Tasks organized by topic: Arrays, File Handling, Functions, Conditional Branching, Loops, Structures, and Switches

### 4. Loop Mechanics & Geometric Patterns ([`Shapes-Loops/`](Shapes-Loops/))
Algorithmic nesting and spatial matrix indexing:
- Triangles: `equi-tri.cpp`, `invert-tri.cpp`, `right-tri.cpp`
- Pyramids: `half-pyramid.cpp`, `pyramid.cpp`
- Bounded boxes: `box.cpp`, `MainBox.cpp`, `num-box.cpp`, `checkers.cpp`
- Centered geometry: `Diamond.cpp`, `Cross.cpp`

### 5. Practice Problem Bank ([`Prct-Questions/`](Prct-Questions/))
Reinforcement challenges (`1.cpp` through `9.cpp`) covering cumulative semester topics.

---

## Compilation & Toolchain

The coursework adheres to standard C++17:

```bash
# Compile individual source file with all standard warnings enabled
g++ -std=c++17 -Wall -Wextra -O2 "Maths/check-prime.cpp" -o check_prime

# Execute binary
./check_prime
```

---

## Author & Academic Record

Maintained by **Hafiz Muhammad Saeed** ([@hmsaeed-dev](https://github.com/hmsaeed-dev)) — Department of Computer Science, **University of Engineering and Technology (UET), Taxila**.

*Documented in personal knowledge vault at `[[UET Taxila BSCS]]` and `[[Semester 1 (Fall 2025)]]`.*
