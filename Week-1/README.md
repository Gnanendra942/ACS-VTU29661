<div align="center">

# 📅 Week 1: Arrays, Strings, Two Pointers & Binary Search
### *Applied Coding Skills (S1L10) — Module 1*

[![Problems Solved](https://img.shields.io/badge/Solved-10%2F10-6366f1?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/)
[![Easy](https://img.shields.io/badge/🟢_Easy-8-10b981?style=for-the-badge)](https://leetcode.com/)
[![Medium](https://img.shields.io/badge/🟡_Medium-2-f59e0b?style=for-the-badge)](https://leetcode.com/)
[![Language](https://img.shields.io/badge/Language-Java-b07219?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com/)

<p align="center">
  Focuses on foundational array manipulations, in-place two-pointer partitions, window-based duplication checks, string frequency analysis, divide-and-conquer binary search, and prefix sum optimizations.
</p>

</div>

---

## 🎯 Learning Objectives

- **Two-Pointer Convergence & Swapping:** In-place array transformations (reversing, zero-shifting, inward sorted-square matching) in $O(N)$ time and $O(1)$ space.
- **Dutch National Flag Partitioning:** Three-way partitioning of array elements in a single pass using three boundary pointers (`low`, `mid`, `high`).
- **Sliding Window & Hash Sets:** Tracking nearby sliding windows of bounded size $k$ to detect duplicate elements in linear time.
- **Prefix Sum Accumulation:** Eliminating redundant nested loops by caching cumulative sums for range-query and absolute-difference calculations.
- **Binary Search (Divide & Conquer):** Logarithmic time $O(\log N)$ search over sorted spaces with overflow-safe midpoint calculation.
- **Single-Pass Greedy Tracking:** Preserving running minimum/maximum states on the fly to maximize profit margins in financial sequences.

---

## 📋 Problem Directory

| # | Problem Title | Difficulty | Key Pattern / Concept | Time | Space | Performance | Solution | Notes |
| :---: | :--- | :---: | :--- | :---: | :---: | :---: | :---: | :---: |
| 0075 | [Sort Colors](https://leetcode.com/problems/sort-colors/) | ![Medium](https://img.shields.io/badge/Medium-yellow?style=flat-square) | Dutch National Flag / 3-Way Partition | $O(N)$ | $O(1)$ | `0 ms (100.00%)` | [solution.java](0075-sort-colors/solution.java) | [README.md](0075-sort-colors/README.md) |
| 0121 | [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) | ![Easy](https://img.shields.io/badge/Easy-brightgreen?style=flat-square) | Single Pass / Min-Price Tracking | $O(N)$ | $O(1)$ | `1 ms (99.96%)` | [solution.java](0121-best-time-to-buy-and-sell-stock/solution.java) | [README.md](0121-best-time-to-buy-and-sell-stock/README.md) |
| 0219 | [Contains Duplicate II](https://leetcode.com/problems/contains-duplicate-ii/) | ![Easy](https://img.shields.io/badge/Easy-brightgreen?style=flat-square) | Sliding Window / HashSet | $O(N)$ | $O(\min(N, k))$ | `24 ms (71.34%)` | [solution.java](0219-contains-duplicate-ii/solution.java) | [README.md](0219-contains-duplicate-ii/README.md) |
| 0283 | [Move Zeroes](https://leetcode.com/problems/move-zeroes/) | ![Easy](https://img.shields.io/badge/Easy-brightgreen?style=flat-square) | Two Pointers / In-Place Swapping | $O(N)$ | $O(1)$ | `2 ms (92.03%)` | [solution.java](0283-move-zeroes/solution.java) | [README.md](0283-move-zeroes/README.md) |
| 0344 | [Reverse String](https://leetcode.com/problems/reverse-string/) | ![Easy](https://img.shields.io/badge/Easy-brightgreen?style=flat-square) | Two Pointers / Opposite Ends Swap | $O(N)$ | $O(1)$ | `0 ms (100.00%)` | [solution.java](0344-reverse-string/solution.java) | [README.md](0344-reverse-string/README.md) |
| 0387 | [First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string/) | ![Easy](https://img.shields.io/badge/Easy-brightgreen?style=flat-square) | Frequency Count / Character Array | $O(N)$ | $O(1)$ | `31 ms (38.93%)` | [solution.java](0387-first-unique-character-in-a-string/solution.java) | [README.md](0387-first-unique-character-in-a-string/README.md) |
| 0704 | [Binary Search](https://leetcode.com/problems/binary-search/) | ![Easy](https://img.shields.io/badge/Easy-brightgreen?style=flat-square) | Binary Search / Divide & Conquer | $O(\log N)$ | $O(1)$ | `0 ms (100.00%)` | [solution.java](0704-binary-search/solution.java) | [README.md](0704-binary-search/README.md) |
| 0977 | [Squares of a Sorted Array](https://leetcode.com/problems/squares-of-a-sorted-array/) | ![Easy](https://img.shields.io/badge/Easy-brightgreen?style=flat-square) | Two Pointers Inward Scan | $O(N)$ | $O(N)$ | `1 ms (100.00%)` | [solution.java](0977-squares-of-a-sorted-array/solution.java) | [README.md](0977-squares-of-a-sorted-array/README.md) |
| 1480 | [Running Sum of 1d Array](https://leetcode.com/problems/running-sum-of-1d-array/) | ![Easy](https://img.shields.io/badge/Easy-brightgreen?style=flat-square) | Prefix Sum In-Place Accumulation | $O(N)$ | $O(1)$ | `0 ms (100.00%)` | [solution.java](1480-running-sum-of-1d-array/solution.java) | [README.md](1480-running-sum-of-1d-array/README.md) |
| 1685 | [Sum of Absolute Differences](https://leetcode.com/problems/sum-of-absolute-differences-in-a-sorted-array/) | ![Medium](https://img.shields.io/badge/Medium-yellow?style=flat-square) | Prefix & Suffix Sum Accumulation | $O(N)$ | $O(1)$ | `4 ms (85.17%)` | [solution.java](1685-sum-of-absolute-differences-in-a-sorted-array/solution.java) | [README.md](1685-sum-of-absolute-differences-in-a-sorted-array/README.md) |

---

[⬅️ Back to Main Repository](../README.md)
