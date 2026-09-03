<div align="center">

# 📅 Week 2: Linked Lists, Two Pointers & Reversals
### *Applied Coding Skills (S1L10) — Module 2*

[![Problems Solved](https://img.shields.io/badge/Solved-8%2F8-6366f1?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/)
[![Easy](https://img.shields.io/badge/🟢_Easy-5-10b981?style=for-the-badge)](https://leetcode.com/)
[![Medium](https://img.shields.io/badge/🟡_Medium-1-f59e0b?style=for-the-badge)](https://leetcode.com/)
[![Hard](https://img.shields.io/badge/🔴_Hard-2-ef4444?style=for-the-badge)](https://leetcode.com/)
[![Language](https://img.shields.io/badge/Language-Java-b07219?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com/)

<p align="center">
  Focuses on singly-linked list fundamentals, two-pointer techniques (Floyd's Tortoise & Hare), iterative pointer manipulations, K-way merges via priority queues, and group-wise node reversals.
</p>

</div>

---

## 🎯 Learning Objectives

- **Pointer Rewiring & In-Place Reversal:** Inverting next-pointer references iteratively with $O(1)$ auxiliary space.
- **Cycle Detection & Entry Resolution:** Applying Floyd's Cycle-Finding Algorithm (Tortoise and Hare) to determine cycle presence and mathematical entry point.
- **Fast & Slow Pointers:** Locating list midpoints in a single pass to facilitate palindrome validation and divide-and-conquer processing.
- **Dummy Head Technique:** Eliminating boundary condition checks when mutating or assembling linked lists.
- **K-Way Merge with Heaps:** Combining $k$ pre-sorted streams efficiently using a min-heap priority queue in $O(N \log k)$ time.
- **Sublist Group Reversal:** Orchestrating pointer swaps in fixed batches of size $k$ while preserving overall list connectivity.

---

## 📋 Problem Directory

| # | Problem Title | Difficulty | Key Pattern / Concept | Time | Space | Performance | Solution | Notes |
| :---: | :--- | :---: | :--- | :---: | :---: | :---: | :---: | :---: |
| 0021 | [Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/) | ![Easy](https://img.shields.io/badge/Easy-brightgreen?style=flat-square) | Two Pointers / Recursive Merge | $O(N + M)$ | $O(N + M)$ | `0 ms (100.00%)` | [solution.java](0021-merge-two-sorted-lists/solution.java) | [README.md](0021-merge-two-sorted-lists/README.md) |
| 0023 | [Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) | ![Hard](https://img.shields.io/badge/Hard-red?style=flat-square) | Min-Heap / PriorityQueue | $O(N \log k)$ | $O(k)$ | `5 ms (40.75%)` | [solution.java](0023-merge-k-sorted-lists/solution.java) | [README.md](0023-merge-k-sorted-lists/README.md) |
| 0025 | [Reverse Nodes in k-Group](https://leetcode.com/problems/reverse-nodes-in-k-group/) | ![Hard](https://img.shields.io/badge/Hard-red?style=flat-square) | Pointer Reversal / K-Group Batching | $O(N)$ | $O(1)$ | `1 ms (34.55%)` | [solution.java](0025-reverse-nodes-in-k-group/solution.java) | [README.md](0025-reverse-nodes-in-k-group/README.md) |
| 0142 | [Linked List Cycle II](https://leetcode.com/problems/linked-list-cycle-ii/) | ![Medium](https://img.shields.io/badge/Medium-yellow?style=flat-square) | Floyd's Tortoise & Hare (Cycle Entry) | $O(N)$ | $O(1)$ | `0 ms (100.00%)` | [solution.java](0142-linked-list-cycle-ii/solution.java) | [README.md](0142-linked-list-cycle-ii/README.md) |
| 0160 | [Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists/) | ![Easy](https://img.shields.io/badge/Easy-brightgreen?style=flat-square) | Two Pointers / Traversal Alignment | $O(N + M)$ | $O(1)$ | `1 ms (99.90%)` | [solution.java](0160-intersection-of-two-linked-lists/solution.java) | [README.md](0160-intersection-of-two-linked-lists/README.md) |
| 0206 | [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) | ![Easy](https://img.shields.io/badge/Easy-brightgreen?style=flat-square) | Iterative 3-Pointer Reversal | $O(N)$ | $O(1)$ | `0 ms (100.00%)` | [solution.java](0206-reverse-linked-list/solution.java) | [README.md](0206-reverse-linked-list/README.md) |
| 0234 | [Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/) | ![Easy](https://img.shields.io/badge/Easy-brightgreen?style=flat-square) | Fast/Slow Pointers + Half Reversal | $O(N)$ | $O(1)$ | `3 ms (99.83%)` | [solution.java](0234-palindrome-linked-list/solution.java) | [README.md](0234-palindrome-linked-list/README.md) |
| 0876 | [Middle of the Linked List](https://leetcode.com/problems/middle-of-the-linked-list/) | ![Easy](https://img.shields.io/badge/Easy-brightgreen?style=flat-square) | Fast/Slow Pointer (Midpoint) | $O(N)$ | $O(1)$ | `0 ms (100.00%)` | [solution.java](0876-middle-of-the-linked-list/solution.java) | [README.md](0876-middle-of-the-linked-list/README.md) |

---

[⬅️ Back to Main Repository](../README.md)
