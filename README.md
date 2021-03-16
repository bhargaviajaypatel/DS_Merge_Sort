# DS_Merge_Sort
1. Divide :- means partitioning the n-element array to be sorted into two sub-arrays of n/2 elements in each sub-array.
2. Conquer :- means sorting the two sub-arrays recursively using merge sort.
3. Combine :- means merging the two sorted sub-arrayof size n/2 each to produce the sorted array of n elements. Merge sort algorithm focuses on two main concepts to improve its performance:-
      1. Running time :- A smaller list takes few steps and thus less time to sort than a large list. Less steps, thus less time is needed to create a sorted list from two sorted list rather than creating it using two unsorted lists.
The basic steps of a merge sort algorithm are as follows :- 
            1. If the array is of length 0 or 1 , then it is already sorted. Otherwise,
(Concetually) divide the unsorted array into two sub-arrays of about half the size. Use merge sort algorithm recursively to sort each sub-array. Merge the two sub-arrays to form a sigle sorted list.
