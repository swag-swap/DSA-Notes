Priority queues are container based designer such that first element of queue is greatest or smallest.
These are build on top of max heap, uses array or vector as internal structure.


# Syntax

> priority_queue<int, vector<int>> pq;

# Basic functions

'''
pq.size();
pq.top();
pq.swap(); // Swap contents of 2 queues having same size and type
pq.pop();
'''


## Creating a min-heap for priority queue

We can order it in decreasing order

### Syntax

> priority_queue <int, vector<int>, greater<int>> gq;  
