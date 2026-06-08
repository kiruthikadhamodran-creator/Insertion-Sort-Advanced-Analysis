Algorithm
Divide the array into two halves using Merge Sort.
Recursively count inversions in the left half.
Recursively count inversions in the right half.
During merging, count cross inversions whenever an element from the right half is placed before an element from the left half.
Sum all inversion counts to get the total number of shifts.
Print the result for each test case.
Time Complexity

O(n log n)

Space Complexity

O(n)

Category
Sorting
Divide and Conquer
Merge Sort
Inversion Count
