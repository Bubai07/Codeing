import random

while True:
    choice = input("Roll the Dice? (y/n): ").lower()
    if choice == "y":
        Dice1 = random.randint(1, 6)
        Dice2 = random.randint(1, 6)
        print(f"({Dice1},{Dice2})")
    elif choice == "n":
        print("Thank you for playing! Bubai")
        break
    else:
        print("Invalid input")
