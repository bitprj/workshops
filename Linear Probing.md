Type: text+img

**Title:** Linear probing

By systematically visiting each slot one at a time, we are performing an open addressing technique called **linear probing**. When the hash function causes a collision by mapping a new key to a cell of the hash table that is already occupied by another key, linear probing searches the table for the closest following free location and inserts the new key there. Lookups are performed in the same way, by searching the table sequentially starting at the position given by the hash function, until finding a cell with a matching key or an empty cell. 

Considering the interval between successive probes is fixed (usually to 1), let’s assume that the hashed index for a particular entry is **index**. The probing sequence for linear probing will be:

index = index % hashTableSize
index = (index + 1) % hashTableSize
index = (index + 2) % hashTableSize
index = (index + 3) % hashTableSize 

and so on...

![LP](https://upload.wikimedia.org/wikipedia/commons/thumb/9/90/HASHTB12.svg/600px-HASHTB12.svg.png)

> The collision between John Smith and Sandra Dee (both hashing to cell 873) is resolved by placing Sandra Dee at the next free location, cell 874.

