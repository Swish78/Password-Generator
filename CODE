import string
import random


def password_generator(n):
    password = string.ascii_letters + string.digits + string.punctuation
    print(''.join(random.choice(password) for i in range(n)))


Length = int(input("Enter number of minimum character your password requires: "))
password_generator(Length)
