# Cirumference-and-Area-of-Circle

import math

def Diameter():
    return 2 * radius

def Circumference():
    return 2 * math.pi * radius

def Area():
    return math.pi * radius * radius

radius = float(input("Please enter the radius of a circle: "))

diameter = Diameter()
circumference = Circumference()
area = Area()

print("Diameter Of a Circle =",diameter)
print("Circumference Of a Circle =",circumference)
print("Area Of a Circle =",area)
