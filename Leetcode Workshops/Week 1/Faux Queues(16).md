### Type of Card: Code left/right ###

-Now you're plane arrived at the Sacramento airport and the first 30 passengers hopped off the plane while the last 20 waited
   in the back because they're going to catch a different flight right after the plane has landed. We would now remove each of the 
   30 passengers in order using the dequeue() call.
   
```python
frontPassengers = 30 #1st 30 passengers that left the plane
int frontPassengers = 30

for x in range(frontPassengers):
	boardingPlane.dequeue(x)

print(boardingPlane.size()) #result prints a size of 20
```
