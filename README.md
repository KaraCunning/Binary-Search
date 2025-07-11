### Binary-Search

![Binary Search Algorithm](https://www.google.com/
https://media.geeksforgeeks.org/wp-content/uploads/20240506155201/binnary-search-.webp)

##Solution for leetcode  problem 704. Binary Search
  - Description: iven an array of integers nums which is sorted in ascending order, and an integer target, write a function to search target in nums. If target exists, then return its index. Otherwise, return       -1.

  - You must write an algorithm with O(log n) runtime complexity.

# Solution 
Creating left and right pointers.
Determine where the middle of the array is and assign the element as mid
If the mid element is the target - return mid
If the mid element is less than the target - have to move the Left pointer to search the right half of the array. It will return the index of the target if found in the right half of the array.
If the mid element is greater than the target - have to move the Right pointer to search the left half of the array. It will return the index of the target if found in the left half of the array.
If the target is not found - return -1
