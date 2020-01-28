# Bootcamp Mentee-Python-Tema 1

import random
generated = random.randint (0,100)
print(generated)
guess = ""

while guess != generated:
    guess = float(input("Enter guess:"))
    if guess < generated:
        print("Caut un numar mai mare")
    elif guess > generated:
        print("Caut un numar mai mic")
    else:
        print("Corect!")
        break
        

