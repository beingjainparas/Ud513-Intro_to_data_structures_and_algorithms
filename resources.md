# Data Structures & Algorithms in Python
## Lesson 1: Introduction and Efficiency
* Efficiency: Time and Space complexity with example of cutting hair
* Notation: Explain O(n) with cipher example, also talk about approximation
* Best case, Average case vs Worst case scenarious with 26 Alphabets.
* **Note:** Anything that can be approximated to O(n) can be said to occur "in linear time". If you plotted n = y on a graph, it would be a line. You can read about other possible time complexities [here](https://en.wikipedia.org/wiki/Time_complexity#Table_of_common_time_complexities).
* [Big-O Cheet Sheet](http://bigocheatsheet.com/)

## Lesson 2: List-Based Collections
* Collection: Group of things, Not in order, Need not be of same type.
* Lists: It has all the properties of collection, But it has a order, Need or need not be of same type.
* Arrays: It has all the properties of collection, But it has a order, Need or need not be of same type, May or may not be of fixed length, Insertion and deletions takes O(n) linear time which is huge.
* **Note:** Inserting into a Python list is actually O(n), while operations that search for an element at a particular spot are O(1). You can see the runtime of other list operations [here](https://wiki.python.org/moin/TimeComplexity), If you aren't already comfortable with Python lists, you can look through this [lesson](https://developers.google.com/edu/python/lists) about basic Python list manipulation.
* Linked List: Extension of list, it has order but does not have indexes, it has links, adding and deleting element takes less time.
