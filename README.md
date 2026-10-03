import random

number = random.randint(1, 100)
guess = int(input("Guess a number between 1 and 100: "))

if guess == number:
    print("Correct!")
else:
    print("Wrong, the number was", number)
