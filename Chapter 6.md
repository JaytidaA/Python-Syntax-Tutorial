Dictionaries are a special data structure in Python used to store key-value pairs(sort of like a map).
\
```python
myDic = {
	"key_1": "value_1"
	"key_2": "value_2"
	"key_3": "value_3"
}

print(type(myDic))
print(myDic["key_2"])
print(myDic.get("key_4", "Invalid key!"))
```
Output:
```
<class 'dict'>
'value_2'
'Invalid key!'
```
