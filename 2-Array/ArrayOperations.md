## Array Operations

1. **<ins>adding items</ins>:** we can insert new items at the end of the data structure until the data structure is not full - **O(1)** running time.

* <ins>What if the data structure becomes full?</ins>
    * Have to allocate a larger chunk of memeory in the **RAM** (usually **2x** the size of the actual array)
    * Have to copy the exiting items one by one to the new array.
    * Because of the these operations: the resize operation take **O(N)** linear running time complexity - "bottleneck"



        |start with a small sized array|or | allocate a huge array at the beginning|
        |-|-|-|
        |we do not waste memory| |we do waste memory because of the large size|
        |we have to resize the array often| | we don't bother with the resize operation|
        |**O(N)** running time| | have to bother with the resize operation|

        ## MEMORY AND RUNNING TIME TRADE-OFF !!!
2. **<ins>adding numbers to arbitrary positions:</ins>** we want to inserta n item to an arbitrary position - so associated with a given index.
    
    * It is an **O(N)** linear running time algorithm because the items must be shifted
    (in worst-case: all the items)

3. **<ins>removing last item:</ins>** removing the last item of an array data structure is quite easy and fast operation - **O(1)** running time
4. **<ins>removing item from arbitrary position</ins>:** usually we don not know the index of the item we want to remove. After removing the item we have to deal with the so called "holes" in the data structures.
    * first we have to find the item in **O(N)** running time, then remove the item in **O(1)** and finally have to shift the other items in **O(N)**  


        **Manipulating the last item (insertion or removal):** 
           
        *  O(1) running time - this is why we like arrays

        **Manipulating arbitrary item (insertion or removal):**

        * O(N) running time - if these kinds of operation will dominate then array data structure is not the best option !!!

## Array - Advantages

* The best feature of arrays is **random access:** we can access arbitrary items extremely fast with indexes
* quite an **easy data structure:** easy to understand and easy to implement as well.
* Arrays are fast data structures in the main
* Use arrays when you wan to manipualte the **last items** of the data structure or you want to access items with **known indexes**.

## Array - Disadvantages

* We have to know the number of items we want to store at ***compile time:*** so it is not a dynamic data structure.
* Since it is not dynamic: Whenever the data structure is full, we have to resized it in **O(N)** linear running time.
* Usually we can not store items with different types in an array - of course Python is the exception.