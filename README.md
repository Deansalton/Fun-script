# Fun-script
Just a silly little game, trying this out to see if I can get it to work here
command = ""
command = input('Any waves out there? (y/n)_ ')


import random

class Dice:
    def roll(self):
        first = random.randint(1, 6)
        return first

dice = Dice()
print (dice.roll())

if command == ('y'):
    input('Gnarly, say is that little wonkey? y/n:')
    if command == ('n'):
        print('Brah, its so good .. , time to paddle out for sure!!!')
elif command == ('y'):
              print('yeah, pretty micro.')

Skateboard = ""
skateboard =input('  ...(Some time later)... Woah brah.  is it about to rain?  __(y/n)')
if skateboard == ('y'):
    print('what?, skunked!!! denied the skate sesh for sure')
elif skateboard == ('n'):
    print ("Its on!!!  skate and destroy! fully session time!!  lets rip at prince park")
import random

while True:
    input("press enter to roll d20")
    d20 = random.randint(1,20)
    print(d20)
    if d20 == 1:
        print('dang brah, flat huh..  ')
    elif d20 == 20:
        print("Livin the California Dream")
