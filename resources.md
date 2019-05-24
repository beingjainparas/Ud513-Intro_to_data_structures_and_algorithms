# Data Structures & Algorithms in Python
## Lesson 1: Introduction and Efficiency
* **Efficiency:** Time and Space complexity with example of cutting hair
* **Notation:** Explain O(n) with cipher example, also talk about approximation
  * Best case, Average case vs Worst case scenarious with 26 Alphabets.
* **Note:** Anything that can be approximated to O(n) can be said to occur "in linear time". If you plotted n = y on a graph, it would be a line. You can read about other possible time complexities [here](https://en.wikipedia.org/wiki/Time_complexity#Table_of_common_time_complexities).
  * [Big-O Cheet Sheet](http://bigocheatsheet.com/)

## Lesson 2: List-Based Collections
* **Collection:** Group of things, Not in order, Need not be of same type.
* **Lists:** It has all the properties of collection, But it has a order, Need or need not be of same type.
* **Arrays:** It has all the properties of collection, But it has a order, Need or need not be of same type, May or may not be of fixed length, Insertion and deletions takes O(n) linear time which is huge.
* **Note:** Inserting into a Python list is actually O(n), while operations that search for an element at a particular spot are O(1). You can see the runtime of other list operations [here](https://wiki.python.org/moin/TimeComplexity), If you aren't already comfortable with Python lists, you can look through this [lesson](https://developers.google.com/edu/python/lists) about basic Python list manipulation.
* **Linked List:** Extension of list, it has order but does not have indexes, it has links, adding and deleting element takes less time, it just store the memory reference of next element and not index, we also have doubly linkedlist which store memory reference of previous and next element.
* **Stacks:** Also a list based datastructures, Lifo processing are applied on stacks, easy acces to top elements, basically can be made by singly linked list, as it is  pretty abstract.
* **Queues:** Its ia a n opposite of stack, Fifo processing are applied on queues, example purchasing tickets on ticket counter, the first element in the queue is called head and the last elemnt in the queue is called tail, wen you add an element in queue it is called enqueue, and when you delete element from the queue it is called dequeue, peek is when you just look on the head element, again you can implement this data structure using linked list. deck is a mixture of stack and queue, priority queues are ones which has priority assigned to each value and the enque and deque operations takes place based on priority.

## Lesson 3: Searching and Sorting
* **Binary Search:**
  * An Algorithm used to search element in an sorted array effiiently, the efficiency of binary search is O(logn), always create a result table when you dont know the efficiency of an particular algorithm. log8 = 3, 2raiseto3 = 8.
  * Searches and sorts can be very hard to visualize and understand. If you need, go through the video a few more times until it really sinks in. [Here](http://www.cs.armstrong.edu/liang/animation/web/BinarySearch.html) is a supplementary visualization that might help as well, check out [this](https://www.cs.usfca.edu/~galles/visualization/Search.html) visualization too which has a coded solution.
  * Python lists have a method called ```index()```, which just does a search and returns the first index with an instance of that value. Next, you're going to write a binary search function that has the same result, but searches faster. Keep in mind the constraint for this exercise—for binary search, elements need to be in increasing order.
 * **Recursion:**
   * 1: It should call itself, 2: It should have a base case, othewise it goes in a an infinite loop, 3: input should be different while calling recursion.
   * Example of a recursive function which returns zero, and returns nth fibonacci element.
* **Sorting:**
  * There are many sorting algorithms, example the naive approach to sort people according to heigt will be to compare first two person at a time.
  * Space complexities should always be deal with if you have large data, as inplace sorting does sorting in same array, rather then creating new array.
* **Bubble Sort:**
  * Its is a great example of inplace sorting algorithm
  * It takes (n-1) iterations and (n-1) comparisiion each time which gives worst and average case complexities as O(nsquare) and best case complexities as O(n) with space complexity of O(1).
  * Sorting techniques can be tricky—sometimes the best way to understand them is to watch a visual of a sorting algorithm in action again and again. When I was first learning sorting, I used to check out the [Wikipedia page](https://en.wikipedia.org/wiki/Bubble_sort) for each sort. There's normally some colorful illustration near the top, then a GIF showing the sort in action. There are plenty of other visualizations on the World Wide Web—take the time to look around if you need it!
* **Merge Sort:**
  * It happens via divide and conquer, you break array into two element each, and then sort those, you then combine two small arrays and sort them untill you get the final whole array.
  * It takes n comparission for logn steps each time which gives worst and average case complexities as O(nlogn) and best case complexities as O(nlogn) with space complexity of O(n).
  * Sorting is pretty tedious—take a break and check out [this comic](https://xkcd.com/1185/) inspired by merge sort. 
  * You can learn more about merge sort, as well as see many more visualizations, in the online Algorithms [textbook](https://algs4.cs.princeton.edu/22mergesort/). This book is often nice for a more in-depth analysis of topics, but beware—all of the examples are in Java! For merge sort, it's particularly worth reading up on top-down and bottom-up merge sort.
* **Quick Sort:**
  * Its is an example of inplace sorting algorithm, you take a pivot element usually the last one and take that pivot elemnet to its exact location by having all elemnet smaller then pivot to left and larger then pivot to right.
  * It takes n-1 comparission for each steps each time which gives worst case complexities as O(nsquare) and average case and best case complexities as O(nlogn) with space complexity of O(1) as it is inplace.
  * Sorting is pretty tedious—take a break and check out [this comic](https://xkcd.com/1185/) inspired by merge sort. 
  * You can learn more about merge sort, as well as see many more visualizations, in the online Algorithms [textbook](https://algs4.cs.princeton.edu/22mergesort/). This book is often nice for a more in-depth analysis of topics, but beware—all of the examples are in Java! For merge sort, it's particularly worth reading up on top-down and bottom-up merge sort.
* **Note:**
  * Congrats on getting through three different types of sorts! You should also investigate some of the other famous sorting algorithms. You can watch all of them in action [here](https://visualgo.net/en/sorting?slide=1) (and see a coding solution too).
