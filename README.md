# Yash_nuthanapati
This project is a fun Guess the Number game where the program generates a random number and the player attempts to guess it. The game gives feedback after each guess (higher or lower) to help the player find the correct number within a set number of attempts.

secret = 9
guess = 0

while guess != secret:
    guess = int(input("Guess the number: "))

    if guess < secret:
        print("Too low")

    elif guess > secret:
        print("Too high")

print("Correct!")
