### Type of Card: Code left/right ###

-We’re now going to create our enqueue() function in the queue class.

- enqueue() adds elements to the rear of the queue.

```python
   
 #Adding elements to queue
    def enqueue(self,data):
        self.queue.insert(0,data)
        return True
```
