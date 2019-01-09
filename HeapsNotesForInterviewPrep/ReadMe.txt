Heaps can be implemented as either arrays or trees.

Heaps in tree form require based upon whether or not its a min heap or max heap:
1. Max heap parent is greater than children, Min heap parent is less than children


This differs from binary trees in that it is a loose sorting where you only will know the exact location of the highest or lowest value
there is no left to right sort in a heap. 

Heaps are primarily used for priority queues.
As they beat bsts in findmin/findmax(O(1)) whereas bsts beat them everywhere else at 0(logN) for all searches.
Binary heap is also preferred because they can be implemented in an array based structure which is more friendly to caching.