### Type: Code Steps Large ###
4. Remove elements from the stack by using the pop() function.

```python
#The process of implementing the pop() function call
print(myStack.pop())   #print the value of removed element
print("Current stack :",myStack.stack)   #print the stack now
print(myStack.pop())
print("Current stack :",myStack.stack)
print(myStack.pop())
print("Current stack :",myStack.stack)
print(myStack.pop())
print("Current stack :",myStack.stack)
print(myStack.pop())
print("Current stack :",myStack.stack)
print("the size of the stack now :",myStack.size())  #print the size of stack
print(myStack.pop())

#The result of the code
3
Current stack : [5, 6, 9, 5]
5
Current stack : [5, 6, 9]
9
Current stack : [5, 6]
6
Current stack : [5]
5
Current stack : []
the size of the stack now : 0
Stack Empty!
```
