# Python Code Examples

## Practice[10]


```python


def fact(n) :
    if(n <= 1) :
        return 1
    return n *fact(n-1)
    
fact(5)

OUTPUT : 120
---------------------------------------------------
def fib(n) :
    if(n == 1) :
        return 1
    elif(n <= 0) :
        return 0
    else :
        return fib(n-1) + fib(n-2)
    
fib(5)

OUTPUT : 5
---------------------------------------------------
def countUp(n) :
    print(n)
    if(n < 10) :
        return   countUp(n+1)
    else :
        print("END...")
    

countUp(1)

OUTPUT :
1
2
3
4
5
6
7
8
9
10
END...
---------------------------------------------------
