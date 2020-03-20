### Type: Code Steps Large ###

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
