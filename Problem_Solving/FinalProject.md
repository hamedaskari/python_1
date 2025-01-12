# Python Final Project

## Guess Number


```python

import random

random_number = random.randint(1, 10)
guess = None

print("Guess the number! It's between 1 and 10.")


while guess != random_number:
    guess = int(input("Your guess: "))
    
    if guess < random_number:
        print(f"Number Grader Than {guess}")
    elif guess > random_number:
        print(f"Number Lower Than {guess}")
    else:
        print("Correct!!...")
