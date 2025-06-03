## 📘 Day 22: Binary Search Trees | HackerRank 30 Days of Code

This repository contains the Python solution for Day 22 of the HackerRank 30 Days of Code challenge, focusing on the concept of Binary Search Trees (BST) and calculating tree height using recursive algorithms.

## 🚀 Challenge Summary

-You are required to complete the getHeight method in a Binary Search Tree implementation.

-The method should calculate and return the height of the BST from root to the deepest leaf node.

-Handle edge cases properly: empty trees should return -1, single nodes should return 0.

## 📝 Problem Statement

Complete the Solution class by:

-Implementing the getHeight(root) method that calculates the height of a Binary Search Tree.

-Height is defined as the number of edges on the longest path from root to leaf.

-Use recursive approach to traverse left and right subtrees.

## ✅ Constraints

        1 ≤ Number of nodes ≤ 20
        
        1 ≤ Node data ≤ 50
        
        All values will be unique
        
        BST property is maintained: left ≤ root < right

## 🔢 Sample Input
        7
        3
        5
        2
        1
        4
        6
        7
## ✅ Sample Output
        3
## 💡 Explanation

The BST formed from the input:

        3
       / \
      2   5  
     /   / \
    1   4   6
             \
              7
              
Height Calculation:

-Path 3→2→1 = 2 edges

-Path 3→5→4 = 2 edges

# -Path 3→5→6→7 = 3 edges (longest path)

Therefore, Height = 3

## 🧠 Concepts Practiced

-Binary Search Tree (BST) implementation

-Recursive tree traversal algorithms

-Tree height calculation techniques

-Base case handling in recursion

-Object-Oriented Programming (OOP)

-BST insertion and property maintenance

-Algorithm complexity analysis

## 🛠 How to Run

Option 1: With input file

Create a file named input.txt with the required input and run:

        python3 binary_search_trees.py < input.txt
        
Option 2: Manual input

Just run:

        python3 binary_search_trees.py
        
## 🔗 HackerRank Challenge Link:

        HackerRank – Day 22: Binary Search Trees
        
🏆 Challenge Completed

✅ Problem Solved

🎯 Points Earned: 30

        ⏱️ Time Complexity: O(n)
        
        💾 Space Complexity: O(h)

        where h = height of tree

## 📅 Completed On:

        3rd June 2025
        
## 🔖 Tags

#Python #HackerRank #BinarySearchTree #DataStructures #Algorithms #Recursion #TreeTraversal #30DaysOfCode #ProblemSolving #Day22Challenge #BST #TreeHeight #CleanCode
## ✍ Author

        Harsha M
        
        GitHub: @Harshaharika7
        
        LinkedIn: Harsha M
