# Python Practice

## Practice[7]


```python
====1====
def CalcBMI(height, weight):
    BMI = weight / (height ** 2)  
    print(f"Your BMI is: {BMI:.2f}")


h = float(input("Please enter your height in meters (e.g., 1.75): "))
w = float(input("Please enter your weight in kilograms (e.g., 65): "))

CalcBMI(h, w)

OUTPUT :
Please enter your height in meters (e.g., 1.75): 
1.75
Please enter your weight in kilograms (e.g., 65): 
65
Your BMI is: 21.22

---------------------------------------------------
====2====
import math as m

def Calc(A, B):
    results = (
        f"{'Operation':<20} {'Result A':<25} {'Result B':<25}\n"
        f"{'-' * 70}\n"
        f"{'tan':<20} {m.tan(A):<25} {m.tan(B):<25}\n"
        f"{'exp':<20} {m.exp(A):<25} {m.exp(B):<25}\n"
        f"{'radical':<20} {m.sqrt(A):<25} {m.sqrt(B):<25}\n"
        f"{'log':<20} {m.log(A) if A > 0 else 'undefined':<25} {m.log(B) if B > 0 else 'undefined':<25}\n"
        f"{'sin':<20} {m.sin(A):<25} {m.sin(B):<25}\n"
        f"{'cos':<20} {m.cos(A):<25} {m.cos(B):<25}\n"
        f"{'-' * 70}\n"
        f"{'A + B (Addition)':<30} {A + B}\n"
        f"{'A - B (Subtraction)':<30} {A - B}\n"
        f"{'A * B (Multiplication)':<30} {A * B}\n"
        f"{'A / B (Division)':<30} {A / B if B != 0 else 'undefined'}\n"
        f"{'A ^ B (Power)':<30} {A ** B}"
    )
    print(results)


A = int(input("Enter Num (1) : "))
B = int(input("Enter Num (2) : "))

Calc(A, B)

OUTPUT :
Enter Num (1) : 
1
Enter Num (2) : 
20
Operation            Result A                  Result B                 
----------------------------------------------------------------------
tan                  1.5574077246549023        2.237160944224742        
exp                  2.718281828459045         485165195.4097903        
radical              1.0                       4.47213595499958         
log                  0.0                       2.995732273553991        
sin                  0.8414709848078965        0.9129452507276277       
cos                  0.5403023058681398        0.40808206181339196      
----------------------------------------------------------------------
A + B (Addition)               21
A - B (Subtraction)            -19
A * B (Multiplication)         20
A / B (Division)               0.05
A ^ B (Power)                  1

---------------------------------------------------
====3====
import math

def function (x,y,z):
    print (math.sqrt((x-y)/z) + math.exp(x+y))
    
function (5,5,10)

OUTPUT : 22026.465794806718

---------------------------------------------------
====4====
import math

def function (r,x):
     y = r*x*(1-x)
     print(y)
function (20,10)

OUTPUT : -1800
---------------------------------------------------
====5====
import math

def function (w1,w2,k):
    y = w2-((w2-w1)/k)*k
    print(y)
    
function (6,2,10)

OUTPUT : 6.0
---------------------------------------------------
====6====
import math

def function (a,b,w1,w2):
     y = (1/(math.exp(a-b)+1))*(w2-w1)
     print(y)
     
function (10,20,6,8)

OUTPUT : 1.9999092042625952
---------------------------------------------------
====7====
import math

def function (f1,f2):
     y = ((f2-f1)/f2)
     print(y)
     
function (10,20)

OUTPUT : 0.5
