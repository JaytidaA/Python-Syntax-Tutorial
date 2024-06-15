A special data structure present in Python called "List" is used to hold multiple values. These values can be of the same type or of different types.

A list is declared as follows:
```python
friends = ["Aaditya", "Akshat", "Anshu", "Ujjwal"]
```
## List functions
1. `extend(List_B)`: Used to extend the original list by adding elements of `List_B` to it.
2. `append(x)`: Used to add element `x` at the end of the list.
3. `pop()`: Used to remove the last element of the list and return it.
4. `insert(i, x)`: Used to insert element at the specified index `i`
5. `remove(x)`: Removes the element `x` from the list and does not return it.
6. `reverse()`: Used to reverse the order of the elements of the lists.
7. `sort()`: Used to sort the elements of the list.(Elements must have the `<` operator defined).
8. `copy()`: Returns the entire list to be copied into another list variable.
9. `clear()`: Clears the content of the list.

## List Indices
1. We use the List Indices starting from 0 to `len(list) - 1` inside `[]` to access a specific element of the list.
```python
>>> friends[0]
'Aaditya'
```
2. We can use the negative numbers to access elements from the back of the list.
```python
>>> friends[-1]
'Ujjwal'
```
3. We can also use a colon to define a [[Chapter 9|range]] which returns an array in that range.
```python
>>> friends[1:3]
['Akshat', 'Anshu']
```

4. If we don't provide another index after the colon, the entire array starting from the first index to the final element is returned.
```python
>>> friends[1:]
['Akshat', 'Anshu', 'Ujjwal']
```
