### Type: Code Steps Large ###

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
