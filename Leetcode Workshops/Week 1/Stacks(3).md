### Type: Code Steps Large ###

### Title: Testing out your Stack Class ###

- If you're curious on testing out your stack class, here's an example of how to do it.

1. Initialize your stack class to a stack variable that you're creating.

```python
myStack = Stack()
```

2. Add elements to your stack through calling the push() function.

```python
#The process of implimenting push() call for stack
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

3. Check the current size of the stack by using the size() function.

```python
#The process of implimenting the size() function call
print(myStack.size())   

#The result of the code
5
```

4. Remove elements from the stack by using the pop() function.

```python
#The process of implimenting the pop() function call
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
