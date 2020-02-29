### Type: Code Steps Large ###

### Title: What's a Deque? ###

- A deque (or a double ended queue) is a data structure that removes and adds elements from either the front or the rear of a queue.

- We're going to show you an example on how to implement a deque.

1. Import the deque library.

```python
from collections import deque
```

2. Create your queue of elements while calling the deque function.

```python
# Creating a Queue
queue = deque([1,5,8,9])
```

3. Append elements towards the rear of the queue.

```python
# Enqueuing elements to the Queue
queue.append(7) #[1,5,8,9,7]
queue.append(0) #[1,5,8,9,7,0]
```

4. This is where you can implement the deque() properly when you dequeuing elements. For deque, you would use the popleft() function
   to delete elements in the front of the list (the version of deleting elements from the rear is popright()).
   
```python
# Dequeuing elements from the Queue
queue.popleft() #[5,8,9,7,0]
queue.popleft() #[8,7,9,0]
```

5. You can call the print() function to check what elements are still in the queue.

```python
#Printing the elements of the Queue
print(queue)
```
