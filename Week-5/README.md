<div align="center">

# 📅 Week 5: Binary Trees, Depth-First Search (DFS) & Tree Traversals
### *Applied Coding Skills (S1L10) — Module 5*

[![Problems Solved](https://img.shields.io/badge/Solved-5%2F5-6366f1?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/)
[![Easy](https://img.shields.io/badge/🟢_Easy-5-10b981?style=for-the-badge)](https://leetcode.com/)
[![Medium](https://img.shields.io/badge/🟡_Medium-0-f59e0b?style=for-the-badge)](https://leetcode.com/)
[![Hard](https://img.shields.io/badge/🔴_Hard-0-ef4444?style=for-the-badge)](https://leetcode.com/)
[![Language](https://img.shields.io/badge/Language-Java-b07219?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com/)

<p align="center">
  Focuses on hierarchical binary tree structures, recursive and iterative Depth-First Search (DFS) traversals (Inorder, Preorder, Postorder), structural tree equivalence, and mirror symmetry validation.
</p>

</div>

---

## 🎯 Learning Objectives

- **Inorder Traversal (L-Root-R):** Traversing the left subtree, visiting the root, and exploring the right subtree; yields monotonic sequences in BSTs.
- **Preorder Traversal (Root-L-R):** Visiting the root node before traversing child subtrees; emulating recursion using an explicit LIFO `Stack<TreeNode>`.
- **Postorder Traversal (L-R-Root):** Bottom-up child subtree processing before evaluating the parent node; essential for tree deletion and post-order dependency evaluations.
- **Structural Tree Equivalence:** Validating simultaneous topological shapes and node values across dual binary trees via recursive base cases.
- **Mirror Symmetry & Reflection:** Formulating cross-branch mirror comparisons (`left.left == right.right` and `left.right == right.left`) to determine bilateral tree symmetry.

---

## 📋 Problem Directory

| # | Problem Title | Difficulty | Key Pattern / Concept | Time | Space | Performance | Solution | Notes |
| :---: | :--- | :---: | :--- | :---: | :---: | :---: | :---: | :---: |
| 0094 | [Binary Tree Inorder Traversal](https://leetcode.com/problems/binary-tree-inorder-traversal/) | ![Easy](https://img.shields.io/badge/Easy-brightgreen?style=flat-square) | Recursive Inorder Traversal (L-Root-R) | $O(N)$ | $O(H)$ | `0 ms (100.00%)` | [solution.java](0094-binary-tree-inorder-traversal/solution.java) | [README.md](0094-binary-tree-inorder-traversal/README.md) |
| 0100 | [Same Tree](https://leetcode.com/problems/same-tree/) | ![Easy](https://img.shields.io/badge/Easy-brightgreen?style=flat-square) | Structural Recursion / Dual Tree DFS | $O(N)$ | $O(H)$ | `0 ms (100.00%)` | [solution.java](0100-same-tree/solution.java) | [README.md](0100-same-tree/README.md) |
| 0101 | [Symmetric Tree](https://leetcode.com/problems/symmetric-tree/) | ![Easy](https://img.shields.io/badge/Easy-brightgreen?style=flat-square) | Mirror Reflection Recursion / Dual DFS | $O(N)$ | $O(H)$ | `0 ms (100.00%)` | [solution.java](0101-symmetric-tree/solution.java) | [README.md](0101-symmetric-tree/README.md) |
| 0144 | [Binary Tree Preorder Traversal](https://leetcode.com/problems/binary-tree-preorder-traversal/) | ![Easy](https://img.shields.io/badge/Easy-brightgreen?style=flat-square) | Iterative DFS / Explicit Stack (Root-L-R) | $O(N)$ | $O(H)$ | `1 ms (6.65%)` | [solution.java](0144-binary-tree-preorder-traversal/solution.java) | [README.md](0144-binary-tree-preorder-traversal/README.md) |
| 0145 | [Binary Tree Postorder Traversal](https://leetcode.com/problems/binary-tree-postorder-traversal/) | ![Easy](https://img.shields.io/badge/Easy-brightgreen?style=flat-square) | Recursive Postorder Traversal (L-R-Root) | $O(N)$ | $O(H)$ | `0 ms (100.00%)` | [solution.java](0145-binary-tree-postorder-traversal/solution.java) | [README.md](0145-binary-tree-postorder-traversal/README.md) |

---

[⬅️ Back to Main Repository](../README.md)
