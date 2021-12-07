import random

dice_1 = [1, 2, 3, 4, 5, 6]
dice_2 = [1, 2, 3, 4, 5, 6]

def game(dice_1, dice_2):
        roll1 = random.choice(dice_1)
        roll2 = random.choice(dice_2)
        total = roll1 + roll2
        throw = input("""=========================
PRESS ENTER TO ROLL DICE
=========================\n""")
        if total >= 7 and total <= 11:
            print(f'Nice roll you hit a {roll1} and a {roll2} thats a total of {total}.')
        elif total <= 6:
            print(f'That was meh... You hit a {roll1} and a {roll2}. THAT SUCKS!')
        elif total == 12:
            print('Double 6???? CRAZYYY LUCK')
        replay = input('\nPRESS ENTER TO PLAY AGAIN (ELSE TYPE QUIT)\n')
        if replay.lower() == 'quit':
            exit()
        else:
            game(dice_1, dice_2)
game(dice_1, dice_2)
