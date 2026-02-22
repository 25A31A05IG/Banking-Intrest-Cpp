# Bank Interest Calculator - Documentation

## 1. Introduction
The Bank Interest Calculator is a simple C++ console application that calculates **Simple Interest** and **Compound Interest** based on user input. It demonstrates real-life banking calculations in a programmatic way.

## 2. Problem Statement
Bank customers need a program to calculate the total amount payable or receivable based on principal, rate of interest, and time. The program should provide options for both Simple and Compound Interest.

## 3. Objective
- To create a menu-driven program for calculating bank interest.  
- To demonstrate the use of loops, switch-case, and mathematical operations in C++.  
- To provide a simple real-life application of programming.

## 4. Approach / Method Used
1. Display a menu with options for Simple Interest, Compound Interest, and Exit.  
2. Take user input: Principal, Rate, Time.  
3. Perform calculations using formulas:  
   - **Simple Interest (SI)**: SI = (P × R × T) / 100  
   - **Compound Interest (CI)**: CI = P * (1 + R/100)^T - P  
4. Display the calculated interest and total amount.  
5. Repeat until user chooses Exit.

## 5. Algorithm
1. Start  
2. Display menu  
3. Input choice  
4. If choice is 1 → calculate SI  
5. If choice is 2 → calculate CI  
6. Display result  
7. Repeat menu  
8. End

## 6. Intuition
The program follows the standard mathematical formulas for interest calculation. It uses loops and switch-case to create an interactive menu.

## 7. Time Complexity
- Simple operations → O(1)  
- Menu loop → O(n) where n = number of times user interacts

## 8. Space Complexity
- Uses constant extra memory for variables → O(1)  
- Vector/arrays not used → minimal memory

## 9. Sample Input/Output
===== Bank Interest Calculator =====
1. Simple Interest
2. Compound Interest
3. Exit
Enter your choice: 1

Enter Principal Amount (₹): 10000
Enter Rate of Interest (% per year): 5
Enter Time (in years): 3

Simple Interest = ₹1500
Total Amount = ₹11500

## 10. Conclusion
This program provides a simple, interactive way to calculate bank interest. It helps beginners understand menu-driven programming, arithmetic operations, and real-life application of programming concepts.
