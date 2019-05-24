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
* 
