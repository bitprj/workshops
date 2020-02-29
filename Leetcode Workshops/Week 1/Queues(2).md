### Type of Card: Code left/right ###

### Title: Implementing a Queue ###

- We're going to make a Queue class to show how the Queue itself works.

- enqueue() adds elements to the rear of the queue.

- dequeue() deletes elements from the front of the queue.

- size() looks at the current size that the Queue has.

- printQueue() prints out the current elements that are inside the queue

```python

class Queue:
    #Constructor creates a list
    def __init__(self):
       self.queue=[]

    #Adding elements to queue
    def enqueue(self,data):
        self.queue.insert(0,data)
        return True

    #Removing the last element from the queue
    def dequeue(self):
        return self.queue.pop()

    #Getting the size of the queue
    def size(self):
        return len(self.queue)

    #printing the elements of the queue
    def printQueue(self):
        return self.queue
        
 ```
