Loops or iterative statements are useful as they prevent us from having to write similar lines of codes many times when we want to repeatedly execute a statement.

## While Loops
Code runs as long as the condition is satisfied.
```python
while condition:
	# Block of code to be executed
	# Control to prevent infinite Loop
```
### While Loops with Lists/Tuples
We make use of the `range` data structure along with the `in` keyword to iterate through a structure more efficiently.
```python
i = 0
while i in range(10):
	# Apply effect to element list[i] or tuple[i]
```

## For Loops
Code runs for a specified number of times. We can make use of the `range` data structure or use a different method as well.
```python
fruits = ["apple", "orange", "banana", "grape", "pear"]
for i in range(len(fruits)):
	# Apply effect to element of list[i] e.g. print
	print(fruits[i])
```
## For Loops with Different Sequences
Using the `in` keyword we can iterate over a sequence of characters using another method.
```python
fruits = ["apple", "orange", "banana", "grape", "pear"]
for fruit in fruits:
	# Apply effect to each element of 'fruits' i.e. 'fruit'
	print(fruit)
```
This method can be used to iterate not only over [[Chapter 4|lists]], but [[Chapter 5|tuples]], [[Chapter 6|dictionaries]] and [[Chapter 9|ranges]] as well.