# Python Code Examples

## Practice[8]


```python


1)
import math

def func(a) :
    if(a<0):
        return 1/(math.exp(-a)+1)
    if(a>1):
        return 1/(1+math.exp(-a))
    else : return True

func(0)

OUTPUT : True
---------------------------------------------------
2)
import math as m
def func(a,b) :
    if(a>b):
        return m.sqrt((a**2-b**2))
    if(a<b):
        return m.sqrt((b**2-a**2))
    else : return a-b

func(4,3)

OUTPUT : 2.6457513110645907
---------------------------------------------------
3)
def func(a) :
    if(a>0):
        return "Positive"
    if(a<0):
        return "Negative"
    else : return "a = 0"

func(-4)

OUTPUT : Negative
---------------------------------------------------
def feetToCM(ft) :
    return (f"{30.48 * ft} CM")

feetToCM(5)

#OUTPUT : 152.4 CM
---------------------------------------------------
def fToC(f) :
    return (f"{(5 * (f-32))/9} C")
    
fToC(100)

OUTPUT : 37.77777777777778 C
---------------------------------------------------
def poundToGr(pound) :
    return (f"{453.59237 * pound} gr")


poundToGr(5)

OUTPUT : 2267.96185 gr
---------------------------------------------------
def PositiveNum(Num) :
    if(Num > 0) : 
        return Num
    elif(Num < 0) :
        return Num * -1
    else :
        return "Enter Positive Or Negative Number"
    
PositiveNum(-3)

OUTPUT : 3
