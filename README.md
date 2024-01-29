# hw1pr3
homework 1 part 3

import random          # imports the library named random

def rps():
    """ this plays a game of rock-paper-scissors
        (or a variant of that game)
        arguments: no arguments    (prompted text doesn't count as an argument)
        results: no results        (printing doesn't count as a result)
    """
    user = input("Choose your weapon: ")
    comp = random.choice(['rock','paper','scissors'])
    print()

    print('The user (you)   chose', user)
    print('The computer (I) chose', comp)
    print()

    if user == comp:
        print('you tied :/')
    elif user == 'rock' and comp == 'paper':
        print('you loose :(')
    elif user == 'rock' and comp == 'scissors':
        print('you win :)')
    elif user == 'paper' and comp == 'scissors':
        print('you loose :(')
    elif user == 'paper' and comp == 'rock':
        print('you win :)')
    elif user == 'scissors' and comp == 'rock':
        print('you loose :(')
    elif user == 'scissors' and comp == 'paper':
        print('you win :)')  
    print()

    if user == 'paper':
        print('paper? i hardly know her!')
    elif user == 'rock':
        print('you "rock"...')
    elif user == 'scissors' :
        print("insert_scissors_joke_here")
    else :
        print('check your spelling...')
    print()
    print('thanks for playing :)')
