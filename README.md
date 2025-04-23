# Merge-Sorted-Array

📌 Problem Description

You are given two integer arrays `nums1` and `nums2`, sorted in non-decreasing order, and two integers `m` and `n` representing the number of elements in `nums1` and `nums2` respectively.
**Note:**  
- `nums1` has enough space (size that is `m + n`) to hold all the elements of `nums2`.
### 🔧 Your Task
Merge `nums2` into `nums1` as one sorted array **in-place** (without using extra space).
---
## 🧪 Example
```python
Input:
nums1 = [1,2,3,0,0,0], m = 3  
nums2 = [2,5,6],       n = 3

Output:
[1,2,2,3,5,6]
...
This problem looked simple… but I struggled with it for over a day and a half.
Tried YouTube videos 🎥
Asked people on LinkedIn 📩
Got no responses and felt pretty stuck 😔
Eventually, I broke the code down line-by-line and finally understood how to merge from the end using three pointers.
And then it hit me — this was actually such an easy idea.
I genuinely thought, “How was I this dumb before?” 😂
💡 Key Concepts
Three pointers:
first_index → points to the end of actual numbers in nums1
second_index → points to the end of nums2
merge_position → points to the end of nums1 (where merged numbers go)
Start from the end of both lists and fill the largest numbers from back to front.
🔄 Time & Space Complexity
Time: O(m + n)
Space: O(1) (in-place merge)
