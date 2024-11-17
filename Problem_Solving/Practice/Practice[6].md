# Python Code Examples

## Practice[6]


```python

def function (a,b):
     y = (a+b) / 2
     return y

print(function (2,4))

# Output: 3.0
---------------------------------------------------
print("a"<"b")

# Output: True
---------------------------------------------------
print(",">="b")

# Output: False
--------------------------------------------------
print("x"<"a")

# Output: False
---------------------------------------------------
import math

def function (x):
    y = (math.exp(x)) + 1
    return y

print(function (5))

# Output: 149.4131591025766
---------------------------------------------------
def calc (a,b):
    print(f"* = {a*b},  / = {a/b} , + =  {a+b} , - = : {a-b}, ** = {a**b}")


calc (10 , 5)

# Output: * = 50,  / = 2.0 , + =  15 , - = : 5, ** = 100000
