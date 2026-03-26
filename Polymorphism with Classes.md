# # 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program
```
class Beans(): 
    def type(self):
        print("Vegetable")
    def color(self):
        print("Green")
class Mango(): 
    def type(self):
        print("Fruit")
    def color(self):
        print("Yellow")
    
def func(obj):
    obj.type()
    obj.color()
b=Beans()
m=Mango()
func(b)
func(m)
```
## Output

<img width="968" height="252" alt="530467575-4e28c508-2100-4026-b75b-13895d67a6be" src="https://github.com/user-attachments/assets/a8a2c783-a007-4730-8a59-007b5c1602c2" />

## Result
Thus,the program is executed successfully.
