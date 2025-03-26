# Data Structures

    Why do Data structures exist? 
        In order to manage larged amounts of data efficiently for uses such as large databases and internet indexing.(Google)
    
    Modern applications and software are manipulating a huge amount of data.
        Ex.
            Facebook users
            Instagram images
            Twitter posts

    How do we deal with the huge amounts of data?
        A: Data Structures

    Somehow we have to make sure the application is as fast as possible,
    this is why the right "data structure" is crucial.

 
# Data Structures Overview
    a. We use "data structures" to store data in an efficient way.
    b. We often have the intuition: if we want to make an algorithm fast, we have to optimize it (fewer operations, avoid nested for loops etc.)
    c. A way to organize and store data 
    d. After organizing data it becomes easy to process.
    e. Make every calcuation/function as fast as possible
    f. BUT algorithms can be boosted up by proper data structures
    g. Data structures make sure the running time will be better.

        "Bad programmers worry about the code. Good programmers worry about data structures and their relationships"



# Case example

### <ins>Djisktra Algorithm</ins>
    
        a. Can find the shortest paths from a starting node to all other nodes in a graph.  

* Without a **"proper"** data structure (heap - priority queue) the running time would be quadratic O(N^2)
        
        This approach will use "less memory" but the have a "greater time complexity".
                                    Slow


* The priority queue approach makes sure the running time will be far better - the running time complexity is reduced to linearithmic O(NlogN)
        
        This approach will use "more memory" but have a "lowest time complexity".
        
                                    Fast

# Main point
    *  There is a trade-off between "running time complexity" and "memory complexity" we can use data structures (and more memory) to boost up an algorithm.


    


###    Example processes
    add, delete, sort, 
    create, read, update, delete(CRUD)


# Types of Data Structures

    1. Linear - arranged in a sequential manner - easy to traverse
        a. Array 
        b. Linked List
        c. Stack
        d. Queue
    2. Non-Linear - are not in sequence but multi-level - not easy to implement
        a. Tree
        b. Graph