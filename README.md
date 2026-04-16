# Dystopian Factory Cost Calculator (P05)

An x86 Assembly Language (MASM) program that calculates the total production cost for a set of resources in a dystopian factory setting. 

This practical demonstrates **modular programming** using custom procedures (PROC), parameter passing via the stack, and proper register preservation.

**Author:** DN MBOYI  
**Student Number:** 222019179  
**Subject:** CSC03B3  
**Practical:** P05  
**Year:** 2025  
**Title:** Dystopian Factory Conglomerate Cost Calculator

---

## Problem Description

The program allows the user to:
- Enter 5 resource quantities
- Enter 5 corresponding resource costs
- Displays both arrays in formatted bracket notation `[val1, val2, ..., val5]`
- Calculates the **total cost** = Σ (resource[i] × cost[i]) for all 5 items
- Repeats the process until the user chooses to exit

---

## Features

- **Modular Design**: Uses three custom procedures:
  - `inputArray` – Prompts and stores values into an array
  - `display` – Displays an array in clean `[x, y, z]` format
  - `totalCost` – Computes the sum of element-wise multiplication of two arrays
- Proper **stack-based parameter passing**
- Register preservation using `PUSH`/`POP`
- Clean, formatted console output with welcome message
- Loop support for multiple calculations
- Robust handling of array operations

---

## Technologies Used

- **x86 Assembly Language**
- **MASM** (Microsoft Macro Assembler)
- **io.inc** library for input/output
- **PROC / ENDP** for modular programming
- Stack parameter passing

---

## How to Run

1. Open the project in **Visual Studio** with MASM support enabled
2. Build the solution
3. Run the executable
4. Follow the prompts:
   - Enter 5 resource amounts
   - Enter 5 resource costs
5. View the displayed arrays and total cost
6. Choose whether to run another calculation

---


