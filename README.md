# Dice-Roller
Don't have a dice... use this!!!

# You can reach out to me at tarunkramesh@gmail.com. Thank you for viewing!


import random

print("Don't have a dice, use this!!!")

try:
    amount = int(input("Please enter the amount of times would you like to roll: "))

    for item in range(amount):

        DICE = random.randint(1, 6)

        print(f"You rolled a: {DICE}!")

except ValueError:
    print("Please enter a valid value... ")
