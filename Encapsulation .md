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
```
class Rectangle:
    def __init__(self, length, width):
        self.__length = length 
        self.__width = width  
    def print_inside(self):
        print(self.__length)
        print(self.__width)
    def get_length(self):
        return self.__length
    def get_width(self):
        return self.__width
r = Rectangle(5, 3)
print(r.get_length())
print(r.get_width())
```
## Output

<img width="287" height="147" alt="530467097-43f2e635-4521-48d2-b91c-0b3cff862647" src="https://github.com/user-attachments/assets/835c776a-63bf-465d-ac81-97691e2c06d9" />


## Result
Thus, the program is executed successfully.
