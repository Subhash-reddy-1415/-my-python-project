import random
print("WELCOME TO ROCK PAPER SCISSOR Game:")
user_move=input("ENTER YOUR CHOICE=")
user_move=user_move.lower()
choices=["rock","paper","scissor"]
computer_move=random.choice(choices)
print("THE COMPUTER MOVE IS=",computer_move)
if user_move not in choices:
    print("INVALID CHOICE")
elif user_move==computer_move:
    print("MATCH TIE")
elif user_move=="rock" and computer_move=="scissor":
    print("YOU WIN")
elif user_move=="paper" and computer_move=="rock":
     print("YOU WIN")
elif user_move=="scissor" and computer_move=="paper":
    print("YOU WIN")
else:
    print("COMPUTER WINS")
