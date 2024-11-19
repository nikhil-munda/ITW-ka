# Data Structures & Algorithms Repository  

This repository contains solutions and implementations of various Data Structures and Algorithms (DSA) topics, along with a **Report Card Generator** program.  

## Repository Structure  

- **K Frequent Numbers**  
  Implementation to find the K most frequent numbers in an array. This solution uses data structures like hashmaps and heaps for optimal performance.  
  - File: `k_frequent.cpp`  

- **Red-Black Tree (RBTree)**  
  A self-balancing binary search tree implementation. The code includes insertion, deletion, and traversal functionalities with adherence to the Red-Black Tree properties.  
  - File: `rbtree.cpp`  

- **Report Card Generator**  
  A student-teacher interactive system for managing report cards.  
  - Teachers can:  
    - Display and modify student information and marks.  
  - Students can:  
    - View their individual report cards.  
  - File: `report_card.cpp`  

## Features  

### K Frequent Numbers  
- Efficiently identifies the `k` most frequent elements in an array.  
- Time Complexity: O(n log k) with a priority queue.  

### Red-Black Tree  
- Self-balancing tree ensuring O(log n) operations for insertion, deletion, and lookup.  
- Implements color-based node balancing for data integrity.  

### Report Card Generator  
- Role-based access control: Teachers vs. Students.  
- Modular code structure for adding new functionalities.  

## Prerequisites  

- **Compiler:** GCC or any C++ compiler.  
- **Languages:** C++  
- **Libraries:** Standard Template Library (STL) for DSA problems.  

## How to Run  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/yourusername/DSA-ReportCard.git  
