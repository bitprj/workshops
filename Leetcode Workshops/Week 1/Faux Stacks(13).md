### Type: Code steps Large ###

### Title: Implementing the Stack Class for the Tower of Hanoi Puzzle ###

- We're now going to solve the Tower of Hanoi puzzle using the stack class

1. The 1st step is to initialize the necessary values that we will need for this puzzle (the disk sizes and the type of poles).

```python
#Initializing the necessary items
sourcePole = Stack()
auxPole = Stack()
destPole = Stack()

smallDisk = 1
avgDisk = 2
largeDisk = 3

sourcePole.push(largeDisk)
sourcePole.push(avgDisk)
sourcePole.push(smallDisk)

print(sourcePole.stack)  # print the Initial state of 3 poles
print(auxPole.stack)
print(destPole.stack)

#Result of the code
[3, 2, 1]
[]
[]
```

