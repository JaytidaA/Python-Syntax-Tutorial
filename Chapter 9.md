Ranges are a special data structure implemented in Python in order to be used for indexing variables. They are generated using the `range()` method.
```python
sequence = range(i, j, k)
```
Creates a sequence of integers starting from `i`, ending at `j - 1` and having `k` as step-size. By default, `i = 0` and `k = 1`.
e.g.
```python
>>> seq = range(10)
>>> print(seq)
range(0, 10)
```

e.g.
```python
>>> seq = range(1, 5, 2)
>>> len(seq)
2

>>> print(seq[0])
1
>>> print(seq[1])
3
```