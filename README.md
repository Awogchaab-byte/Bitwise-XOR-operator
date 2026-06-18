# 🔄 Swap Two Numbers Using XOR (C++)

This C++ program swaps the values of two integers without using a temporary variable.  
It leverages the **bitwise XOR operator** to perform the swap efficiently.

---

## 🧠 Objective
To demonstrate how bitwise operators can be used for swapping values in C++.

---

## 📜 Problem Statement
> Write a C++ program that reads two integers, displays their original values, swaps them using the XOR operator, and then displays the swapped values.

---

## 💻 Code Overview
The program:
1. Prompts the user to enter two integers (`X1` and `X2`).
2. Displays the original values.
3. Swaps the values using three XOR operations:
   ```cpp
   X1 = X1 ^ X2;  // step 1
   X2 = X1 ^ X2;  // step 2
   X1 = X1 ^ X2;  // step 3
