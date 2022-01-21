import random

chars = """qwertyuiopasdfghjklzxcvbnmQWERTYUIOPASDFGHJKLZXCVBNM1234567890_-$%&#@!()-_=+\;:"*/"""

encrypted = ''.join(random.choice(chars) for x in range(34))

print(f"We have generated a encrypted password for you it's {encrypted}")
wait = input("What will it be used for")

f = open('encryptedpassword.txt', 'a')
f.write(wait + ' ' + '|' + ' ' + encrypted + '\n')
