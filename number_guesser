# This is a guess the number game with python.

#This command imports the random module
import random
#This generates a random number between 1 and 10
unknownNumber = random.randint(1, 10)
print("I am thinking of a number between 1 and 10.")
# Ask the player to guess 6 times.
for guessesTaken in range(1, 7):
    print("Take a guess. You have " + str((7 - guessesTaken)) + " trials left to guess the right number!")
    guess = int(input())
    if guess < unknownNumber:
        print("Your guess is too low.")
    elif guess > unknownNumber:
        print("Your guess is too high.")
    else:
        break # This condition is the correct guess as the program breaks out of the loop once guess is correct!
if guess == unknownNumber:
    print("Good job! You guessed my number in " + str(guessesTaken) + " guesses!")
else:
    print("Nope. The number I was thinking of was " + str(unknownNumber))
