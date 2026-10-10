
import random
import string
import math

# QUESTION 1: PASSWORD GENERATOR

def make_password(length=8):
    characters = string.ascii_letters + string.digits
    password = ""
    for i in range(length):
        password += random.choice(characters)
    return password

print("QUESTION 1: PASSWORD GENERATOR")

p1 = make_password()
p2 = make_password(12)

print("Password:", p1)
print("Length:", len(p1))
print("Password:", p2)
print("Length:", len(p2))


# QUESTION 2: YOUR OWN MODULE

def tables_needed(people, seats):
    return math.ceil(people / seats)

def welcome(name):
    return f"Welcome to PLP, {name}!"


# MAIN PROGRAM OUTPUT

print("\nQUESTION 2: YOUR OWN MODULE")
print(welcome("Amina"))
print(tables_needed(47, 6))
print(tables_needed(20, 5))


# HELPERS.PY STANDALONE OUTPUT

if __name__ == "__main__":
    print("\nHELPERS.PY OUTPUT")
    print(tables_needed(10, 4))
