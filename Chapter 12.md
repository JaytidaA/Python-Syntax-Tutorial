Inheritance is an important concept. It helps us reduce code by reusing the properties of the same classes in another class.

e.g.
```python
class Chef:
	def cook_salad():
		print("Chef cooks a salad.")
	
	def cook_special_dish():
		print("Chef cooks a Pizza")

# Here IndianChef is derived from Chef
class IndianChef(Chef):
	def cook_special_dish():
		print("Indian chef cooks Butter Chicken")

myChef = Chef()
myChef.cook_salad()
myChef.cook_special_dish()

myIndianChef = IndianChef()
myIndianChef.cook_salad()
myIndianChef.cook_special_dish()
```
Output:
```
Chef cooks a salad
Chef cooks a Pizza
Chef cooks a salad
Indian chef cooks Butter Chicken
```
Here, we have two classes `Chef` and `IndianChef`, where `Chef` is a general class and `IndianChef` is a derived class which inherits the properties of `Chef`.`IndianChef` also overloads the `cook_special_dish()` method of `Chef`. So instead of printing `Chef cooks a Pizza`, it will print `Indian chef cooks Butter Chicken`. 