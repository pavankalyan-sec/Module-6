# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program
~~~
class Box:
    def __init__(self,a):
        self.a = a
    def __lt__(self, o):
        return self.a < o.a
box1 = Box(100)
box2 = Box(150)
if box1 < box2:
    print("Box 1 is smaller than Box 2.")
else:
    print("Box 1 is not smaller than Box 2.
~~~
## Output
<img width="915" height="107" alt="image" src="https://github.com/user-attachments/assets/a5413cff-844a-43f1-9e0b-b13bf0c32f5b" />

## Result
Thus,the program has been executed successfully.
