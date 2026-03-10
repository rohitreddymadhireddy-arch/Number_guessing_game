# Number_guessing_game
import random

number = random.randint(1,100)

while True:
    guess = int(input("Guess the number: "))

    if guess > number:
        print("Too high")
    elif guess < number:
        print("Too low")
    else:
        print("You win!")
        break
