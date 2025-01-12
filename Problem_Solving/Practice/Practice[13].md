Python Code Examples

## Practice[13]


```python

fact = 1
for i in range(1,4):
    fact = fact * i
    print(fact)

OUTPUT : 
1
2
6
---------------------------------------------------
text = "lol"
reversedText = ""
for i in text :
    reversedText = i + reversedText
if(text == reversedText) :
    print("Palindrome")
else :
    print("NoPalindrome")


OUTPUT : Palindrome
---------------------------------------------------
num = int(input("Enter Number : "))
while(num > 0):
    num -= 1
    print(num)

OUTPUT : 
10
9
8
7
6
5
4
3
2
1
0
---------------------------------------------------
