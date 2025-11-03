# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math
class cse:
    def mech(r):
        a=math.pi*r*r
        print(f"Area of circle: {a:.2f}")
r=int(input())
cse.mech(r)
```
## Output
<img width="651" height="221" alt="Screenshot 2025-11-03 192118" src="https://github.com/user-attachments/assets/87d4362e-d55f-4450-bee3-2a97a02f8427" />

## Result
Thus,the program is executed successfully
