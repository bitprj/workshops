### Type: Code Steps Large ###

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
