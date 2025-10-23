# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
~~~
class Rectangle:
    def __init__(self, length, breadth):
        self.__length = length
        self.__breadth = breadth

    def display_dimensions(self):
        print("Length:", self.__length)
        print("Breadth:", self.__breadth)

    def calculate_area(self):
        return self.__length * self.__breadth

my_rectangle = Rectangle(20, 4)

print("Area:", my_rectangle.calculate_area())

my_rectangle.display_dimensions()

# print(my_rectangle.__length)
~~~
## Output

## Result
Thus, the program has been executed successfully.