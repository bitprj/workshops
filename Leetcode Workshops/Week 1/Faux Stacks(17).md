### Type: Code Steps Large ###

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
