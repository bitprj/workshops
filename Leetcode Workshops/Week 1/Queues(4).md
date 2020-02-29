### Type: Code Steps Large ###

### Title: A Real-life Example of a Queue ###

- You're probably thinking, "Learning about queues is cool and all, but when will I ever apply this in my life?"

- Well today's your lucky day!

- Let's say that you're boarding a plane and you're fighting to get the first front seats of the plane.

1. Let's say that the total amount of passengers is 50 people. Let's add each passenger in the plane using the enqueue() call
   to fill up the number of spots available.
   
```python
passengers = 50 #Total of the current 50 passengers on the plane
boardingPlane = Queue()
int(passengers) = 50

for x in range(passengers):
	boardingPlane.enqueue(x)
  
print(boardingPlane.size()) #result prints a size of 50
```

2. Now you're plane arrived at the Sacarmento airport and the first 30 passengers hopped off the plane while the last 20 waited
   in the back because they're going to catch a different flight right after the plane has landed. We would now remove each of the 
   30 passengers in order using the dequeue() call.
   
```python
frontPassengers = 30 #1st 30 passengers that left the plane
int frontPassengers = 30

for x in range(frontPassengers):
	boardingPlane.dequeue(x)

print(boardingPlane.size()) #result prints a size of 20
```
