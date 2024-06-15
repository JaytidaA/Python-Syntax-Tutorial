Conditional Statements are a very important part of a programming language, it helps us create different pathways and different logic depending on the previous conditions.

## If blocks
```python
if condition:
	# Code Block if condition is true
	# Indentation matters as it defines the scope
```
## If - Else Blocks
```python
if condition:
	# Code Block if condition is true
else:
	# Code Block if condiiton is false
```
## If - Else if - Else chains
```python
if condition:
	# Code Block 1
elif condition_2:
	# Code Block 2
elif condition_3:
	# Code Block 3
else:
	# Code Block if no condition is satisfied
```
## Match - Case (From Python 3.10 and above)
```python
match(variable):
	case pattern_1:
		# Block 1
	case pattern_2:
		# Block 2
	case pattern_3:
		# Block 3
	case _:
		# Default Block
```
# Conditions
In the above examples, the `conditions` were a set of variables used to determine whether a block of code may be run or not, these conditions are actually boolean variables which can be constructed in many different ways. The two main ways are as follows:
1. Logical: `c1` and `c2` are boolean variables
	1. `c1 and c2`: Returns `True` if and only if both `c1` and `c2` are true.
	2. `c1 or c2`: Returns `True` if either `c1` or `c2` or both are true.
	3. `not(c1)`: Returns `True` if `c1` is `False` and vice-versa.
2. Relational: `a` and `b` are Integers or Floats.
		1. `a < b`: Returns `True` if `a` is less than `b`.
		2. `a <= b`: Returns `True` if `a` is less than or equal to `b`.
		3. `a > b`: Returns `True` if `a` is greater than `b`.
		4. `a >= b`: Returns `True` if `a` is greater than or equal to `b`.
		5. `a == b`: Returns `True` if `a` is equal to `b`.
		6. `a != b`: Returns `True` if `a` is not equal to `b`.