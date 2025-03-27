# dice
sg
import random

def guess_the_number():
    number = random.randint(1, 10)
    print("🎲 Welcome to 'Guess the Number'!")
    print("I'm thinking of a number between 1 and 10.")

    guess = int(input("Take a guess: "))

    if guess == number:
        print("🎉 You got it right! You win!")
    else:
        print(f"❌ Nope! I was thinking of {number}. Better luck next time!")

guess_the_number()
