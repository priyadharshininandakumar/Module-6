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
        self.__length = length  # Private variable
        self.__width = width    # Private variable
    
    def print_values(self):
        print(self.__length)
        print(self.__width)

rect = Rectangle(5, 3)
rect.print_values()
```

## Output
![WhatsApp Image 2025-12-27 at 11 17 55 PM](https://github.com/user-attachments/assets/0f084f22-f11b-469c-a821-647d348245ea)

## Result
Thus, the program is executed successfully.
