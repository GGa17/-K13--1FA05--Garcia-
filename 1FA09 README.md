"""
Student reflection
The math library helps you use math operations like the square root, exponents, and etc. 
The math library makes these operations more doable to do on code,
and also make it easier and less troublesome to try to use square roots, exponents, and many more in your code.
The math Library is incredibly useful if you want to reduce the ammount of workload that you need to code, 
just like the code below if I didn't use the math library it would take many more lines of code just to achevieve the same result.
"""





import math

x1 = float(input("Enter x1: "))
y1 = float(input("Enter y1: "))

x2 = float(input("Enter x2: "))
y2 = float(input("Enter y2: "))

distance = math.sqrt(math.pow(x2 - x1, 2) + math.pow(y2 - y1, 2))

print("The distance between the two points is:", distance)
