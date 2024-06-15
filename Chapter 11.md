Classes and objects form the basis of object oriented programming and are very important in programming. Many of the real world objects cannot be modelled with the basic data structures provided in Python so a class allows you to create a "Template" of a Data Type using the preexisting templates and an object is just an instance of this class Data Type.

The main parts of a class are as follows:
```python
# Class Declaration and Definition
class className:
	# Constructor
	def __init__(self, inp1, inp2):
		# Data members initialization
		self.attr1 = inp1
		self.attr2 = inp2
	
	# Member function definitions
	def meth1(self, [optional parameters]):
		# Code to be executed

# Object Declaration
object1 = className(x, y)
object1.meth1()
```
In the above example, we declare a class and then declare an object of `className` type. The class has two methods `__init__()` and `meth1()` .
1. `__init__()` is a special method which is executed only once whenever we declare an object of type `className`. Although in the declaration 3 parameters are required, the first parameter just represents the object being created so we only pass 2 parameters.
2. We then define the `meth1()` method as a general method with a non-optional parameter `self` which need not be passed while calling the function.

e.g. A model of **Rational Number** needs to be modelled in Python
```python
class Rational:
	def __init__(self, n, d):
		if d == 0
			raise(ValueError)
			return
		else:
			self.num = n
			self.denom = d
			return
```

