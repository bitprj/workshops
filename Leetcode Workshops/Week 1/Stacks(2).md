### Type: Code steps large ###

### Title: Implementing a Stack ###

- Now that you have seen an example of what a stack is, let's put this knowledge into practice.

- Before we get into the code, we should go over how each function in a stack works.

- push() adds elements to the front of the stack (stacking items on top) and pop() remeoves the latest elements that are on top of the
  stack.
  
- Now that you know these basics, let's make our stack class.

1. The 1st step is to intialize our stack class with stack() being an empty list.

```python
class Stack:

    #Constructor creates a list
    def __init__(self):
        self.stack = list()
```

2. The 2nd step is to create a push() function that adds elements to the stack.

```python
  #Adding elements to stack
    def push(self,data):
        self.stack.append(data)
        return True
```

3. The 3rd step is to create a pop() function that removes elements from the stack.

```python
  #Removing last element from the stack
    def pop(self):
        if len(self.stack)<=0:
            return ("Stack Empty!")
        return self.stack.pop()
```

4. The final step is to create a size() function that returns our current size of the stack.

```python
#Getting the size of the stack
    def size(self):
        return len(self.stack)
````
