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

2. The 2nd step is to place the smallest disk into our 3rd pole (`destPole`).

```python
#Moving the smallest disk to the 3rd pole
disk = sourcePole.pop() #remove the top disk of source pole to destination pole
destPole.push(disk)

print(sourcePole.stack) #print the state now
print(auxPole.stack)
print(destPole.stack)

#Result of the code
[3, 2]
[]
[1]
```

3. The 3rd step is to place the medium sized disk into our 2nd pole ('auxPole`).

```python
#Moving the medium sized disk into the 2nd pole
disk = sourcePole.pop() #remove the top disk of source pole now to destination pole
auxPole.push(disk)

print(sourcePole.stack) #print the state now
print(auxPole.stack)
print(destPole.stack)

#Result of the code
[3]
[2]
[1]
```

4. The 4th step is to place the smallest disk into our 2nd pole.

```python
#Moving the smallest disk into our 2nd pole
disk=destPole.pop()
auxPole.push(disk)

print(sourcePole.stack)
print(auxPole.stack)
print(destPole.stack)

#Result of the code
[3]
[2, 1]
[]
```

5. The 5th step is to place the largest disk into our 3rd pole.

```python
#Moving the largest disk into our 3rd pole
disk=sourcePole.pop()
destPole.push(disk)

print(sourcePole.stack)
print(auxPole.stack)
print(destPole.stack)

#Result of the code
[]
[2, 1]
[3]
```

6. The 6th step is to place the smallest disk into our 1st pole(`sourcePole`).

```python
#Moving the smallest disk into our 1st pole
disk=auxPole.pop()
sourcePole.push(disk)

print(sourcePole.stack)
print(auxPole.stack)
print(destPole.stack)

#Result of the code
[1]
[2]
[3]
```

7. The 7th step is to place the medium sized disk into our 3rd pole.

```python
#Moving the medium sized disk into our 3rd pole
disk=auxPole.pop()
destPole.push(disk)

print(sourcePole.stack)
print(auxPole.stack)
print(destPole.stack)

#Result of the code
[1]
[]
[3, 2]
```

8. The final step would be to place the smallest disk into the pole and just like that, we solved the Tower of Hanoi :)

```python
#Moving the smallest disk into our 3rd pole
disk=sourcePole.pop()
destPole.push(disk)

print(sourcePole.stack)
print(auxPole.stack)
print(destPole.stack)

#Result of the code
[]
[]
[3, 2, 1]
```
