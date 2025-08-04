# Python FAQs

### 1. What is the `__init__` method?
> The `__init__` method is a special instance method that runs automatically when a new object of a class is created.

### 2. What is the `self` keyword?
> `self` refers to the instance on which a method is called, letting you access its attributes and methods
```python
class Dog:
  def __init__(self, name):
    # will store the name of the particular instance
    self.name = name

  def bark(self):
    print(f"{self.name} says 'woof'!")

dog1 = Dog("Osvi")

print(dog1.bark()) #osvi says 'woof'! 
    
