# insertion-sort
Insertion sort is an algorithm used to sort a collection of elements in ascending or descending order. The basic idea behind the algorithm is to divide the list into two parts: a sorted part and an unsorted part.

Initially, the sorted part contains only the first element of the list, while the rest of the list is in the unsorted part. The algorithm then iterates through each element in the unsorted part, picking one at a time, and inserts it into its correct position in the sorted part.


![image](https://user-images.githubusercontent.com/125429673/234467245-9d3d85ad-9c7a-4276-9f13-4ba1e6084928.png)



To do this, the algorithm compares the current element with each element in the sorted part, starting from the rightmost element. It continues to move to the left until it finds an element that is smaller (if sorting in ascending order) or larger (if sorting in descending order) than the current element.

Once the correct position has been found, the algorithm shifts all the elements to the right of that position to make room for the current element, and then inserts the current element into its correct position.


This process continues until all the elements in the unsorted part have been inserted into their correct positions in the sorted part, resulting in a fully sorted list.

One of the advantages of insertion sort is that it is an in-place sorting algorithm, which means that it does not require any additional storage space other than the original list. Additionally, it has a time complexity of O(n^2), which makes it suitable for small datasets, but not for large ones.

Overall, insertion sort is a simple, yet effective sorting algorithm that can be used for small datasets or as a part of more complex algorithms.

Characteristics of Insertion Sort:
This algorithm is one of the simplest algorithm with simple implementation
Basically, Insertion sort is efficient for small data values
Insertion sort is adaptive in nature, i.e. it is appropriate for data sets which are already partially sorted.
