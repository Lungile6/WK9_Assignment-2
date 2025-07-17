# C Programming Group Project: Pointers, Sorting, and Memory Management

## Project Overview

This project is designed to assess and enhance learners’ understanding of key C programming concepts, including the use of pointers, function pointers, dynamic memory management, modular programming with functions, and working with arrays and strings.

### Group Work Instructions

- This is a group assignment.
- Each member must contribute; contributions will be tracked via the GitHub repository.
- The deadline has been extended.
- All code must be pushed to GitHub and the repository link submitted in the final report.
- Grades will be distributed based on individual contributions reported by GitHub.

---

## Assessment Goals

By completing this project, learners will be able to:

1. Understand how the **stack and heap** memory areas work.
2. Use **pointers** on variables, arrays, and strings.
3. Apply **nested loops** for data manipulation using arrays and strings.
4. Use **functions** to build **modular and readable code**.
5. Differentiate and implement **dynamic memory management** functions: `malloc()`, `calloc()`, and `free()`.
6. Develop programs that demonstrate proper use of **memory allocation and deallocation**.

---

## Project Tasks

### ✅ Question 1: Net Salary Calculator

You will write a modular C program that calculates the net salary of an employee by applying deductions such as:

- **Tax** (based on salary range)
- **Medical insurance** (5%)
- **Maternity leave** (0.3%)
- **Social security fund** (3%)

**Requirements:**

- Each deduction must be implemented in a separate function.
- Each function must use **pointers** to return values.
- The `main()` function should receive and print the final net salary.
- Implement a logic for tax brackets:
  - ≤ $100 → 0%
  - > $100 and ≤ $300 → 20%
  - > $300 → 28%

**Reflection Question:**
- What are the advantages of using pointers over normal variables in this implementation?

---

### ✅ Question 2: Name Sorting

Develop a C program that sorts **20 full names** entered by the user.

**Requirements:**

- Ask the user to choose the sorting order: `asc` (ascending) or `desc` (descending).
- Use **bubble sort algorithm** to sort the names.
- Use **function pointers** to handle sorting direction (ascending/descending).

---

### ✅ Question 3: Memory Management

Build a program that stores **10 email addresses** of students from the 2023M cohort using **dynamic memory allocation**.

**Requirements:**

- Use `malloc()` or `calloc()` to store email addresses dynamically.
- Use `free()` to properly deallocate memory after use.
- Later, **shrink the array size to 6 students** without altering existing data.
- Implement proper memory reallocation where necessary.

---

## Compilation Instructions

Make sure you have a C compiler like `gcc`.

To compile any of the tasks:

```bash
gcc salary_calculator.c -o salary_calculator
./salary_calculator

gcc name_sorter.c -o name_sorter
./name_sorter

gcc memory_management.c -o memory_management
./memory_management


Contributors
Lungile Mabelebele
Implemented Net Salary Calculator & handled pointer logic.

Hirwa Walid
Developed Name Sorting with function pointers and bubble sort.

Kelia Songa Tesi
Handled dynamic memory allocation and shrinking logic for emails.
