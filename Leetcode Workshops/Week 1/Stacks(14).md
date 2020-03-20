### Type: Code Steps Large ###

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
