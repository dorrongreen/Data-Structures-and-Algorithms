# Arrays

* The aim is to make operations as fast as possible: inserting new items or removing given items from the **data structure**
* Arrays are data structures where all the items are identified by an integer value starting with **0** - the so-called **index**.
* The items of the array are located **right next to each other** in the main memory (**RAM**) - they can be accessed by the **index**.


    * **ADVANTAGE: ACCESSING THE ITEMS - RANDOM ACCESS**


### Example

| INDEX| NUMS|  
|------|----| 
|0|34|
|1|-12|
|2|2|
|3|300|
|4|-45|
|5|0|
|6|5|
|7|1|

* Every single item (value) can be identified with a given **index**.
* Indexes start with **0**.
* Usually we can store items of the same type.
* **Random access:** items are located right next to each other so we can get them with the help of the index - in **O(1)** running time.


### Memory address


| Value |3|12|-2|9|5|
|-|-|-|-|-|-|
|Memory address(id)|0x116|0x132|0x148|0x164|

* **memory address = array's address + index * data size (4 byte)**
    
    * Hence why we can access the values in constant time because the elements are next to each other in memory.

### Two dimensional arrays

 * every single item (value) can be identified with 2 indexes - **rowIndex** and **columnIndex**
 * indexes start with **0**
 * usually we can store items of the same type.
 * **random access:** items are located right next to each other so we can get them with the help of the index - in O(1) running time.


 ### Array Sizing 
* We can store any types of items witht the help of array data structures.
* We use **indexes** (or so-called keys)
* We can create multi-dimentions arrays as well.

|static array|dynamic array|
|-|-|
|size of the array does not change| size of the array may change dynamically|

### Application of Arrays

* More complex data structures rely heavily on arrays because of **random indexing - O(1)** access of items with known indexes.
* Stacks, queues and hash-tables(dictionaries)
* **Numerical methods** use arrays: most the operations can be achieved quite efficiently - matrix related operations