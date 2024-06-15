Strings are a data type in Python used to represent collections of alphanumeric symbols and textual data.

## Basic String Properties
1. String Length: We can find out the length of a string in two different ways.
	+ Using the `__len__()` property.
	+ Using the `len()` method.
```python
>>> line.__len__()
5

>>> len(line)
5
```
2. String Indices: You can access each element of the string using the `[]` operator and its corresponding index.
```python
>>> line[0]
H

>>> line[1]
e

>>> line[2]
l

>>> line[3]
l

>>> line[4]
o
```
## String Methods
There are many different methods defined in the `str` class. Here are a few which are widely used:
1. `lower()/upper()`: Converts the string to Lowercase/Uppercase format.
2. `islower()/isupper()`: Returns a boolean value if string is entirely uppercase or lowercase.
3. `index(x)`: Returns the first index of the element 'x' inside the string.
4. `replace(str1, str2)`: Replaces the sub string `str1` with the sub string `str2`.
5. `count(x)`: Returns the number of times the element 'x' appears inside the string.

## Concatenation
We can concatenate two strings to form a new string using the `+` operator
```python
str1 = "Hello"
str2 = "World!"
print(str1 + " " + str2)
```
will give the output
```
Hello World!
```