<div align="center">

# 📅 Week 4: Queues, Deques, Monotonic Queues & BFS
### *Applied Coding Skills (S1L10) — Module 4*

[![Problems Solved](https://img.shields.io/badge/Solved-9%2F9-6366f1?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/)
[![Easy](https://img.shields.io/badge/🟢_Easy-2-10b981?style=for-the-badge)](https://leetcode.com/)
[![Medium](https://img.shields.io/badge/🟡_Medium-6-f59e0b?style=for-the-badge)](https://leetcode.com/)
[![Hard](https://img.shields.io/badge/🔴_Hard-1-ef4444?style=for-the-badge)](https://leetcode.com/)
[![Language](https://img.shields.io/badge/Language-Java-b07219?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com/)

<p align="center">
  Focuses on FIFO data structures, array-based circular ring buffers, monotonic double-ended queues (Deques) for sliding window extrema, greedy task scheduling, and level-order Breadth-First Search (BFS) tree traversals.
</p>

</div>

---

## 🎯 Learning Objectives

- **Queue Emulation via Stacks:** Architecting FIFO semantics using two LIFO stacks with amortized $O(1)$ push/pop complexity.
- **Circular Buffer Design:** Managing front and rear indices using modulo arithmetic for fixed-capacity circular queues and deques.
- **Monotonic Deques & Extremum Windows:** Maintaining running maximums and minimums over dynamic sliding windows in linear $O(N)$ amortized time.
- **Sliding Subarray Bounds:** Coordinating dual monotonic deques to enforce maximum absolute difference limits across variable subarrays.
- **Tree Level-Order Traversal (BFS):** Processing hierarchical tree levels sequentially using standard FIFO queue structures.
- **Right-Side Tree Projection:** Extracting visible node boundaries from tree breadth-first and depth-first perspectives.
- **Greedy Scheduling with Cooldown:** Formulating optimal CPU idle-slot requirements based on highest-frequency task counts.

---

## 📋 Problem Directory

| # | Problem Title | Difficulty | Key Pattern / Concept | Time | Space | Performance | Solution | Notes |
| :---: | :--- | :---: | :--- | :---: | :---: | :---: | :---: | :---: |
| 0102 | [Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/) | ![Medium](https://img.shields.io/badge/Medium-yellow?style=flat-square) | Breadth-First Search (BFS) / Queue | $O(N)$ | $O(N)$ | `1 ms (95.80%)` | [solution.java](0102-binary-tree-level-order-traversal/solution.java) | [README.md](0102-binary-tree-level-order-traversal/README.md) |
| 0199 | [Binary Tree Right Side View](https://leetcode.com/problems/binary-tree-right-side-view/) | ![Medium](https://img.shields.io/badge/Medium-yellow?style=flat-square) | BFS Level-End / Depth-First Scan | $O(N)$ | $O(H)$ | `0 ms (100.00%)` | [solution.java](0199-binary-tree-right-side-view/solution.java) | [README.md](0199-binary-tree-right-side-view/README.md) |
| 0232 | [Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks/) | ![Easy](https://img.shields.io/badge/Easy-brightgreen?style=flat-square) | Two Stacks / Amortized FIFO | $O(1)$ *amortized* | $O(N)$ | `2 ms (18.03%)` | [solution.java](0232-implement-queue-using-stacks/solution.java) | [README.md](0232-implement-queue-using-stacks/README.md) |
| 0239 | [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | ![Hard](https://img.shields.io/badge/Hard-red?style=flat-square) | Monotonic Decreasing Deque | $O(N)$ | $O(k)$ | `29 ms (85.20%)` | [solution.java](0239-sliding-window-maximum/solution.java) | [README.md](0239-sliding-window-maximum/README.md) |
| 0621 | [Task Scheduler](https://leetcode.com/problems/task-scheduler/) | ![Medium](https://img.shields.io/badge/Medium-yellow?style=flat-square) | Greedy / Frequency & Idle Slots | $O(N)$ | $O(1)$ | `4 ms (73.21%)` | [solution.java](0621-task-scheduler/solution.java) | [README.md](0621-task-scheduler/README.md) |
| 0622 | [Design Circular Queue](https://leetcode.com/problems/design-circular-queue/) | ![Medium](https://img.shields.io/badge/Medium-yellow?style=flat-square) | Ring Buffer Array / Modulo Math | $O(1)$ | $O(k)$ | `4 ms (100.00%)` | [solution.java](0622-design-circular-queue/solution.java) | [README.md](0622-design-circular-queue/README.md) |
| 0641 | [Design Circular Deque](https://leetcode.com/problems/design-circular-deque/) | ![Medium](https://img.shields.io/badge/Medium-yellow?style=flat-square) | Circular Array / Head-Tail Pointers | $O(1)$ | $O(k)$ | `4 ms (100.00%)` | [solution.java](0641-design-circular-deque/solution.java) | [README.md](0641-design-circular-deque/README.md) |
| 0933 | [Number of Recent Calls](https://leetcode.com/problems/number-of-recent-calls/) | ![Easy](https://img.shields.io/badge/Easy-brightgreen?style=flat-square) | Sliding Window Queue / Eviction | $O(1)$ *amortized* | $O(W)$ | `19 ms (93.36%)` | [solution.java](0933-number-of-recent-calls/solution.java) | [README.md](0933-number-of-recent-calls/README.md) |
| 1438 | [Longest Continuous Subarray With Limit](https://leetcode.com/problems/longest-continuous-subarray-with-absolute-diff-less-than-or-equal-to-limit/) | ![Medium](https://img.shields.io/badge/Medium-yellow?style=flat-square) | Dual Monotonic Deques + Window | $O(N)$ | $O(N)$ | `29 ms (96.61%)` | [solution.java](1438-longest-continuous-subarray-with-absolute-diff-less-than-or-equal-to-limit/solution.java) | [README.md](1438-longest-continuous-subarray-with-absolute-diff-less-than-or-equal-to-limit/README.md) |

---

[⬅️ Back to Main Repository](../README.md)
