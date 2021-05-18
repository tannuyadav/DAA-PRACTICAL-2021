# DAA-PRACTICAL-2021
Question :1 Complexity: The time-complexity of inserting a single element into an RB-tree is O (log n) where n is the current size of the tree. The time-complexity of inserting n elements into an empty RB-tree is, therefore, O (n log n). The time-complexity of inserting 10 elements into an empty RB-tree is constant, or O (1) Applications: Red-black trees are needed when height balancing is a desirable trait, and insertion/deletion must not be too slow either. RB trees are common in the Linux kernel. Two of the places where you can see it are:

In the Completely Fair Scheduler implementation - the process virtual runtimes serve as the key. To keep track of the virtual memory segments for a process - the start address of the range serves as the key. As you may notice, in both cases it is important to retrieve the node by their key rather quickly from performance considerations. Question-02 Complexity: Sorting of edges takes O(ELogE) time. After sorting, we iterate through all edges and apply the find-union algorithm. The find and union operations can take at most O(LogV) time. So overall complexity is O(ELogE + ELogV) time. The value of E can be at most O(V2), so O(LogV) is O(LogE) the same. Therefore, the overall time complexity is O(ElogE) or O(ElogV) Applications: -Cluster analysis -Image segmentation -Handwriting recognition -Medical Image Processing -Identify patterns in gene expression Question-03 Complexity:

Application: The library has a database that every computer can read from and only the librarian has access to be able to modify the values. This database stores all the information previously made available and adds another value, whether or not the book is available or someone else has it in their possession.

You can now go to the computer and type in the name of the book, the computer will look through the database to find the book in question and then will sort according to whether the book is in stock or not, the location of where it is and how many are available.

Question :2 
Complexity Analysis: Best Case:O(N logE) Worst Case:O(ElogE) or O(ElogV) Average Case:O(ElogE)

Applications:
Spanning tree is basically used to find a minimum path to connect all nodes in a graph. Common application of spanning trees are − a) Civil Network Planning b) Computer Network Routing Protocol c) Cluster Analysis

Question 3:
Bubble
Complexity: a) Worst and Average Case Time Complexity: O(n*n). Worst case occurs when array is reverse sorted. b) Best Case Time Complexity: O(n). Best case occurs when array is already sorted.

Application of Bubble Sort:
a)Due to its simplicity, bubble sort is often used to introduce the concept of a sorting algorithm. b)In computer graphics it is popular for its capability to detect a very small error (like swap of just two elements) in almost-sorted arrays and fix it with just linear complexity (2n).

Selection
Complexity: O(n^2) as there are two nested loops in all cases.

Application:
a)Selection sort almost always outperforms bubble sort and gnome sort. b)Can be useful when memory write is a costly operation c)While selection sort is preferable to insertion sort in terms of number of writes (Θ(n) swaps versus Ο(n^2) swaps). d)This can be important if writes are significantly more expensive than reads, such as with EEPROM or Flash memory, where every write lessens the lifespan of the memory.

Insertion
Complexity: Worst case time complexity: Θ(N^2) comparisons and swaps Average case time complexity: Θ(N^2) comparisons and swaps Best case time complexity: Θ(N) comparisons and Θ(1) swaps

Application:
a)If the cost of comparisons exceeds the cost of swaps, as is the case for example with string keys stored by reference or with human interaction, then using binary insertion sort may yield better performance. b)A variant named binary merge sort uses a binary insertion sort to sort groups of 32 elements, followed by a final sort using merge sort. c)If a skip list is used, the insertion time is brought down to O(log n), and swaps are not needed because the skip list is implemented on a linked list structure. The final running time for insertion would be O(n log n).

Merge
Complexity: Worst case time complexity: Θ(N log N) Average case time complexity: Θ(N log N) Best case time complexity: Θ(N log N) Time complexity of Merge Sort is θ(nLogn) in all 3 cases (worst, average and best) as merge sort always divides the array into two halves and takes linear time to merge two halves.

Applications:
a)Merge Sort is useful for sorting linked lists in O(n Log n) time b)Merge sort can be implemented without extra space for linked lists c)Merge sort is used for counting inversions in a list d)Merge sort is used in external sorting

Quick
Complexity: Worst case time complexity: Θ(N^2) Average case time complexity: Θ(N log N) Best case time complexity: Θ(N log N)

Applications:
a)Quicksort is used everywhere where a stable sort is not needed b)Variants of quicksort are used to separate the k smallest or largest elements c)Quicksort's divide-and-conquer enables the use of parallelization d)Quick Sort is a cache friendly sorting algorithm as it has good locality of reference when used for arrays e)Quick Sort is tail recursive and hence, all tail call optimizations can be done f)Quick Sort is an in-place sort that is does not require any extra storage

