### Type: Code steps large ###

The 3rd step is to create a pop() function that removes elements from the stack.

```python
  #Removing last element from the stack
    def pop(self):
        if len(self.stack)<=0:
            return ("Stack Empty!")
        return self.stack.pop()
```
