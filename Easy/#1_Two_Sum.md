# 1. Two Sum

## 📝 Problem Description
Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.

You may assume that each input would have exactly one solution, and you may not use the same element twice. You can return the answer in any order.


## 💡 Algorithm & Complexity Analysis

### One-Pass Hash Map (Optimized)
* **Time Complexity:** $O(N)$
* **Space Complexity:** $O(N)$
* **Plan:** Look at the numbers that have already been visited. Store `value: index` in a hash map. Then for each number, check if its `target - current` complement already exists in the hash map.
