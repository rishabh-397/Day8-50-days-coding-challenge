# Day8-50-days-coding-challenge
# Day 8 – 50 Days of Coding Challenge

## 🚀 Problems Solved

### 1. Odd‑Even Linked List
- **Description:** Group all odd‑indexed nodes followed by even‑indexed nodes in a linked list.
- **Example:**  
  - Input: `[1,2,3,4,5]`, k irrelevant → Output: `[1,3,5,2,4]`
- **Approach:**  
  1. Use two pointers (`odd`, `even`) to build two sub‑lists.  
  2. Link the tail of the odd list to the head of the even list.  
- **Complexity:** O(n) time, O(1) space.

### 2. Excel Sheet Column Number
- **Description:** Given a column title as in Excel, return its corresponding column number.
- **Example:**  
  - “A” → 1, “AB” → 28, “ZY” → 701
- **Approach:**  
  1. Traverse the string left to right.  
  2. Accumulate result: `res = res*26 + (ch - 'A' + 1)`.  
- **Complexity:** O(k) time, where k = title length, O(1) space.

---

## 🧠 Concepts Practiced
- In‑place linked list reordering  
- Two‑pointer technique  
- Cycle‑free pointer manipulation  
- String processing & positional numeral systems

## 💻 Language & Tools
- **Language:** C++  
- **Editor:** VS Code  
- **Version Control:** Git & GitHub
