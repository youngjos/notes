# Algorithms

### Searching
### Sorting

<details>
  <summary>Insertion Sort</summary>
  Insertion sort is a simple sorting algorithm that works the way we sort playing cards in our hands

  It takes an array as input and returns a new, sorted array

  ![](../img/insertionsort.png)

  **Space Complexity** O(n) with O(1) auxiliary

  **Performance**
  - Worst Case O(n^2) comparisons
  - Best Case O(n) comparisions
  - Average O(n^2) comparisions
</details>

<details>
  <summary>Merge Sort</summary>
  Merge sort is a divide and conquer algorithm
  
  Conceptually, a merge sort works as follows:
  - Divide the unsorted list into n sublists, each containing one element (a list of one element is considered sorted).
  - Repeatedly merge sublists to produce new sorted sublists until there is only one sublist remaining. This will be the sorted list
  
  ![](../img/mergesort.gif)
  
  **Space Complexity** O(n) with O(n) auxiliary, O(1) auxiliary with linked lists

  **Performance**
  - Worst Case O(n log n) comparisons
  - Best Case O(n log n) comparisions
  - Average O(n log n) comparisions
</details>
