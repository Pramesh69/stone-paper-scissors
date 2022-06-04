# stone-paper-scissors program 


import random
p = input("Enter a choice (rock, paper, scissors):\n ")
n = ["rock", "paper", "scissors"]
c = random.choice(n)
print(f"\nYou chose {p}, computer chose {c}.\n")

if p == c:
    print("Both players selected {p}. It's a tie!")
elif p == "rock":
    if c == "scissors":
        print("Rock smashes scissors! You win!")
    else:
        print("Paper covers rock! You lose.")
elif p == "paper":
    if c== "rock":
        print("Paper covers rock! You win!")
    else:
        print("Scissors cuts paper! You lose.")
elif p == "scissors":
    if c == "paper":
        print("Scissors cuts paper! You win!")
    else:
        print("Rock smashes scissors! You lose.")
