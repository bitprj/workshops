### Type: Code Steps Large ###

2. Add elements to your stack through calling the push() function.

```python
#The process of implementing push() call for stack
myStack = Stack()
print(myStack.push(5)) #prints whether the operation "push" successes
print(myStack.stack)   #print the stack(left is bottom of the stack,right is the top of stack)
print(myStack.push(6)) 
print(myStack.stack)
print(myStack.push(9)) 
print(myStack.stack)
print(myStack.push(5)) 
print(myStack.stack)
print(myStack.push(3)) 
print(myStack.stack)

#The result of the above code
True
[5]
True
[5, 6]
True
[5, 6, 9]
True
[5, 6, 9, 5]
True
[5, 6, 9, 5, 3]
```
