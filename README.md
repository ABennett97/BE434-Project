# BE434-Project
Hello everyone, for my final project I wanted to attempt writing a simple number guessing game.

## Number guessing game
This is one of the simplest games that can be coded for in python, it can be found as `guess_game.py`. The objective of the game is to guess a randomly generated number by the code. 
The code starts by asking the user to enter a number between 1 and 100. If the number the user enters is lower or higher than the random number the program lets them know with 
a print statement:

`print(guess, 'is too small\n')` or `print(guess, 'is too large')`

The code allows for multiple attempts to guess until the user guesses the number correctly by using a while loop:

`while guess != ran_num:
       if guess < ran_num:
            ...
       if guess > ran_num:
            ...`

The code also keeps track of how many guess attempts the user has used within the while loop. Once the user has successfully guessed the number the program congratulates them with
one final print statement:

`print('Congrats! You got it in', attempt, 'guesses!')`

It really is a simple but fun game. 
